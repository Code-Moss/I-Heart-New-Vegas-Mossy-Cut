[<< Back to Readme](README.md)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# NEW VEGAS SETUP

## Requirements

- An english copy of the game from [**GOG**](https://www.gog.com/game/fallout_new_vegas_ultimate_edition), or Steam.
  - Installation instructions are found on the next section. 
- A [**Nexus**](https://users.nexusmods.com/register) account. This guide assumes you are using a Free account, so no need to pay for Premium.
- A file archiver. I recommend [**7-Zip**](https://www.7-zip.org/).
- A text editor. I recommend [**Notepad++**](https://notepad-plus-plus.org/downloads/v7.9.5/).
- [**DirectX Runtime Libraries**](https://www.microsoft.com/en-us/download/details.aspx?id=8109).
- [**Microsoft VC++ 2013**](https://www.microsoft.com/en-us/download/details.aspx?id=40784) (x86 version) and [**Microsoft VC++ 2015-2019**](https://docs.microsoft.com/en-GB/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64 versions).

## Installation

You should install Fallout: New Vegas outside all default Windows folders (Program Files, Program Files (x86), Desktop, and Documents for example). Windows User Account Control monitors these folders, which can cause problems later on.

Your **Root** folder is where Fallout: New Vegas will be installed, and where the game's executable (**FalloutNV.exe**), launcher (**FalloutNVLauncher.exe**), and **Data** folder will be found.

For the purpose of this guide, this will be our **Root** folder:
```
C:\Games\Fallout New Vegas
```
Additionaly, you will need a folder where to install our mod manager and keep your mods. The following path will be used for this guide:
```
C:\Mods
```

> ⚠️ Make sure you *don't* create your Fallout New Vegas Mods folder *inside* your Fallout New Vegas folder, or else you will run into issues when you try to launch the game through Mod Organizer 2, most importantly, your mods not being registered.

Once you've finished installation of the game, go to the game's **Data** folder. If there is a plugin called **FalloutNV_lang.esp**, delete it.

## Generating fresh .INI files

- Run **FalloutNVLauncher.exe** from the game's Root folder.
- Click **OK** to both pop-ups that say **Detecting Video Hardware**. If there aren't any pop-ups, navigate to **Documents\My Games\FalloutNV** and delete all the files ending in .INI, then retry.
- Click **Options**, then select the **Ultra** preset option. Set antialiasing to **8 Samples**. If you want to improve performance without drastically changing the game's visuals, disable shadows under the **Options**, **Shadows** tab. These are hardly noticeable but can have a considerable performance impact.
- Set **Resolution** to your preference.
- Click **OK**, then **Exit**.

# UTILITIES

[**FNV BSA Decompressor**](https://www.nexusmods.com/newvegas/mods/65854?)  
Decompresses the Fallout New Vegas BSAs and repacks them without zlib compression for performance. Also transcodes the .ogg sounds effects to .wav so they work. It also extracts any mp3 files to loose files because they will not play when in a BSA.
- Manually download the **FNV BSA Decompressor** main file.
- Extract the contents of the archive, and run **FNV BSA Decompressor.exe**.
- Select your game's **Root** folder, and click **Decompress**.
- **Exit** the program once the process is done.

> ℹ️ This utility will add the following lines to your **Fallout.ini** file. If you ever encountering missing meshes in-game (in the form of red exclamation marks), make sure these lines are still present in your .ini.

```
[Archive]
SArchiveList=Fallout - Invalidation.bsa, Fallout - Textures.bsa, Fallout - Textures2.bsa, Fallout - Meshes.bsa, Fallout - Meshes2.bsa, Fallout - Voices1.bsa, Fallout - Sound.bsa, Fallout - Misc.bsa
```

[**xNVSE**](https://github.com/xNVSE/NVSE/releases)  
New Vegas Script Extender (xNVSE) expands the engine and scripting capabilities of Fallout New Vegas. This framework is required by many modern mods.
- Click the **nvse_6_2_9.7z** under **Assets** to download it.
- Extract the contents of the archive to the game's **Root** folder. Allow it to merge and overwrite if asked.

[**FNV 4GB Patcher**](https://www.nexusmods.com/newvegas/mods/62552?)  
Makes Fallout New Vegas 4GB Aware. Automatically loads NVSE if present.
- Manually download the **FNV 4GB Patch** main file.
- Extract the contents of the archive, and place **FalloutNVpatch.exe** in your game's **Root** folder.
- Run the patch. Close the command prompt once the process is done.

[**New Vegas Heap Replacer**](https://www.nexusmods.com/newvegas/mods/69779)  
Replaces the in-game heap with a faster, more optimized version. It should decrease load times, remove some stutter and slightly improve frame rate. 
- Manually download the **NVHR** main file.
- Extract the contents of the archive and run **cpu_info.exe**. It will determine which file you need to install.
- Place the **.dll** file from the appropiate folder (indicated by **cpu_info.exe**) in your game's **Root** folder.

# MOD ORGANIZER 2

[**Mod Organizer 2**](https://www.nexusmods.com/skyrimspecialedition/mods/6194)  
**Mod Organizer 2** is an excellent mod manager, offering lots of quality of life conveniences that make modding an easy and quick process.
- Manually download the **Mod Organizer 2** main file.
- Run the **Mod Organizer 2.exe**.
- When prompted to choose an install location, choose your Fallout: New Vegas **Mods** folder (**C:\Mods\MO2**).
- When installation has finished, uncheck the **Launch Mod Organizer** option and click **Finish**.

## Configuration

### Initial setup

- Run **ModOrganizer.exe**, found in **C:\Mods\MO2**.
- The **Instance manager** window will appear. Click on the **Create a new instance** bottom to the upper left. Choose **Create a portable instance**.
- You will be asked to select a game to manage. If **New Vegas** is available using the appropriate file path, select it. Otherwise, click **Browse...** and choose your game's **Root** folder.
- You will be asked to select a folder where data will be stored. The default MO2 folder is fine.
- Click **Next** and then **Finish**. Mod Organizer 2 will now launch.

> ℹ️ If you get a pop-up called **INI file is read-only**, schoose **Remember my choice** from the drop-down at the bottom, then click **Clear the read-only flag**.

> ℹ️ If you get a pop-up called **Register?**, choose **Yes**. This will allow Mod Organizer 2 to handle Nexus links.

> ℹ️ If you get a pop-up called **Show tutorial?**, choose **No**.

### Adjusting mod and load order

Reorganize the plugins to the right to read as follows using drag and drop, and enable the plugins.
```
FalloutNV.esm
DeadMoney.esm
HonestHearts.esm
OldWorldBlues.esm
LonesomeRoad.esm
GunRunnersArsenal.esm
ClassicPack.esm
MercenaryPack.esm
TribalPack.esm
CaravanPack.esm
```

> ℹ️ Your installed mods are listed on the pane to the left. This is the order in which Fallout: New Vegas loads their assets, with mods closer to the bottom overwriting the assets of mods closer to the top (if conflicting assets are present). We will refer to it as our **mod order**.

> ℹ️ Your plugins are listed on the pane to the right. This is the order in which Fallout: New Vegas loads their plugins, with plugins closer to the bottom overwriting the records of plugins closer to the top (if conflicting records are present). We will refer to it as our **load order**.

> ℹ️ You can hide unnecessary information in Mod Organizer 2 by right clicking on the headers above the installed mods, and unchecking the tabs you don't want to see. I suggest unchecking everything but the **Conflicts**, **Flags**, and **Priority** boxes. You can also click on the **X** to the bottom right of the **load order** panel, hiding unnecessary background information seen on the pane below.

### Adjusting falloutcustom.ini

- Click the **Tools** ![Tools](assets/icon-mo2tools.png) button, and click **INI Editor**. Select the **the falloutcustom.ini** tab.
- Paste in the following lines.

```
[General]
bUseThreadedAI=1
iNumHWThreads=2
bPreemptivelyUnloadCells=1

[BackgroundLoad]
bSelectivePurgeUnusedOnFastTravel=1

[Display]
bFull Screen=1
iTexMipMapSkip=0

[Controls]
fForegroundMouseAccelBase=0
fForegroundMouseAccelTop=0
fForegroundMouseBase=0
fForegroundMouseMult=0

[Audio]
iAudioCacheSize=8192
iMaxSizeForCachedSound=1024
```

- Click **Save** and close the window.

### Setting up Profiles

Mod Organizer 2 has a feature called **Profiles**, which lets you quickly change from one mod setup to another.

- Click the **Configure profiles** ![Profiles](assets/icon-mo2profiles.png) button.
- Check the following options:
  - [X] Use profile-specific Game INI files.
  - [X] Use profile-specific Save Games.
  - [X] Automatic Archive Invalidation.
- With the **Default** profile selected, click **Copy**. Type in **MAXIMUM New Vegas** and click **OK**.
- Click on the newly created profile, and click **Select**. The window will close, and the new profile should have been automatically selected.

> ℹ️ This is the profile we will be modding. You can always revert to the **Default** profile to quickly deactivate all installed mods.

# Hiding NVSE and FalloutNVLauncher in Mod Organizer 2

Earlier we installed [**FNV 4GB Patcher**](https://www.nexusmods.com/newvegas/mods/62552?), which makes Fallout: New Vegas 4GB Aware, and automatically loads NVSE if present.

From now on, you should avoid running the game through **nvse_loader.exe**. You should also avoid accidentally running **FalloutNVLauncher.exe**. We can hide both of these from Mod Organizer 2's list of executables.
- Click the **Modify Executables** ![Executables](assets/icon-mo2executables.png) button.
- Select **Fallout Launcher**, and tick **Hide in user interface**.
- Select **NVSE**, and tick **Hide in user interface**.
- Click **Apply**, and then **OK**.

# TOOLS

## FNVEdit

Because mods can conflict with one another, or have bugs/unintended changes themselves, we will be installing **FNVEdit** to help us troubleshoot and get rid of these issues.

[**FNVEdit**](https://www.nexusmods.com/newvegas/mods/34703)  
An advanced graphical module viewer/editor and conflict detector.
- Manually download the **FNVEdit 4.0.4** main file.
- Extract the contents of the archive to **Mods\FNVEdit**.

## FNVLODGen

**FNVLODGen** lets you generate LOD for our installed mods. LOD stands for level of detail. Fallout: New Vegas has very poor distant statics, and this tool will not only let us improve it, but also increase the amount of rendered statics, including those modified or added by mods.

[**FNVLODGen**](https://www.nexusmods.com/newvegas/mods/58562)  
Allows generation of LOD for worldspaces by scanning all mods in the load order that add visible from distant objects.
- Manually download the **FNVLODGen** main file.
- Extract the contents of the archive to **Mods\FNVLODGen**.

## Registering tools in Mod Organizer 2

For our tools to work in Mod Organizer 2, we need to register and configure them.

Follow these steps for **FNVEdit**:

- Click the **Modify Executables** ![Executables](assets/icon-mo2executables.png) button.
- Click the **Add an executable** ![AddExe](assets/icon-mo2addfile.png) button and choose **Add from file...**.
- Navigate to FNVEdit's folder (**C:\Mods\FNVEdit**) and double click **FNVEdit.exe**.
- In the **Start In** field, choose your **Root** folder (**C:\Games\Fallout New Vegas**).
- In the **Arguments** field, paste **-IKnowWhatImDoing**.
- Click **Apply** and then **OK**.

Follow these steps for **FNVEditQuickAutoClean**:

- Click the **Modify Executables** ![Executables](assets/icon-mo2executables.png) button.
- Click the **Add an executable** ![AddExe](assets/icon-mo2addfile.png) button and choose **Add from file...**.
- Navigate to FNVEdit's folder (**C:\Mods\FNVEdit**) and double click **FNVEditQuickAutoClean.exe**.
- In the **Start In** field, choose your **Root** folder (**C:\Games\Fallout New Vegas**).
- Click **Apply** and then **OK**.

Follow these steps for **FNVLODGen**:

- Click the **Modify Executables** ![Executables](assets/icon-mo2executables.png) button.
- Click the **Add an executable** ![AddExe](assets/icon-mo2addfile.png) button and choose **Add from file...**.
- Navigate to FNVLODGen's folder (**C:\Mods\FNVLODGen**) and double click its .exe file.
- In the **Start In** field, choose your **Root** folder (**C:\Games\Fallout New Vegas**).
- In the **Arguments** field, paste **-o:"C:\Mods\FNVLODGen Output\"**.
- Click **Apply** and then **OK**.

> ℹ️ This argument will make the files generated through FNVLODGen appear in a folder called **FNVLODGen Output** on your **Fallout New Vegas Mods** folder.

# GENERAL TIPS

## Mod Organizer 2 tips

### Mod manager download installation

Mods downloaded from Nexus will be instantly added to Mod Organizer 2 when using the **Mod manager download** option. However, you still need to install these mods for them to work in-game.

- In MO2, click on the **Downloads** tab. You can check the download progress for your file there.
- Right-click the downloaded file, and click **Install**.
- MO2 will prompt you to give the mod a name. I suggest giving it a descriptive name (e.g. **Patch for Purists 4.0.2**).
- Click **OK**.
- The mod will appear in the left pane. To finish installation, check the box next to it.

There will be times when you will need to install multiple files from the same mod page. Mod Organizer 2 allows the user to either merge, replace, or rename the file being installed.

![ModExists](assets/setup-exists.png)

What these options do is simple:

- **Merge** merges the contents of the file being installed with those of the file of the same name already installed. The new files will take priority over the old files, overwriting as necessary. This option is generally recommended when installing an update file that is separate from the main file, or optional files in the case you don't want to clutter your mod order.
- **Replace** will delete the installed mod, and install the new file. This option is generally recommended when installing a new version of the main file.
- **Rename** will install the new file under a different name, as a separate mod. This option is generally recommended when installing multiple files that are unrelated to each other (as is the case of compilation pages that list many mini-mods).

> ℹ️ By default, this guide will always ask users to download the main file from a Nexus page. If different or more detailed instructions are required, they will be provided. 

> ℹ️ When necessary, the guide will ask you to merge, replace, or rename files in order to avoid issues.

### Manual download installation

Sometimes authors will block the **Mod manager download** option in Nexus, and you will have to download the mod manually. On occasion, you will download a mod from a different site altogether, be it GitHub, Google Drive, or the personal website of a number of authors.

- In MO2, click the **Install a new mod from archive** ![Archive](https://github.com/Sigourn/nerevarrising/blob/master/MO2/MO_Archive.png) button.
- Navigate to the folder where the downloaded file is stored and double click on it.

The rest of the steps work exactly as during mod manager download installation.

- MO2 will prompt you to give the mod a name. As before, I suggest giving it a descriptive name (e.g. **Correct UV Rocks 1.0**).
- Click **OK**.
- The mod will appear in the left pane. To finish installation, check the box next to it.

### BAIN and FOMOD installers

BAIN installers allow users to customize their install by spliting their mods into multiple options. BAIN installers generally provide a **Core** option which needs to be installed for the mod to work at all, but this option is not always provided, and neither is it always required.

Like BAIN installers, FOMOD installers allow users to customize their install by spliting their mods into multiple options.

> ℹ️ This guide will list the necessary options to install. Unless listed, the missing options should be skipped.

### Hiding files

Mod Organizer 2 lets you hide specific files from your installed mods, be it assets or plugins. A hidden plugin is treated as a deactivated plugin, with the bonus that it will no longer clutter your load order. Hiding assets is useful when you don't want to install specific assets, or when you don't want them to overwrite another mod's.

- Right click on your installed mod and click **Information...**.
- On the **Filetree** tab, right click on the plugins, folders, or files you want to hide, and click **Hide**.
- Mod Organizer 2 will hide the files, and these will no longer affect your game.

### Creating a separator

Separators allow you to neatly separate installed mods in Mod Organizer 2 for ease of viewing. These can be created and then moved around in the left pane to place them where you want them to be.

- Right click on the empty space on the left pane, below **Overwrite**, and click **Create Separator**.
- Name your separator and click **OK**.

> ℹ️ It's strongly encouraged to create separators in order to distinguish mods from separate categories. Separators can be collapsed to keep your mod list clean and tidy.

### The Overwrite folder

The **Overwrite** folder is the destiny folder for a handful of files, including **config** folders which contain the configuration files for a number of NVSE mods. There's always a chance files in the **Overwrite** folder will overwrite assets and/or plugins from your installed mods, but for the purpose of this guide, you don't need to worry about them.

## Modding tips

The following aren't strict rules, but tips to follow if you are new to modding Fallout: New Vegas.

- Always keep backup saves, particularly so when uninstalling or installing mods.
- Read mod descriptions. They usually list requirements, compatibility with other mods, and known issues. User comments can also list issues and possible fixes, but take these with a grain of salt. Many users erroneously claim a mod isn't working, because of end user mistakes.
- Don't uninstall or install mods mid-playthrough, unless you know for sure you can do it safely. Mod descriptions and user comments can help you out here.
- Learn how file structure works. Incorrect file structure means mods will not work as intended.

# MOVING ON TO THE NEXT SECTION

[To MAXIMUM New Vegas >>](MAIN.md)  
[<< Back to Readme](README.md)
