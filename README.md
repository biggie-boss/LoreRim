# LoreRim - A Modern Action RPG

![banner image](https://staticdelivery.nexusmods.com/mods/1704/images/112590/112590-1708904333-195281047.png))

Wabbajack Modlist Installer by biggie_boss.

<table stlyle="border: none;">
<tr>
<td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/112590">Nexus Page</a></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><a href="https://loadorderlibrary.com/lists/lorerim">Load Order Library</a></td>
<td><a href="https://discord.gg/Tb5ETzBYjd"><img alt="Discord" src="https://cdn.logojoy.com/wp-content/uploads/20210422095037/discord-mascot.png" width="64px" ></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Preamble

**LoreRim** is complete overhaul of Skyrim Anniversary Edition, designed to modernize the visuals and combat of the game while also staying true to lore and bringing back gameplay mechanics from previous games. This modlist is heavily focused on immersion, role-playing and progression.

The main gameplay overhaul in LoreRim is Requiem. Requiem completely delevels the world of Skyrim and encourages careful preperation before combat. Attack - Modern Combat Overhaul provides a basis to revamp third person combat and new animations are included for both first and third person combined with a stance system, allowing players to choose their favorite animation style.

There are multiple EnaiRim mods included to help counter Requiem's default harshness. Growl, Sacrilege, Wintersun Faiths and Apocalypse Magic are all at your disposal.

This list is challenging but it is up to you, the player, to overcome those challenges and become the Dragonborn of Legend. Each level, you will get stronger than the level before. 

## System Requirements

### Disclaimer

Owing to the need to clean master files and certain errors with Wabbajack, LoreRim only supports **English Steam** versions of Skyrim Anniversary Edition. **GOG and other Languages are not supported**. The specific version used is 1.5.97 with the creation club content from 1.6.1170.

:warning: :exclamation: **LORERIM REQUIRES THE FULL PAID UPDATE TO SKYRIM ANNIVERSARY EDITION. IT IS NOT/WILL NOT BE MADE COMPATIBLE WITH THE NON PAID UPDATE OR OLDER VERSIONS** :exclamation: :warning:

***

Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your windows version **must be 21H2 or newer** to run both Wabbajack and LoreRim.

Running the list from Hard Disk Drives or external drives is **STRONGLY ADVISED AGAINST**. A lot of content is swapped at game run time and, as a result, fast storage and RAM are needed.

### Recommended System Requirements

LoreRim requires a mid-tier modern system to run to its fullest potential. The recommended specs given below are based on utilizing the ENB in the list. For community shaders, you can subtract a little bit from them. Users have reported being able to run on hardware slightly lower than this, however your mileage may vary.

| Component    | Recommended for 1080p | 
|:--------------:|:-------------:|
| CPU | 10th Generation i5 or better/equivalent
| Ram | 16GB DDR4 Ram  + 40GB Pagefile 
| Storage | SATA SSD or higher
| GPU | RTX 3060 or better/equivalent

| Component    | Recommended for 1440p | 
|:--------------:|:-------------:|
| CPU | 12th Generation i7 or better/equivalent
| Ram | 32GB DDR4 Ram  + 40GB Pagefile 
| Storage | M.2 SSD
| GPU | RTX 4070 or better/equivalent

Space required: ~300GB Download Size ~250GB install Size ~550GB Total

See how to setup a page file here: https://www.tomshardware.com/news/how-to-manage-virtual-memory-pagefile-windows-10,36929.html

:warning: **NOTE**: AMD RX 580 and older cards are **not supported**. :warning:

## Installation

Installing LoreRim is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing LoreRim, please complete the following steps.


1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64]([https://dotnet.microsoft.com/download/dotnet/5.0/runtime](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Launch the game to the main menu and allow it to download the paid addon files. **DO NOT VERIFY YOUR GAME FILES**
8. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.
9. **Install the Skyrim Special Edition: Creation Kit on Steam and run it at least once.**

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

:warning: **NOTE**: LoreRim will **always** require the latest version of Wabbajack **UNLESS IT IS SPECIFICALLY STATED HERE**. :warning:

#### Downloading and Installing LoreRim

Downloading and installing LoreRim can take a while depending on your internet connection and computer. To install LoreRim, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on LoreRim and wait for it to download.
3. Set the installation folder to be somewhere like C:\LoreRim. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run Wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
    - **Make sure you have downloaded all the Paid AE update content!**
	- Make sure you have the Creation Kit installed. Go back to [Pre-Installation](#pre-installation) and read it properly this time.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Stock Game & Root Builder

LoreRim utilizes a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Skyrim installation within the installation location of the list. This enables greater compatibility with other mod-lists.

LoreRim also utilizes Root Builder alongside Stock Game to enable easier management of hooks such as ENB, Reshade and Engine Fixes. Please see our guide to [Root Builder](https://github.com/The-Animonculory/Modding-Resources/blob/main/Root%20Builder%20for%20Skyrim%20AE.md) for more details.
***

### OPTIONAL MODS - ULTRAWIDE SUPPORT & PERFORMANCE

**If you do not have an RTX Graphics Card it is CRUCIAL that you DISABLE the DLAA mod located towards the bottom of the load order.**

LoreRim comes with several list customization options. There is ultrawide support under the "Widescreen Support" section of Mod Organizer 2. There are several ENB presets to choose from ONLY CLICK ONE OPTION AT A TIME.

If you need a boost in FPS, you can choose the performance profile from the Profile dropdown in MO2.

**NOTE**: Screenshots save to `Overwrite\Stock Game`.

### Starting up the list
Open the installation folder and double-click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `LoreRim` and press the `Run` button.

### In-game MCM options

LoreRim has no required MCM options to be selected; however, you can load the smoothcam preset if you wish to do so.

You are welcome to change any others to achieve your desired setup.

### Starting the Game & Important Information

After creating your character, you will be given an option to use 25 tokens to pick starting gear. You also have a "Choose Birthsign" Power that lets you choose a starting Birthsign (replaces standing stones). 

MAKE SURE TO OPEN UP YOUR INVENTORY TO INITIALIZE REQUIREM STARTUP BEFORE LEAVING THE STARTING CAVE.

After you leave the cave, you will be given a choice to follow a starting diety. It is recommended you listen to Hadvar/Ralof's full dialogue before leaving the area. 

### Default Hotkeys

For INI related controlls, please see https://ck.uesp.net/wiki/Input_Script

Pressing F11 opens up a controller map.

Left Alt - Dodge (Changed via TK Dodge Re.ini IN THE "LoreRim - MCM and INI Settings" **MOD** - PLEASE READ IT IS THE MOD AND NOT IN-GAME MCM!!!) If you activate the controller config mod, there is a TK Dodge.ini file in there as well that you'll have to change instead.

V - Dual Parry (Changed via DualWieldParryingSKSE.ini LOCATED IN THE Dual Wield Parrying SKSE MOD)

G - Opens wheeler menu. Add or remove items from the Magic/Inventory menu by hovering over the item/spell and holding T then pressing left click in the slot you want. While in this same menu, right click will remove items and M/N will create new slots and wheeler pages.

Arrow Keys - Switch stances

Controller Hotkeys: https://www.nexusmods.com/skyrimspecialedition/mods/111887

### Gameplay Tips / Unlocking Cool Mechanics

Your starting dodge will be pretty bad. You can unlock a better version in the Evasion perk tree.

You can unlock starting Dynamic Dodge Shots with bows also in the Evasion Tree.

You can unlock use of a secondary dagger (pulling out a dagger when using your bow) in the One Handed perk tree.

You unlock SkyClimb at lvl 20 sneak. At lvl 50 sneak, light/unarmored users can get a faster more flashy vault animation.

Quick Light requires "Lantern With Fuel". To craft lantern fuel, use a cooking pot with dwemer oil or troll fat. Once you have this, click on it while having an empty lantern in your inventory.

### Known Bugs/Crashes

If you are using an AMD GPU, you need to disable DLAA and enable TAA in the SkyrimPrefs.ini located in the profile folder. Otherwise, you WILL crash.

"Crashing" on loading isn't actual crashing. It's the save loader mod exiting the game completely and reloading. It does this to ensure games are safe for long playthroughs.You can disable this in Optional - Gameplay but I recommend leaving it on.

Wheeler can cause crashes when assigning self-made potions/poisons/etc and using your last one. If this happens, press home to open dmenu and navigate to wheeler and "reset all wheels".
 
## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- Althro & Ylikollikas for answering all my questions.
- Bingus, Curly & Aljo for creating Ascensio - upon which LoreRim was built.
- ShadowSorcery for creating LoreRim's awesome logo.
- DiscloApproved for revamping LoreRim's NPCs.
- Abandoned by Arkay & Camboi for inspiring me to create a Requiem-based modlist.
- Halgari and everyone on the WJ Team - Wabbajack is awesome and so are you.
