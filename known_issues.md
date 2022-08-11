# Known Issues

Below is a list of currently known issues and their progress on development.

For any other issues regarding the Modlist that are not already listed, please report them via either the [GitHub Issues](https://github.com/Rage-GitHub/Atomic-Warfare/issues) page or within the Discord's Atomic Warfare [#bug-reports](https://discordapp.com/channels/1005978270409437215/1006002360931336254) channel.

## In-Progress


  - Ocassionally caused by the Modlist not being installed on the same drive as Fallotu 4.

## Planned

- Screen flashbanging on initial save startup, I.E. your screen will gradually grow brighter and audio bugs out (Can be fixed by reloading the save)
  - Temporary solution is to pause the game, save, exit to main menu then reload that save.

## Looking At

-

## Fixed

- General Issues Fixed
  - [#2](https://github.com/Rage-GitHub/Atomic-Warfare/issues/2#issuecomment-1211060096) Widescreen users utilizing the LevelUpMenuEx mod can not use [TRUBY9 Ultrawide](https://www.nexusmods.com/fallout4/mods/24630) as it will cause crashes
    - Simply avoid the use of a Widescreen mod for now, or expiriment and use a different Widescreen mod.

- Implemented in 1.2.0
  - Missing/Broken textures in Concord Museum resulting in combining or completely gone textures
  - Micro stuttering when wandering around randomly, causing huge influxes in the FPS.
    - Potentially fixed, please revise and report back if the issue persists.
  - Unable to launch from Fallout 4 Script Extender executable, providing an error that points to Root Builder.
    - Fixed by running Root Builder and creating your own Root Builder cache and data. See [Wiki](https://github.com/Rage-GitHub/Atomic-Warfare/wiki/Prerequisities-Before-Beginning#building-root-directory-files) for more information.
