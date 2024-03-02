# LoreRim - A Modern Action RPG

![banner image]([https://raw.githubusercontent.com/Althro/Anvil/main/Resources/AnvilTestThumbnail.png](https://staticdelivery.nexusmods.com/mods/1704/images/112590/112590-1708904333-195281047.png))

Wabbajack Modlist Installer by biggie_boss.

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/Althro/Anvil/main/Resources/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><a href="https://loadorderlibrary.com/lists/lorerim">View modlist</a></td>
<td><a href="https://discord.gg/Tb5ETzBYjd"><img alt="Discord" src="https://cdn.logojoy.com/wp-content/uploads/20210422095037/discord-mascot.png" width="64px" ></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Preamble

**LoreRim** is designed as a forge for creating on. It can be used to build your own list, create mods, and also be played as is. It is fully documented with all changes and tweaks to mods being detailed in the `notes` part of Mod Organizer 2, and aims to be light in its footprint.

There are `Three` profiles in Anvil, each serving a distinct purpose.

`Anvil - Forge` is the most basic of profiles. It is designed as a mod development base with the Creation Kit and Plugin Development libraries being availiable. It can also serve as a "non-graphical" base for building a list off. It serves as the consolidated replacement of [Althro's Dev Tools](https://github.com/Althro/ADT).

`Anvil - Core` & `Anvil - Core CS` are the visual profiles, being for [Community Shaders](https://www.nexusmods.com/skyrimspecialedition/mods/86492) and [ENB](http://enbdev.com/news.html) respectively. Anvil's visual overhaul has an emphasis on "less is more" and improving what is already there. It serves as the replacement for [Althro's/Animonculory Visual Overhaul](https://github.com/Althro/Anvil).

## System Requirements

### Disclaimer

Owing to the need to clean master files and certain errors with Wabbajack, Anvil only supports **English Steam** versions of Skyrim SE. **GOG and other Languages are not supported**. The specific version used is 1.6.640 with the creation club content from 1.6.1170.

:warning: :exclamation: **ANVIL REQUIRES THE FULL PAID UPDATE TO SKYRIM. IT IS NOT/WILL NOT BE MADE COMPATIBLE WITH THE NON PAID UPDATE OR OLDER VERSIONS** :exclamation: :warning:

***

Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your windows version **must be 21H2 or newer** to run both Wabbajack and Anvil.

Anvil *should* work on Linux, however this is not supported by the author. An unofficial guide to running the list on Linux is being developed.

Running the list from Hard Disk Drives or external drives is **STRONGLY ADVISED AGAINST**. A lot of content is swapped at game run time and, as a result, fast storage and RAM are needed.

### Recommended System Requirements

Anvil requires a mid-tier modern system to run to its fullest potential. The recommended specs given below are based on utilizing the ENB in the list. For community shaders, you can subtract a little bit from them. Users have reported being able to run on hardware slightly lower than this, however your mileage may vary.

| Component    | Recommended | 
|:--------------:|:-------------:|
| CPU | 6 core/12 thread
| Ram | 16GB DDR4 Ram  + 20GB Pagefile 
| Storage | SSD
| GPU | 6GB VRAM 

Space required: Approx 121GB (Downloads included) + 30GB working room for Wabbajack.

:warning: **NOTE**: AMD RX 580 and older cards are **not supported**. :warning:

## Installation

Installing Anvil is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing Anvil, please complete the following steps.


1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Launch the game to the main menu and allow it to download the paid addon files.
8. Install the [Creation Kit on Steam](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/).
9. Run it once and select `Yes` when it asks about unpacking scripts.
10. Close the creation kit and continue with the installation steps.
11. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

:warning: **NOTE**: Anvil will **always** require the latest version of Wabbajack **UNLESS IT IS SPECIFICALLY STATED HERE**. :warning:

#### Downloading and Installing Anvil

Downloading and installing Anvil can take a while depending on your internet connection and computer. To install Anvil, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on Anvil and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Anvil. **Do not install it to your desktop or downloads folder.**
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

Anvil utilizes a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Skyrim installation within the installation location of the list. This enables greater compatibility with other mod-lists.

Anvil also utilizes Root Builder alongside Stock Game to enable easier management of hooks such as ENB, Reshade and Engine Fixes. Please see our guide to [Root Builder](https://github.com/The-Animonculory/Modding-Resources/blob/main/Root%20Builder%20for%20Skyrim%20AE.md) for more details.
***

### Post Processing

Anvil uses [Aequinoctium - Weathers and Seasons](https://www.nexusmods.com/skyrimspecialedition/mods/15884) with lighting governed by [Skyim is Luminous - Ominous Option](https://www.nexusmods.com/skyrimspecialedition/mods/110471). These are method patched and easy enough to remove should you wish to switch to something else.

The list comes with [Silent Horizons 2 ENB](https://www.nexusmods.com/skyrimspecialedition/mods/99398) as the main post processing option. The only changes made are to the screenshot format. Should you wish to change this, is is easy to adjust or remove the ENB.

[Amethyst - Weathers and Reshade preset for Community Shaders](https://www.nexusmods.com/skyrimspecialedition/mods/994502) is also included and fully set up and ready to use. This is easy to change and remove should you wish to. If you wish to use this, please enable the `Anvil - Core CS` profile.

**NOTE**: Screenshots save to `Overwrite\Game Root`.

**NOTE**: By default, the list is **capped at 82fps**. To change this, disable `Display Tweaks - Anvil Tweaks` and set your new cap in the `ini` file in `SSE Display Tweaks`. Make to disable the framerate lock in ENB if you are using the `Anvil - Core` profile.

## The Creation Kit on "Forge"

The Creation Kit version used in this list **WILL GENERATE PLUGINS WITH THE NEW HEADER VERSION**. Please bear this in mind when creating plugins.

CK platform fixes is used to enable the Creation Kit to work with the specialised game version used in this list. Please ensure that you do not change anything in the INI without first reading what it does.

:warning: **UNDER NO CIRCUMSTANCES CHANGE `bSupportFormat171` TO FALSE. THE CREATION KIT WILL FAIL TO LAUNCH OTHERWISE** :warning:

To launch the creation kit, set the profile to `Anvil - Forge` and then run `Creation Platform extended`. You can also press the icon for it to run it if you wish.

## Playing the List

### Ultrawide Setup

To enable 21x9 ultrawide support, activate the two mods tagged `21x9` under `UI Fixes [Forge & Core]`. **NOTE**: Resolutions outside of 21x9 and 16x9 are **NOT** supported.

### Real-time performance monitoring

Anvil includes a mod that enables you to see your FPS and VRAM usage in real-time. To enable this, activate the mod called `OSD Font for SSE Display Tweaks`. **NOTE**: This comes disabled by default.

***

### Starting up the list
Open the installation folder and double-click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.

### In-game MCM options

Anvil has no required MCM options to be selected; however, you can load the smoothcam preset if you wish to do so.

- SmoothCam
	- Load Preset

You are welcome to change any others to achieve your desired setup.

### Starting the Game

By default, Anvil uses [Optional Quick Start](https://www.nexusmods.com/skyrimspecialedition/mods/63953) to bypass the cart ride and start the game in the Helgen Cave. A message will pop-up asking you to chose whether to Skip the intro (Press `Yes`) and then, after character creation, Hadvar or Ralof. Choose your preferred companion and then the game will play out as if you made that choice before entering.
	
## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- Ferroxius for the logo, splash and ensuring focus.
- The Aetherius Modding Team.
- The beta testers on Aetherius Modding.
- Noggog for Mutagen.
- xSlim & Aosana for proofreading documentation.
- Umgak for help patching.
- Halgari and everyone on the WJ Team - Wabbajack is awesome and so are you.

## Contact

Whilst I am available primarily on [my server](https://discord.gg/xRrHRsb5e9), please check the [issues](https://github.com/Althro/Anvil/issues) tab on GitHub first if you have any issues. DO NOT DM ME ON DISCORD.
