[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# I HEART NEW VEGAS WABBAJACK SETUP

![Banner](https://raw.githubusercontent.com/Sigourn/iheartnewvegas/main/8064e94210b0914d6edbf0790d145e40d0c1890da78130c3d3c28f18bdae483e_bg_crop_1920x655.jpg)

## Requirements

- An english copy of the game from [**GOG**](https://www.gog.com/game/fallout_new_vegas_ultimate_edition).
  - Installation instructions are found on the next section. 
- A [**Nexus**](https://users.nexusmods.com/register) account. This guide assumes you are using a Free account, so no need to pay for Premium.
- A file archiver. I recommend [**7-Zip**](https://www.7-zip.org/).
- A text editor. I recommend [**Notepad++**](https://notepad-plus-plus.org/downloads/v7.9.5/).
- [**DirectX Runtime Libraries**](https://www.microsoft.com/en-us/download/details.aspx?id=8109).
- [**Microsoft VC++ 2013**](https://www.microsoft.com/en-us/download/details.aspx?id=40784) (x86 version) and [**Microsoft VC++ 2015-2019**](https://docs.microsoft.com/en-GB/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64 versions).

## Installation

You should install Fallout: New Vegas outside all default Windows folders (Program Files, Program Files (x86), Desktop, and Documents for example). Windows User Account Control monitors these folders, which can cause problems later on.

Your **Root** folder is where Fallout: New Vegas will be installed, and where the game's executable (**FalloutNV.exe**), launcher (**FalloutNVLauncher.exe**), and **Data** folder will be found.

By default, GOG will install Fallout: New Vegas to the next directory:
```
C:\Games
```
This will create a folder in the following path, which we will refer to as our **Root** folder.
```
C:\Games\Fallout New Vegas
```
### Cleaning up your GOG installation

Delete the following from your **Fallout New Vegas\Data** folder, if present:

```
FalloutNV_lang.esp
```

## Generating fresh .INI files

- Run **FalloutNVLauncher.exe** from the game's Root folder.
- Click **OK** to both pop-ups that say **Detecting Video Hardware**. If there aren't any pop-ups, navigate to **Documents\My Games\FalloutNV** and delete all the files ending in .INI, then retry.
- Click **Options**, then select the **Ultra** preset option. Set antialiasing to **8 Samples**. If you want to improve performance without drastically changing the game's visuals, disable shadows under the **Options**, **Shadows** tab. These are hardly noticeable but can have a considerable performance impact.
- Set **Resolution** to your preference.
- Click **OK**, then **Exit**.

# WABBAJACK

## Preamble

**Wabbajack** is an installation tool that can reproduce an entire modding setup on another machine without bundling any assets or re-distributing any mods. It can reproduce an entire modding setup on another machine without bundling any assets or re-distributing any mods.

This tool is invaluable for setting up I Heart New Vegas, drastically reducing the amount of time and effort required to get it working, minimizing user error, and ensuring things work smoothly.

## Installation

[**I Heart New Vegas Wabbajack**](https://drive.google.com/drive/folders/1GzS2b1TtYWgCZ57vuk8D9520kJ2dsTEH?usp=sharing)  
The official Wabbajack files for I Heart New Vegas.
- Download **I Heart New Vegas.wabbajack** and place it in your **C:\Games** folder.

[**Wabbajack**](https://www.wabbajack.org/#/)  
Automated installer for mod lists. Used to install I Heart New Vegas.
- Click the **Download** button on the main page to download the **Wabbajack.exe** installer.
- Launch **Wabbajack.exe**. This will download the tool and place it on a folder named after the current version number (e.g. **2.5.3.9**).
- **Wabbajack.exe**, found in the aforementioned folder, will be launched.
- Click the **Install From Disk** button.
- Under the **Target Modlist** path, paste the following path:
```
C:\Games\I Heart New Vegas.wabbajack
```
- Under the **Installation Location** path, paste the following path:

```
C:\Games\I Heart New Vegas
```
- With our modlist configured, click the play button to the right.

> ⚠️ If at any point the installation process fails because of Wabbajack being unable to download **FNVLODGen Output Extended**, close Wabbajack. Manually download the file from [**Google Drive**](https://drive.google.com/file/d/1fT7k67vv-K6QLhiJ9UrIMheJXuBewwNT/view?usp=sharing) and place the file in your **I Heart New Vegas\downloads** folder, overwriting when prompted. Launch **Wabbajack.exe**, and click the **Install From Disk** button. You'll be able to resume installation by clicking the play button to the right.

> ℹ️ The installation process, which includes download, extraction, and installation of mods and required tool, can take anywhere from 20 minutes to an hour. Once the process is finished, as indicated by the log, you can close **Wabbajack**. It is encouraged that you take this time to check out the mod slideshow, as it will give you an idea of what mods are included in the guide.

> ℹ️ You can safely delete the installer we downloaded in the first step. It is of no use to us anymore.

# UTILITIES AND TOOLS

## Preamble

The [**FNV BSA Decompressor**](https://www.nexusmods.com/newvegas/mods/65854?) decompresses the Fallout New Vegas BSAs and repacks them without zlib compression for performance. It also transcodes the .ogg sounds effects to .wav so they work, and extracts any mp3 files to loose files because they will not play when in a BSA.

The [**FNV 4GB Patcher**](https://www.nexusmods.com/newvegas/mods/62552?) makes Fallout New Vegas 4GB Aware. It also automatically loads NVSE if present.

The [**New Vegas Heap Replacer**](https://www.nexusmods.com/newvegas/mods/69779) will replace the in-game heap with a faster, more optimized version. It should decrease load times, remove some stutter and slightly improve frame rate.

The [**New Vegas Script Extender (xNVSE)**](https://github.com/xNVSE/NVSE/releases) expands the engine and scripting capabilities of Fallout New Vegas. This framework is required by many modern mods.

[**FNVEdit**](https://www.nexusmods.com/newvegas/mods/34703) is an advanced graphical module viewer/editor and conflict detector.

[**FNVLODGen**](https://www.nexusmods.com/newvegas/mods/58562) lets you generate LOD for our installed mods. LOD stands for level of detail. Fallout: New Vegas has very poor distant statics, and this tool will not only let us improve it, but also increase the amount of rendered statics, including those modified or added by mods.

## Installation

All these aforementioned tools and utilities have been downloaded and their files placed inside the **I Heart New Vegas\Game Folder Files** folder.

![GameFolderFiles](https://raw.githubusercontent.com/Sigourn/iheartnewvegas/main/gameFolderFiles.png)

- Copy the contents of **I Heart New Vegas\Game Folder Files** and paste them inside the **Fallout New Vegas** folder.
- Allow merge and overwrite when prompted.

## FNV BSA Decompressor setup

- Execute **FNV BSA Decompressor.exe**, found in your **Fallout New Vegas** folder.
- Select **C:\Games\Fallout New Vegas** as the path to your New Vegas installation, and click **Decompress**.
- Wait for the **Decompression has completed!** message, then click **EXIT**.

> ℹ️ This utility will add the following lines to your **Fallout.ini** file. If you ever encountering missing meshes in-game (in the form of red exclamation marks), make sure these lines are still present in your .ini.
```
[Archive]
SArchiveList=Fallout - Invalidation.bsa, Fallout - Textures.bsa, Fallout - Textures2.bsa, Fallout - Meshes.bsa, Fallout - Meshes2.bsa, Fallout - Voices1.bsa, Fallout - Sound.bsa, Fallout - Misc.bsa
```
## FNV 4GB Patcher setup

- Execute **FalloutNVpatch.exe**, found in your **Fallout New Vegas** folder.
- Run the patch. Close the command prompt once the process is done.

## New Vegas Heap Replacer setup

- Execute **cpu_info.exe**, found in your **Fallout New Vegas\NVHR** folder.
- Place the d3dx9_38.dll file from the corresponding folder (pointed out by the executable) inside your **Fallout New Vegas** folder.

# IN-GAME CONFIGURATION

It's time to finally run Fallout: New Vegas.

- In Mod Organizer 2, click on the executables dropdown menu to the left of the **Run** button, and select **New Vegas**. 
- Click **Run** to run the executable.

> ℹ️ Always remember to run Fallout: New Vegas through Mod Organizer 2 to detect the **Virtual Files** folder, and thus load the installed mods.

### Settings config

> ℹ️ The following settings need to be configured after you've already started a new save, using the in-game **Settings** option.

**Gameplay**:
- Set **Killcam Mode** to None.
- Set **Difficulty** to Hard.

**Controls -> Action Mapping**:
- Set **VATS** to Esc in order to disable the keybinding.
- Set **Ammo Swap** to Esc in order to disable the keybinding.

### MCM config

> ℹ️ The following settings need to be configured after you've already started a new save, using the in-game **Mod Configuration** option.

**Quick Grenade Hotkey**:
- Set **Grenade Hotkey** to **G**.
- Set **Grenade Swap Hotkey** to **C**.

**RAD**:
- Set **Hardcore** to **ON**.
- Set **JSawyer Increments** to **ON**.

> ℹ️ Sleep deprivation, hunger, and thirst will affect max AP; makes the former setting follow JSawyer's stat penalties progression.

# MOD KEYBINDINGS

This is a handy reference table which will hopefully help you have a better idea of what new hotkeys are available to you.

Key | Function | Added by
------------ | ------------- | -------------
F6 | Create full save | lStewieAl's Tweaks
F10 | Reload current loaded save | lStewieAl's Tweaks
Left ALT | Skip player deathcam when dying | lStewieAl's Tweaks
R (double tap) | Switch ammunition | lStewieAl's Tweaks
I | Toggle HUD | lStewieAl's Tweaks
J | Open Pip-Boy quests tab | lStewieAl's Tweaks
Hold Tab | Toggle scope night vision when aiming down the scope | lStewieAl's Tweaks
M | Open Pip-Boy world map tab | lStewieAl's Tweaks
Ctrl-F | Apply filter for searching in Pip-Boy | lStewieAl's Tweaks
Shift+E | Pick locked door even if you have the key | lStewieAl's Tweaks
Shift+E | Pick up and equip | lStewieAl's Tweaks
Scroll wheel | Adjust binocular zoom | lStewieAl's Tweaks
G | Equip/unequip grenade/mine | Quick Grenade Hotkey
C + Scroll wheel | Scroll through grenades/mines | Quick Grenade Hotkey
H | Open weapon wheel | Just Assorted Mods
V | Toggle bullet time | Just Assorted Mods
Shift+Movement | Sprint | Just Assorted Mods
X | Melee bash | B42 Melee Bash

# MOD ORGANIZER 2 PROFILES

I Heart New Vegas is offered in two versions:
- The standard **I Heart New Vegas** profile.
- The extended **I Heart New Vegas Addendum** profile.

The second profile expands on I Heart New Vegas' base install. It adds a selection of minor mods that I would have loved to include in **Misc Immersion Merge**. It also adds modern, high quality body replacers.

Additionally, both profiles featured **Altitude**-based profiles. These replace **Desert Natural Weathers** with a more purist-friendly weather overhaul.

Which one you choose to use, standard or addendum, is up to you. To select profiles, click the **Profile** dropdown menu as seen in the screenshot, and click the profile you want to use. Make sure not to switch profiles on an ongoing save, in particular if going from **I Heart New Vegas Addendum** to **I Heart New Vegas**.

![Profiles](https://raw.githubusercontent.com/Sigourn/iheartnewvegas/main/profileSelection.png)

# MODS YOU SHOULD KNOW ABOUT

As an automated Wabbajack setup, it is important to know about a handful of mods which will drastically affect your Fallout: New Vegas experience. This is to let you know in advance which tweaks and features are intended, evacuate some doubts that may arise during gameplay, as well as help you decide whether they are something you want to play with. Note that this is not a comprehensive list of all mods included in the guide. For that, [**please refer to this link**](https://github.com/Sigourn/iheartnewvegas/blob/main/main.md).

[**The Mod Configuration Menu**](https://www.nexusmods.com/newvegas/mods/42507)  
Allows any number of mods to be configured from a single menu, accessible through the Pause menu.

[**Simple DLC Delay**](https://www.nexusmods.com/newvegas/mods/62779)  
Delays DLC pop-ups until you meet certain level requirements or discover the entrances to the DLC areas.

[**Follower Formula Redone**](https://www.nexusmods.com/newvegas/mods/71490)  
Limits the amount of followers the player can have depending on their Charisma stat divided by 2, rounded down. The player will need at least 2 Charisma to have one follower, and they can have 5 followers at most. 

[**JAM - Just Assorted Mods**](https://www.nexusmods.com/newvegas/mods/66666)  
A collection of toggleable mods, including dynamic crosshair, hit marker, hit indicator, visual objectives, hold breath, vanilla sprint, bullet time, weapon wheel, and loot menu.

[**RAD - Radiation (is) Actually Dangerous - Overhaul**](https://www.nexusmods.com/newvegas/mods/71541)  
Makes radiation work like in Fallout 4, by damaging your max health.

[**JSawyer Ultimate Edition**](https://www.nexusmods.com/newvegas/mods/61592)  
Completely reconstructed version of Josh Sawyer's mod, made from the ground up. Tweaks inconsistencies, expands compatibility, re-adds some elements of cut content, and covers additional balance issues which were missed.

[**Famine - A Loot Rarity Mod**](https://www.nexusmods.com/newvegas/mods/74985)  
Simple and comprehensive loot scarcity mod using event-based scripting.

[**New Vegas Economy Improved**](https://www.nexusmods.com/newvegas/mods/71604)  
Fully-scripted, lightweight, and compatible item value overhaul, taking into consideration important aspects of the vanilla economy balance. Applies a moderate reduction in value to high-value items, and a small reduction to low-value items.

[**Better Character Creation**](https://www.nexusmods.com/newvegas/mods/70973)  
Improves the character creation by speeding up the process, adding specialized gear based on your tag skills, and making Wild Wasteland an opt-in feature rather than a trait.

The **Addendum** profile adds body replacers. By default, these body replacers will have underwear, as well as reduced nudity in the case of female body replacers. You can choose to disable these options by deactivating a number of mods in the profile. These mods are:

[**Improved Vanilla Male Body - Underwear**](https://www.nexusmods.com/newvegas/mods/70160)  
Patches **Improved Vanilla Male Body** to add underwear.

[**More Modest TYPE4 Body and Armor**](https://www.nexusmods.com/newvegas/mods/69642)  
Less skimpy outfits for many TYPE4 outfits.

[**More Modest TYPE4 Fixes**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/More%20Modest%20T4%20Fixes.7z)  
Fixes mismatching textures on a number of More Modest TYPE4 outfits.

[**TYPE4 Alternative Outfits**](https://www.nexusmods.com/newvegas/mods/66993)  
Less skimpy Wasteland Wanderer and Raider outfits.

# CHANGELOG

03-08-2022
- 1.1.3.
- Hopefully fixed Google Drive link to **FNVLODGen Output Extended**, now renamed to **I Heart New Vegas LOD**.
- Updated **Desert Natural Weathers**.
- Added **Desert Natural Weathers Custom INI**. Disables interior tint fix and increases sunlight during the day.

03-07-2022
- 1.1.2 Hotfix.
- Updated **Desert Natural Weathers - Zion Ambient Music**.

03-07-2022
- 1.1.1.
- Hid **NVSE** executable on MO2.
- Fixed Google Drive link to **FNVLODGen Output Extended**.
- Updated **yUI - User Ynterface**.
- Updated **ySI - Sorting Ycons**.
- Updated **Desert Natural Weathers**.

03-05-2022
- 1.1.0.
- Added alternative profiles which use **Altitude** instead of **Desert Natural Weathers**. This covers both the standard and addendum profiles.
- Added **Elegant Sunglare Retexture** to the Altitude profiles.
- Updated **Essential DLC Enhancements** (Gameplay).
- Updated **Desert Natural Weathers** (Visuals).
- Removed **HD Moon 2K** (Visuals) from the non-Altitude profiles. The latest update of **Desert Natural Weathers** finally fixes the white outline bug on the Moon, so it is no longer needed.

03-04-2022
- 1.0.5 Hotfix.
- Updated **lStewieAl's Tweaks and Engine Fixes** (Patches) for latest Nexus release.
- Updated **lStewieAl's Tweaks Custom INI** (Patches).

03-04-2022
- 1.0.4 Hotfix.
- Added missing **Restore Fake Interior Godrays** file for **Desert Natural Weathers** (Visuals).
- Updated **HD Moon 2K - NASA Satellite Images** (Visuals) for latest Nexus release.

03-04-2022
- 1.0.3 Hotfix.
- Updated **Desert Natural Weathers** (Visuals) for latest Nexus release.

03-04-2022
- 1.0.2 Hotfix.
- Updated **Just Assorted Mods Custom INI** (Gameplay).

03-03-2022
- 1.0.1 Hotfix.
- Updated **Desert Natural Weathers** (Visuals) for latest Nexus release.

03-03-2022
- 1.0.0
- Initial release.

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md)
