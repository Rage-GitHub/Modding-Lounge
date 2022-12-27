# Valheim Modding Tools

Valheim Modding Tools, VMT for short,  is a great modding resource for modlist authors who wish to make their own modlist for Valheim. It provides an easy, straightforward modding experience that is simple enough to install a few mods and get them running.

## Features

Some of the greatest feats this modlist achieves are:

- Straightforward and basic modding setup for Valheim mods
- Automatic Nexus download support and mod installation
- Quick and easy mod configurations setup
- And more!

## Notes

Due to the way Valheim modding support is handled as of right now, a testing build for Mod Organizer 2.5.0 alpha 6 is currently being used, so do be aware that issues may be prevalent. Valheim mod installation support isn't always automatically handled, so mods may require some more assembly before fully integrating them into the modlist.

### Correcting Mod Installations

Some mods may not have the right folder structure setup for Mod Organizer to handle, such as if a mods **.dll** file, aka the plugin, is located directly in the base of the archive, it needs to be specified into the right folder structure.

An example of this would be Odin Ship, which as of 12/26/2022, has the .dll file directly in the base of the archive, causing MO2 to not see it as a valid mod installation.

To fix this, inside of the Install Mods popup when installing a new mod, right-click on the **<valheim>** directory, select **Create directory...** and call it BepInEx. Inside of the BepInEx folder, right-click it and replicate the same thing but call this one **Plugins**. Any files that are present in the archive, move into the Plugins folder. For our case, it would be moving the OdinShip folder into Plugins. Files such as **icon.png**, **mainfest.json**, or **README.md** can be unticked and removed from the installation.

If a mod comes shipped with a config file, create a folder under the BepInEx folder called **Configs** and move them into there.

Your folder structure should look as follows:

```Plain
↳ <valheim>
  ↳ BepInEx
    ↳ Plugins
      ↳ OdinShip
    ↳ Configs
```

### Mod Config Files

Mod configuration files are usually included in the mod installation, which may be an issue if you plan on editing and configuring mods. To resolve this, I've included a **Configuration Files** empty mod, which already has the configuration files for the necessary mods, that can be used for mods and overwriting a mods config files and included it as part of the compiled Wabbajack installation file.

Whenever you install a new mod, make sure that the configuration files from that mod are placed inside of the **Configuration Files** mod folder to overwrite and allow you to configure it.

### Installing Mods from Thunderstore (For Wabbajack Modlists)

If you plan on installing mods from Thunderstore, you can simply do so by downloading each mod manually, then adding the correct meta information for the installation. To do so, simply right-click the **Manual Download** button when installing a mod.

In MO2, drag and drop the archive you manually downloaded from Thunderstore into the MO2 downloads tab for MO2 to recognize it as a installed mod, and then right-click that mod and click **Open meta file**. Inside of that document, delete everything and copy and paste the text below inside:

```Meta
[General]
installed=true
uninstalled=false
directURL=<thunderstore link>
removed=true
```

With that link you copied from Thunderstore, paste it in directly after the `directURL=` value, replacing `<thunderstore link>`.
