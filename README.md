# Table of Contents
1. [Welcome to Atomic Warfare](https://github.com/Rage-GitHub/Atomic-Warfare#welcome-to-atomic-warfare)
    - [Main Takeaways](https://github.com/Rage-GitHub/Atomic-Warfare#main-takeaways)
      - [Quests and Adventures](https://github.com/Rage-GitHub/Atomic-Warfare#quests-and-adventures)
      - [Noticeable Features](https://github.com/Rage-GitHub/Atomic-Warfare#noticeable-features)
    - [Other Things to Notes](https://github.com/Rage-GitHub/Atomic-Warfare#other-things-to-note)
      - [Best Practices](https://github.com/Rage-GitHub/Atomic-Warfare#best-practices)
2. [Prerequisites Before Beginning](https://github.com/Rage-GitHub/Atomic-Warfare#prerequisites-before-beginning)
    - [Installing the Modlist via Wabbajack](https://github.com/Rage-GitHub/Atomic-Warfare#installing-the-modlist-via-wabbajack)
    - [Changing INI Core Count Variable](https://github.com/Rage-GitHub/Atomic-Warfare#changing-ini-core-count-variable)
    - [Enabling/Disabling Optional Mods](https://github.com/Rage-GitHub/Atomic-Warfare#enabling-/-disabling-optional-mods)
3. [In-Game Settings](https://github.com/Rage-GitHub/Atomic-Warfare#in-game-setings)
    - [MCM Settings Manager](https://github.com/Rage-GitHub/Atomic-Warfare#mcm-settings-manager)
4. [Hardware Specifications](https://github.com/Rage-GitHub/Atomic-Warfare#hardware-specifications)
    - [Minimum Specifications](https://github.com/Rage-GitHub/Atomic-Warfare#minimum-specifications)
    - [Personal Specifications](https://github.com/Rage-GitHub/Atomic-Warfare#personal-specifications)

# Welcome to Atomic Warfare

Atomic Warfare is a comprehensive modlist that focuses on improving over the Vanilla Fallout 4 with better mechanics, additional content to explore, and an overall immersive experience.

For support and live chat, visit my [personal Discord](http://discord.gg/fEBJYFnKsp). You can also find me actively messaging and maintaining more information there about the modlist and other mods I have available.

For known issues and progress, visit the GitHub [Known Issues.md](https://github.com/Rage-GitHub/Atomic-Warfare/blob/main/known_issues.md) file. Report any issues via the [GitHub page](https://github.com/Rage-GitHub/Atomic-Warfare/issues) using the **Bug Report** template provided.

For any current issues, please read the [Known Issues.md](known_issues.md) file.

# Main Takeaways
Atomic Warfare provides an overall balanced and fair content to performance ratio, allowing for a wide variety of visuals to appear while also not sacrificing your FPS to the FPS Gods. With this, a lot of really great and popular Quest mods, such Fourville, Old Time Religion, Point Lookout and more have been featured within this Collection.

### Quests and Adventures
- Fourville
- Fallout 4: Point Lookout
- Miami Misadventures: Episode 1
- Nuka World Plus
- Old Time Religion
- Tales from the Commonwealth (And it's Addons)

### Noticeable Features
- Vastly improved gunplay, allowing diverse ways to take out your enemy such as new leaning mechanics, real bullet projectiles, cleaner, more realistic headsets and overall a harsher way to survive.
- Survival needs without the need of the Survival gamemode and it's restrictions, allowing you to truly control how you want your survival playthrough to be.
- Lots of amazing Capital Wasteland and New Vegas content, offering a lore-friendly(ish) way of introducing content from the two other amazing wasteland adventures
- Luscious and overhauled visuals for the maximum fidelity without compromise to give you the freedom of exploring the game like it was vanilla without the loss of vanilla.
- Specifically chosen game tweaks to provide the best and most optimized experience for Fallout 4 there is, with hundreds of mods running simultaneously.

I've been tweaking and making necessary changes to optimize Fallout 4 to the best of it's capability, while retaining fidelity to offer the best visual to performance ratio. An example of Downtown Boston, near Goodneighbor, which is usually the most taxing location can be seen in the media.

## Other Things to Note
I'm looking for comparisons on other systems to see how well the game runs, so I can manage and fine-tweak more settings to help the majority of users. Share your Specs, average framerates and locations of specific areas hurting your FPS in the discussions tab.

Regarding Undeducated Shooter, the mod utilizes the Q and E button, meaning E is overriden by the mod which you will have to rebind the Activate button to something else like F.

### Requirements
- Clean Fallout 4 Install
- All Fallout 4 DLC
- [FO4Edit](https://www.nexusmods.com/fallout4/mods/2737/?tab=files)
- [BethINI](https://www.nexusmods.com/fallout4/mods/2737/?tab=files)

### Best practices
Avoid from editing the modlist too much, everything is changed for a reason. If you choose to edit it, support is not provided and you will be ignored.

# Prerequisites Before Beginning

### Cleaning Game Files
Modlists from Wabbajack generally require a clean installation of Fallout 4 and no mods installed whatsoever. For this reason, before you install anything, perform a clean installation of Fallout 4. To do so, follow these steps:

Locate your games directory, right-click the game folder and hit delete
Navigate to Documents > MyGames and delete the Fallout4 folder
Go back to your launcher, then reinstall Fallout 4.
Once it's installed, boot the game up and let the launcher load default values

It is highly recommended, if at all, required for you to install Fallout 4 outside of your C: drive and somewhere on another drive like an SSD or M.2. This will substantially help in load times, file redundancy and generally good practices.

### Installing the Modlist via Wabbajack
Now that you've performed a clean install for Fallout 4 and generated all of the necessary files, it's time to install the modlist itself. 

To begin, go to the a new drive location (Same location to where Fallout 4 is installed), I.E. the base directory for a drive, create a new folder and call it whatever you please, Wabbajack ideally. Inside of that folder, download the Wabbajack tool itself and run it inside of that folder. Create a new folder inside of the Wabbajack directory and call it Modlists.

The folder structure should look as follows:

```
Wabbajack (Make This)
┗ Downloads (Make This)
┗ Modlists (Make This)
  ┗ Atomic Warfare (Automatically Made by Wabbajack) 
    ┗ (Wabbajack Files Will Download Here)
```

Now, launch Wabbajack and download the Wabbajack file from the Files tab on Nexus and click the Install From Drive button in Wabbajack. Locate the Wabbajack file and click open. Choose the install location inside of the Modlists folder you created above earlier. You can specify the download location for the wabbajack mods to install to another location if you choose. Once finished, hit the button to the right and it will begin downloading everything needed.

### Changing INI Core Count Variable
There is a core count variable called `iNumHWThreads=6` set within the **Fallout4Custom.ini** file under the `[General]` section. Change this value to the amount of PHYSICAL cores your have, I.E. if it's a 6 Core 12 Thread CPU, you set the value to 6 and not 12. 

This can help accelerate script loading as well as rendering assets needed rendered from the GPU, allowing for more optimal performance.

### Optimizing INIs to Your Hardware
Generally, INIs are shipped with predefined variables. For this case, the modlist is shipped with the High preset defined by BethINI. This can be changed if you can not run the BethINI High preset. 

With Mod Organizer closed, launch open BethINI. In the setup tab, make sure all of the locations are pointed to the correct directory, I.E. the INI path to your **Documents > MyGames > Fallout4** folder. 

In BethINI, set the resolution to your current display's resolution, choose the Preset given by default when you launch the Fallout 4 Launcher, and hit Recommended Tweaks. Save and Exit.

Make sure that in the Fallout4Custom.ini, which can be edited from Mod Organizer using the INI Editor in the Puzzle Piece Dropdown, that these values match as follows:

```
[Decals]
bDecals=1
bSkinnedDecals=1
uMaxSkinDecalPerActor=5
uMaxSkinDecals=10

[Display]
bDynamicObjectQueryManager=1 
bMultiThreadedRendering=1 
bMultiThreadedAccumulation=1 
bMultiThreadedRenderingUNP=1
fSAOBias=0.6
fSAOIntensity=7.1
fSAORadius=108.2

[General]
iTextureDegradeDistance0=1600
iTextureDegradeDistance1=3000
iTextureUpgradeDistance0=1200
iTextureUpgradeDistance1=2400
sStartingConsoleCommand=bat stealth;bat godrays;bat cl
```

### Enabling/Disabling Optional Mods
Some mods within this modlist aren't entirely required, but recommended to fit with the modlist style. However, if these mods don't fit your needs or wants, you can simply disable them.

Find below the list of optional mods you can disable below:
- Fallout 4 HD Overhaul (Separate Wabbajack File for Avoiding This Download)
- FallUI Collection (If you disable the Item Sorter mod, disable the Inventory one as well)
- LC and CC Texture Mods (No need to rebuild LODs or anything, just disable them)
- LevelUpMenuEx
- PipBoyTabs
- Thaylar's Armor and Clothing Enhanced
- Uneducated Shooter (Disable within Mod Organizer)

# In-Game Settings
### MCM Settings Manager
With the Modlist comes a prepared MCM Settings file, allowing you to use the already configured options for many of the mods in the MCM to fit the Modlist even more.

To use these settings, simply navigate to the Mod Configuration Menu and then go to MCM Settings Manager. Find the Atomic Warfare option, then click Apply. Close out of the MCM menu, save the game and reload that save.

If you choose to not use these settings, just note that some mods are intentionally edited for the sole purpose of conflicts such as An76 and Wasteland Ballistics.

### Custom HUD Replacer
With the modlist, comes provided my own custom made preset for FallUI HUD. It is, in my opinion, the best HUD preset there is that doesn't intrude too much on the necessary information and mechanics of the interface while providing an entirely new look. 

There are two options for this HUD, a Hardcore mode, which removes things like reticles, enemy dots on the compass, ammo counter, etc. and then there is the default one which is everything but stylized how I designed the HUD to look.

# Hardware Specifications

Ideally, you want a computer with a great CPU and lots of VRAM, if you choose to run lots of texture mods. Fallout 4 will occasionally take up a lot of GPU and CPU so anything that's at least these recommended specs or above should compute. For a referenced setup from what I am running this collection on, see the Personal Specifications section below.

### Minimum Specifications
| Type | Hardware |
| --- | --- |
| GPU | NVIDIA GeForce GTX 1660Ti  |
| CPU | AMD Ryzen 5 2600X 6-Core |
| RAM | 8GB DDR4 |

### Personal Specifications
| Type | Hardware |
| --- | --- |
| GPU | NVIDIA GeForce RTX 3070Ti |
| CPU | AMD Ryzen 9 5900X 12-Core |
| RAM | Corsair Vengeance RGB PRO 32GB DDR4 |