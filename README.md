# Beat Saber Version Control

This repo contains information on

> How to manage manage your Beat Saber copies with Git (Not `GitHub`)

## How To

Please refer to the [Wiki](./wiki)

## Pros and Cons

Um... Yes, but why?  
Here are common ways people handle their Beat Saber versions.
Below lists the pros and cons for each methods.

| Methods            | Pros                                                                                                                                               | Cons                                                                                                                                                    |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| Git                | - Easy to setup<br>- Easy to switch version<br>- Smaller backup size<br>- Can also manage your game settings<br>- All files sits in the same place | - Game size grows for each version and cannot be removed easily                                                                                         |
| Manually           | - No brainer<br>- Mostly working                                                                                                                   | - Large file size for duplicates of songs<br>- Changing setup requires backup of whole game again                                                       |
| Manually (Symlink) | - Mostly working                                                                                                                                   | - Requires some technical knowledge for the setup<br>- Changing setup requires backup of whole game again                                               |
| BSLegacy           | - Not affected by Steam Update<br>- Ability to backup OS settings<br>- Easy to switch version<br>- Can download any version                        | - Setup requires manually linking each common folder<br>- Cannot use SteamVR to launch the game<br>- Mod installation starts from zero for each version |
