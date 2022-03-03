[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# PREAMBLE

## Disclaimer

The guide presented here assumes you have already followed all instructions found in the [**Setup**](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup) page, and are familiar with Mod Organizer 2, which we will be using to install the mods in this document. Please abstain from using this guide until you've correctly set up Fallout: New Vegas and the recommended tools.

## Installing mods appropriately

When installing a mod, use the name provided for it in the guide's hyperlink. For example, the guide lists the following mod's name as **Yukichigai Unofficial Patch - YUP**.

![Example](https://raw.githubusercontent.com/Sigourn/iheartnewvegas/main/modExample.png)

Whenever you install a mod in Mod Organizer 2, the mod manager assigns it a default name, which is either the name of the Nexus page from where it is being downloaded from, the name of the file, or a complete filename. When manually installing a mod, Mod Organizer 2 will always resort to its filename.

All files installed from a same Nexus page should be merged into a single mod when using Mod Organizer 2. They should also be merged in the order they are listed in this guide, to avoid potential problems (such as update files being overwritten by older files from a same mod). The rule of thumb to use is that one hyperlink in the guide = one single mod on your MO2's left pane.

By default, this guide will always require you to download the main file. On the occasion more specific instructions are required (e.g. multiple main files are present and you need directions, or additional files need to be installed) they will be provided.

# I HEART NEW VEGAS

## xNVSE PLUGINS

[**New Vegas Heap Replacer**](https://www.nexusmods.com/newvegas/mods/69779)  
Replaces the in-game heap with a faster, more optimized version. It should decrease load times, remove some stutter and slightly improve frame rate. 
- Manually download the **NVHR** main file.
- Extract the contents of the archive and run **cpu_info.exe**. It will determine which file you need to install.
- Place the **.dll** file from the appropiate folder (indicated by **cpu_info.exe**) in your game's **Root** folder.

[**JIP LN NVSE Plugin**](https://www.nexusmods.com/newvegas/mods/58277)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**JIP LN NVSE Plugin Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JIP%20LN%20NVSE%20Plugin%20Custom%20INI.7z)  
Enables Fallout 3-style repair, localized damage (allowing headshots to be more powerful when the enemy has no helmet), and a chance for random NPCs to have weapon mods. Disables the voice modulation fix, which could cause noticeable audio popping, particularly in Elijah's dialogue.

[**JohnnyGuitar NVSE**](https://www.nexusmods.com/newvegas/mods/66927)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**ShowOff NVSE Plugin**](https://github.com/Demorome/Showoff-NVSE/releases)  
Adds new functions, engine bug fixes and tweaks.
- Click the **ShowOffNVSE.7z** under **Assets** to download it.
 
[**kNVSE Animation Plugin**](https://www.nexusmods.com/newvegas/mods/71336)  
Enables having custom animations for weapons and actors. Also fixes the engine-bound anim group limit problem.

[**yUI - User Ynterface**](https://www.nexusmods.com/newvegas/mods/74357)  
Aims to fix UI bugs and add new UI features. 

Files to install:
- **yUI** (Main files)
- **Matched Cursor - Fallout New Vegas** (Optional files)  

[**yUI - User Ynterface Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/yUI%20-%20User%20Ynterface%20Custom%20INI.7z)  
Matches cursor color to HUD color,  required for the Matched Cursor - Fallout New Vegas file we installed earlier.

[**NVAC - New Vegas Anti Crash**](https://www.nexusmods.com/newvegas/mods/53635)  
Implements structured exception handling and sanity checking to reduce frequency of game crashes.

[**OneTweak**](https://www.nexusmods.com/skyrim/mods/40706)  
Enables borderless window mode for safe alt-tabbing.
- Manually download the **OneTweak** main file.
- Extract the contents of the archive. Inside, rename the **SKSE** folder to **NVSE**, and copy this NVSE folder into your **Fallout New Vegas\Data** folder, merging both NVSE folders into one.
- Launch Mod Organizer 2.
- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Select the **FalloutCustom.ini** tab.
- Set **bFull Screen** to 0.

[**NVTF - New Vegas Tick Fix**](https://www.nexusmods.com/newvegas/mods/66537)  
Fixes the tick count bug (which creates noticable micro stutter), optimizes hash tables (helping performance and decreasing menu load times), and fixes the high FPS bug (fixing physics and lipsync at high framerates).
- Install as **NVTF - New Vegas Tick Fix**.

[**NVTF Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/NVTF%20Custom%20INI.7z)  
Custom configuration that enables a number of settings to achieve the best balance between performance and stability.

[**FNV Mod Limit Fix**](https://www.nexusmods.com/newvegas/mods/68714)  
Allows a maximum of 255 plugins to be loaded, as well as improving FPS, removing game stutter, and allowing for faster loading times (particularly when using a large number of mods).

[**Improved lighting Shaders**](https://www.nexusmods.com/newvegas/mods/69833)  
Almost completely fixes the exterior lighting bug, and allows up to four times the number of active lights.

[**Console Paste Support**](https://www.nexusmods.com/newvegas/mods/65906)  
Enables hotkeys for pasting and enhanced movement/deletion of console commands.

## PATCHES

### Bug fixes

[**Yukichigai Unofficial Patch - YUP**](https://www.nexusmods.com/newvegas/mods/51664)  
Collection of bug fixes for Fallout: New Vegas and its DLCs, combined into one ESM.

Files to install:
- **YUP - Base Game and All DLC** (Main files)

[**Landscape Disposition Fix**](https://www.nexusmods.com/newvegas/mods/73937/)  
Small mod fixing several hundred vanilla floating objects, underground or above ground.

[**Navmesh Fixes and Improvements**](https://www.nexusmods.com/newvegas/mods/62041)  
Fixes virtually every navmesh where the edge connections were missing or pointing at misplaced or invalid triangles, all while retaining the original triangle ordering at the cell edges whenever possible for maximum compatibility. Also makes improvements to the majority of the affected navmeshes, like adding gaps for obstacles such as rocks and trees.

Files to install:
- **Navmesh Fixes and Improvements - Base Game and ALL DLC** (Main files)

### NVSE bug fixes

[**Unofficial Patch NVSE Plus**](https://www.nexusmods.com/newvegas/mods/71239?)  
Collection of bug fixes for Fallout: New Vegas and its DLCs which require NVSE.

[**lStewieAl's Tweaks and Engine Fixes**](https://www.nexusmods.com/newvegas/mods/66347)  
Engine bugfixes, optional tweaks and new features with no performance impact. Fully customisable via in-game menu and INIs.

[**lStewieAl's Tweaks Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/lStewieAl's%20Tweaks%20Custom%20INI.7z)  
Custom configuration that enables many quality of life improvements, as well as gameplay and balance tweaks.

<details>
	<summary>Detailed list of tweaks</summary>

- Numbered dialogue topics.
- Hidden skill requirements for skill checks.
- Guns require enough ammo to fire a full round (clip size matters).
- Holding the attack button for grenades decreases their detonation timer.
- Throwables can be held and released, like grenades.
- Vendors obey their Buy/Sell flags, restricting which items they accept. Meant to be used alongside Misc Gameplay Merge (Gameplay section).
- Can't steal caps after paying for repairs.
- Binoculars can zoom in and out.
- Entering VATS costs AP.
- Opening Pip-Boy in combat costs AP.
- Living Anatomy perk shows Damage Resistance.
- Unconscious actors can be looted.
- Manual reloading.
- Slower backpedalling.
- Owned items can't be grabbed and moved around.
- VATS' range is tied to current weapon's range.
- Pickpocket formula takes into account item weight, target Perception, and detection value.
- Agility affects reload jams.
- Repairing items gives XP.
- Robotic companions heal with Scrap Metal instead of Stimpaks.
- Sneak attack critical hits can only be dealt with melee weapons.
- Broken armor is automatically unequipped.
- Weapon mods can be unequipped.
</details>

### Additional NVSE bug fixes

[**Ammo Burst Case Count Fix**](https://www.nexusmods.com/newvegas/mods/69175)  
Fixes the game only giving you one ammo case when your weapon uses more than one ammo count in a shot, for you and companions.

[**Ammo Script Fixes**](https://www.nexusmods.com/newvegas/mods/63997)  
Fixes several problems at the core level with how ammo scripts and effects work. Includes other gameplay tweaks.

[**Critical and Effects - Fixes and Tweaks**](https://www.nexusmods.com/newvegas/mods/69200)  
Fixes the damage dealing critical effects of most vanilla weapons so that they cannot cause you to miss "killcounts" and other proc effects such as crime responsibility. Includes other gameplay tweaks.

[**Melee VATS Animation Restoration**](https://www.nexusmods.com/newvegas/mods/73480)  
Brings VATS melee animations back from Fallout 3.

[**Mostly Unarmed Tweaks**](https://www.nexusmods.com/newvegas/mods/69283)  
Fixes the fatigue-dealing weapons to deal correct and damage-adjusted fatigue. Includes other gameplay tweaks.

[**Universal Pyromaniac Buff for Fire Effects**](https://www.nexusmods.com/newvegas/mods/71505)  
Makes the Pyromaniac perk affect all the lingering fire damage effects from weapons and ammo.

### Mesh fixes and optimization

[**New Vegas Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/74295)  
Optimizations and fixes for a large selection of meshes in the base game and DLC.

[**Weapon Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/65052?)  
Fixes mesh errors, UV errors, incorrect flags, missing extra data, form lists, projectiles, and other weapon related bugs and errors.

[**Weapon Mesh Improvement Mod ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/WMIM%20ESP%20Replacer%201.4.7z)  
Omits ITM records and removes unnecessary tweaks to Ammunition, Object Effect, Explosion, FormID List, and Recipe recorts.

[**Throwable Weapon Fixes**](https://www.nexusmods.com/newvegas/mods/62767)  
Visual and audio fixes for thrown projectiles.

[**Throwable Weapon Fixes - WMIM Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Throwable%20Weapon%20Fixes%20-%20WMIM%20Patch.7z)  
Compatibility patch for Weapon Mesh Improvement Mod. Includes the latter's fixes to projectiles.

[**Female White Glove Society Mask Fix**](https://www.nexusmods.com/newvegas/mods/66940)  
Fixes the White Glove Society Mask mesh for female characters.

[**Less Flickery City of New Vegas**](https://www.nexusmods.com/newvegas/mods/72061)  
Fixes the intense flickering in the city of New Vegas (such as when looking from Goodsprings Cemetery) due to extra white proxy meshes clipping into the object LOD meshes.

## USER INTERFACE

### Menus

[**UIO - User Interface Organizer**](https://www.nexusmods.com/newvegas/mods/57174)  
An NVSE-powered plugin designed to manage and maintain all UI/HUD extensions added to the game by various mods.

[**The Mod Configuration Menu**](https://www.nexusmods.com/newvegas/mods/42507)  
Allows any number of mods to be configured from a single menu, accessible through the Pause menu.

Files to install:
- **The Mod Configuration Menu** (Main files)
- **MCM BugFix 2** (Optional files)  

[**Vanilla UI Plus (New Vegas)**](https://www.moddb.com/mods/vanilla-ui-plus/downloads/vanilla-ui-plus-nv)  
Greatly improves the user interface without compromising the original style.
- Download the mod using the **DOWNLOAD NOW!** button.
- FOMOD options to install:
  - [X] Classic Pip-Boy Font
  - [X] Plugin
  - [X] WASD Compatible 

> ℹ️ The **Classic Pip-Boy Font** option includes the **Default Font Tweaks** option, and only enables said font exclusively in the Pip-Boy screen.

[**Vanilla UI Plus (New Vegas) Custom Settings**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Vanilla%20UI%20Plus%20(New%20Vegas)%20Custom%20Settings.7z)  
Increases the amount of visible dialogue topics, and displays numbers next to dialogue topics (intended to be used alongside my lStewieAl's Tweaks Custom INI).

[**JIP Improved Recipe Menu**](https://www.nexusmods.com/newvegas/mods/59638)  
Makes the crafting interface easier, more efficient and less tedious to use. 

[**ySI - Sorting Ycons**](https://www.nexusmods.com/newvegas/mods/74358?)  
Sorting mod, using features of yUI to make inventory management a better experience. Each item gets assigned one of the 140+ included custom icons, representing different categories of items.

[**FOV Slider**](https://www.nexusmods.com/newvegas/mods/55085)  
Adds an MCM menu that allows for adjusting the Fields of View for all of the game's camera views.

[**FOV Slider Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/FOV%20Slider%20Custom%20INI%201.0.3.7z)  
Custom configuration that increases field of view. Recommended to be used alongside **Pip-Boy 2000 Mk VI**, which we will install in the **Visuals** section.

[**Vanilla HUD Cleaned**](https://www.nexusmods.com/newvegas/mods/70001)  
Cleans up HUD textures (such as the compass ticks or other arrows) that have went unnoticed.
- FOMOD options to install:
  - All **Modules** and **Tweaks** options.
  - Skip the **DarnUI Specific** options.

[**Clean Companion Wheel**](https://www.nexusmods.com/newvegas/mods/70486)  
Cleans up textures surrounding the Companion Wheel.

Files to install:
- **Clean Companion Wheel 256x256 Edition** (Main files)

[**Consistent Pip-Boy Icons**](https://www.nexusmods.com/newvegas/mods/65046)  
Bug fixes and consistency tweaks for icons in terms of coloring and transparency.

Files to install:
- **1. Consistent Pip-boy Icons** (Main files)  
- **2. Consistent Addon Icons** (Main files)
  - FOMOD options to install:
    - [X] Interfaceshared0 Addon
- **3. Consistent Glow Icons** (Main files)
  - FOMOD options to install:
    - [X] Main File
- **6. Vanilla UI Plus Patch** (Optional files)

[**Satellite World Map**](https://www.nexusmods.com/newvegas/mods/58602)  
High-res satellite map for the Mojave Wasteland.

Files to install:
- **Satellite World Map** (Main files)

[**Satellite Maps DLC**](https://www.nexusmods.com/newvegas/mods/64292)  
High-res satellite maps for Dead Money, Honest Hearts, Old World Blues, and Lonesome Road.

## GAMEPLAY QOL

[**Faster Pip-Boy Animation**](https://www.nexusmods.com/newvegas/mods/67761)  
Increases the speed of the Pip-Boy animation.

Files to install:
- **Faster Pip-Boy Animation (2x)** (Main files)

[**Quick Grenade Hotkey**](https://www.nexusmods.com/newvegas/mods/64874)  
Adds a hotkey to automatically select the currently selected grenade/mine, as well as a hotkey to scroll through your available grenades/mines. Read the description for instructions on how these features work.

[**Quick Grenade Hotkey Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Quick%20Grenade%20Hotkey%20Tweaks.7z)  
Adjusts the positioning of the grenade/mine icon to not overlap with other UI elements, and removes the unnecessary "no grenade/mine" icon.

[**Simple DLC Delay**](https://www.nexusmods.com/newvegas/mods/62779)  
Delays DLC pop-ups until you meet certain level requirements or discover the entrances to the DLC areas.

## GAMEPLAY

[**Essential DLC Enhancements Merged**](https://www.nexusmods.com/newvegas/mods/73803)  
A collection of small essential gameplay improvements for the official DLCs that have been fully merged, updated, and cleaned.

[**Follower Formula Redone**](https://www.nexusmods.com/newvegas/mods/71490)  
Limits the amount of followers the player can have depending on their Charisma stat divided by 2, rounded down. The player will need at least 2 Charisma to have one follower, and they can have 5 followers at most. 

[**Follower Formula Redone YUP Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for Yukichigai Unofficial Patch.

[**Follower Tweaks**](https://www.nexusmods.com/newvegas/mods/62180)  
Removes annoying features from some followers. Changes the effects of the Enhanced Sensors, Spotter, and Search and Mark perks. ED-Es no longer 'whirs' whilst moving.

[**Helmet Armor Rebalance (JIP)**](https://www.nexusmods.com/newvegas/mods/72028)  
Scripted rebalance of all helmet armors in the game for users of JIP's bLocalizedDTDR feature. This raises their DT to the level of their associated or equivalent body armors in order to compensate for protective headwear being rendered practically useless with the setting enabled.

> ℹ️ This mod requires a specific JIP LN Plugin feature to be enabled, which we will enable in the **INI config** section.

[**Jamming Fix and Optional Tweaks**](https://www.nexusmods.com/newvegas/mods/66293)  
Fixes the on-fire jamming for automatic weapons and adds an option for how often weapons jam.

[**JAM - Just Assorted Mods**](https://www.nexusmods.com/newvegas/mods/66666)  
A collection of toggleable mods, including dynamic crosshair, hit marker, hit indicator, visual objectives, hold breath, vanilla sprint, bullet time, weapon wheel, and loot menu.

> ℹ️ For detailed instructions on how the **Weapon Wheel** feature works, [**see here**](https://www.nexusmods.com/newvegas/mods/67460).

[**Just Assorted Mods Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Just%20Mods%20Assorted%20Custom%20INI.7z)  
Custom configuration that disables Visual Objectives and Hold Breath. Sets 1st Person Mode crosshair to dynamic and 1st Sighting Mode to none. Sets Bullet Time to use VATS sounds, and use the V hotkey.

[**JAM or Just Sprint Animation Replacers**](https://www.nexusmods.com/newvegas/mods/74839)  
Improves animation transitions when going from idle to sprint, plus allows the player to reload their weapons when sprinting.

[**B42 Melee Bash**](https://www.nexusmods.com/newvegas/mods/68055)  
Adds melee attacks for non-melee weapons, similar to melee hits and buttstrokes in modern FPS games.

[**Melee Cleave (a.k.a. Sweep)**](https://www.nexusmods.com/newvegas/mods/66187)  
Makes melee attacks hit multiple enemies.

[**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)  
Compilation of small gameplay mods, fully fixed, optimized, and updated, ranging from quality of life improvements, gameplay and balance tweaks, and visual tweaks.

[**Misc Immersion Merge**](https://www.nexusmods.com/newvegas/mods/75283)  
Compilation of minor visual, gameplay, and immersion mods.

Files to install:
- **Misc Immersion Merge** (Main files)
- **Follower Formula Redone Patch** (Optional files)
- **JSawyer Ultimate Patch** (Optional files)
- **JSawyer Ultimate - Mojave Arsenal Patch (GRA Merged) Patch** (Optional files)

[**Miscellaneous Tweaks Collection**](https://www.nexusmods.com/newvegas/mods/71847)    
Collection of gameplay and balance tweaks.

[**Miscellaneous Tweaks Collection Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Miscellaneous%20Tweaks%20Collection%20Tweaks.7z)  
Nerfs Feral Ghoul Reavers, ties Honest Hearts recipes to reaching Zion (mirroring how other DLC recipes work), and adds a new Mojave Express dropbox outside Camp McCarran.

[**NPCs Sprint In Combat**](https://www.nexusmods.com/newvegas/mods/68179)  
NPCs will now sprint in melee combat instead of casually jogging. Uses custom sprint animations.

[**NPCs Use Aid Items**](https://www.nexusmods.com/newvegas/mods/68742)  
NPCs will now use aid items in combat. They will not consume their loot; instead, they will simulate consuming items they can potentially carrying.

[**RAD - Radiation (is) Actually Dangerous - Overhaul**](https://www.nexusmods.com/newvegas/mods/71541)  
Makes radiation work like in Fallout 4, by damaging your max health.

[**Realistic Movement**](https://www.nexusmods.com/newvegas/mods/64202/)  
Movement is slowed for all actors, and their turning speed is also reduced, forcing them to make parabolic turns instead of sharp ones. Movement speed is especially slower for actors who have their weapon out. This makes combat targets less likely to dodge your bullets while strafing. The slowed movement speed and slower turning speed also makes enemies less likely to bolt out suddenly from around a corner in a jerky way.

[**Reload Reloaded**](https://www.nexusmods.com/newvegas/mods/62266)  
Fixes issues with Agility and Strength modifiers for reloading and throwing weapons; makes sneak critical hit damage scale with Sneak; allows grenade throwing range to be affected by Strength.

[**Simple Explosive Entry**](https://www.nexusmods.com/newvegas/mods/66992)  
Allows the player to use explosives to bypass locks. Items have a chance of being destroyed, with the exception of notes and quest items.

## OVERHAULS

[**JSawyer Ultimate Edition**](https://www.nexusmods.com/newvegas/mods/61592)  
Completely reconstructed version of Josh Sawyer's mod, made from the ground up. Tweaks inconsistencies, expands compatibility, re-adds some elements of cut content, and covers additional balance issues which were missed.

Files to install:
- **JSawyer Ultimate Edition** (Main files)
- **JSawyer Ultimate Edition - Push's Tweaks** (Optional files)

> ℹ️ It is recommended that you play New Vegas at **Hard** difficulty or lower when using this mod.

[**JSawyer Ultimate Edition Fixes**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JSawyer%20Ultimate%20Edition%20Fixes.7z)  
Incorporates Yukichigai Unofficial Patch, Weapon Mesh Improvement Mod, and Throwable Weapon Fixes fixes.

[**Food Effect Tweaks - Custom Food Healing**](https://www.nexusmods.com/newvegas/mods/75103)  
Reduces food healing effects to help balance Survival versus Medicine. Affects all items, including from other mods.

[**Mojave Arsenal**](https://www.nexusmods.com/newvegas/mods/62941)  
Adds ammo variants, reloading parts, and weapon mods as loot, fixes item naming conventions, improves recipes, and adds options for configuring Gun Runners' Arsenal.

[**Mojave Arsenal Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Mojave%20Arsenal%20Custom%20INI.7z)  
Custom configuration that disables most GRA features.

[**JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)**](https://www.nexusmods.com/newvegas/mods/62933)  
Compatibility patch for JSawyer Ultimate.

Files to install:
- **JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)** (Main files)

[**Famine - A Loot Rarity Mod**](https://www.nexusmods.com/newvegas/mods/74985)  
Simple and comprehensive loot scarcity mod using event-based scripting.

[**New Vegas Economy Improved**](https://www.nexusmods.com/newvegas/mods/71604)  
Fully-scripted, lightweight, and compatible item value overhaul, taking into consideration important aspects of the vanilla economy balance. Applies a moderate reduction in value to high-value items, and a small reduction to low-value items.

Files to install:
- **New Vegas Economy Improved** (Main files)

[**Player Combat Priority**](https://www.nexusmods.com/newvegas/mods/71699)  
Makes enemies more likely to target the player in combat rather than companions.

[**Repair Tools**](https://www.nexusmods.com/newvegas/mods/74884)  
Makes repairing more difficult by making each repair require a consumable Repair Tools item.

Files to install:
- **Repair Tools** (Main files)
- **Repair Tools - JSawyer Ultimate Push's Tweaks Patch** (Optional files)

[**FNV Opposite Traits**](https://www.nexusmods.com/newvegas/mods/69141?)  
Expands the idea of traits with opposite effects (seen in Fast Shot and Trigger Discipline) to the game's other traits.

Files to install:
- **FNV Opposite Traits (YUP OWB)** (Main files)

[**Improved Traits**](https://www.nexusmods.com/newvegas/mods/65403)  
Edits some vanilla traits and adds two new ones.

[**Improved Traits Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Improved%20Traits%20Tweaks.7z)  
Addresses an unintentional edit that removed Small Frame's Agility requirements, and adds the missing icon for the Four Eyes trait.

[**Improved FNV Opposite Traits**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Improved%20FNV%20Opposite%20Traits.7z)  
Gives the new traits from FNV Opposite Traits the Improved Traits treatment.

[**Better Character Creation**](https://www.nexusmods.com/newvegas/mods/70973)  
Improves the character creation by speeding up the process, adding specialized gear based on your tag skills, and making Wild Wasteland an opt-in feature rather than a trait.

[**Consistent Pip-Boy Icons Mod Patches**](https://www.nexusmods.com/newvegas/mods/65046)  
Collection of upscaled icons for a variety of mods.
- FOMOD options to install:
  - [X] B42 Melee Bash
  - [X] Mojave Arsenal

[**JSawyer Ultimate Edition Patches**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JSawyer%20Ultimate%20Edition%20Patches.7z)  
Collection of compatibility patches for mods installed so far.
- BAIN options to install:
  - [X] 00 Misc Gameplay Merge
  - [X] 01 Push's Tweaks + Miscellaneous Tweaks
  - [X] 02 Push's Tweaks + Mojave Arsenal
  - [X] 03 Mojave Arsenal (GRA Merged) + WMIM
  - [X] 04 Mojave Arsenal (GRA Merged) + Miscellaneous Tweaks
  - [X] 05 Opposite Traits
  - [X] 06 Improved Traits

## CONTENT

[**Uncut Wasteland**](https://www.nexusmods.com/newvegas/mods/56625)  
Restores a huge amount of cut content from the game, from scenery and little random things, to NPCs and creatures.

Files to install:
- **Uncut Wasteland plus NPCs** (Main files)
- **Uncut Extra Collection** (Optional files)
- **Uncut Wasteland Pole Remover** (Optional files)

[**Uncut Extra Collection - JSawyer Ultimate Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Uncut%20Extra%20Collection%20-%20JSawyer%20Ultimate%20Patch.7z)  
Patches Uncut Extra Collection for compatibility with JSawyer Ultimate Edition.

[**Uncut Wasteland Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Uncut%20Wasteland%20Tweaks.7z)  
Includes YUP fixes; omits the NPC restorations at the Ultra-Luxe Bathhouse and replaces static Destitute Travelers with leveled, random NPCs.

[**The Strip NPCs Uncut - Content Restoration**](https://www.nexusmods.com/newvegas/mods/71503)  
Restores some cut but fully-functional NPCs to the Strip.

[**Mojave Raiders**](https://www.nexusmods.com/newvegas/mods/64660)  
Overhaul of New Vegas's raider factions, balancing their loot and adding more of them to fight.

Files to install:
- **Mojave Raiders** (Main files)
- **Mojave Raiders - Nipton Takeover Disabled** (Optional files)
- **Mojave Raiders - No NPC Throwing Weapon Consumption** (Optional files)

[**No NPC Throwing Weapon Consumption - WMIM Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/No%20NPC%20Throwing%20Weapon%20Consumption%20-%20WMIM%20Patch.7z)  
Compatibility patch for Weapon Mesh Improvement Mod.

[**JSawyer Ultimate - Mojave Raiders Patch**](https://www.nexusmods.com/newvegas/mods/62933)  
Compatibility patch for JSawyer Ultimate.

[**Mojave Wildlife**](https://www.nexusmods.com/newvegas/mods/64638)  
Adds hundreds more leveled, vanilla-friendly creature spawn points throughout the whole Mojave, based off unused vanilla leveled lists. All spawn points are meticulously hand-placed and distributed as evenly and fairly as possible.

Files to install:
- **Mojave Wildlife - Vanilla No Chanced Spawns Version** (Main files)

## AUDIO

[**All Weapon Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/62870)  
Replaces every gun sound in the game, from ballistic to energy weapons.

[**All Weapon Sounds Overhaul ESP Replacer**](https://github.com/VivaNewVegas/Living-in-New-Vegas/blob/master/All%20Weapon%20Sounds%20Overhaul%20ESP%20Replacer.7z)  
Scripted ESP replacer that vastly improves compatibility with other mods.

[**All Weapon Sounds Overhaul WMIM Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/All%20Weapon%20Sounds%20Overhaul%20WMIM%20Patch.7z)  
Compatibility patch for Weapon Mesh Improvement Mod.

[**All Explosion Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/66946)  
Replaces every explosion sound in the game.

Files to install:
- **All Explosion Sounds Overhaul BSA and YUP Patch** (Main files)
- **All Explosion Sounds Overhaul SCRIPT Version** (Optional files)

[**Immersive Primary Needs**](https://eddoursul.win/mods/immersive-primary-needs/)  
As hunger, thirst or sleep deprivation increase, the player is notified by periodic sound effects. These effects kick in shortly before the first penalties occur, so the player is given a chance to eat, drink or sleep in time.

Files to install:
- **Project Nevada - Immersive Primary Needs 1.1**  
  Install as **Immersive Primary Needs**.

[**Female Nuka-Cola Drinking Sound Replacer**](https://www.nexusmods.com/newvegas/mods/68476)  
Replacer for the male drinking sound the game plays whenever you consume a Nuka-Cola.

Files to install:
- **Female Nuka-Cola Drinking Sound replacer** (Main files)

> ⚠️ You should only use this mod when playing a female character, since it replaces the vanilla male drinking sound.

## VISUALS

### Animations

[**Anniversary Anim Pack**](https://www.nexusmods.com/newvegas/mods/70158)  
Merge of many animation mods by the same author, improving the game's overall look and feel when it comes to gunplay.

Files to install:
- **Anniversary Anim Pack** (Main files)
  - Hide/delete all folders inside **Meshes** minus the **Meshes\Characters** folder.

[**Anniversary Anim Pack - General Bugfix**](https://www.nexusmods.com/newvegas/mods/72320)  
Fixes camera jumps, animation snapping, movement lock, and broken aim in 3rd person when using Anniversary Anim Pack.

Files to install:
- **AnniAnimPack_BugFix 1.3** (Main files)  
- **Bonus Patch** (Main files)

[**FNV Clean Animations**](https://www.nexusmods.com/newvegas/mods/70599)  
Clean first person animations. No new idles, no bugs, no reload cancelling from shooting early or crouching, no compatibility issues.

Files to install:
- **FNV Clean Animations** (Main files)
- **FNV Clean Animations - Update 2.2.2** (Update files)

[**ISControl Enabler**](https://www.nexusmods.com/newvegas/mods/75417)  
Removes the need to manually patch weapons for animations using the ISControl node system, used in most kNVSE sets by New Vegas animators. Works with every weapon and every mod, instantly.

[**Immersive Recoil 2.0**](https://www.nexusmods.com/newvegas/mods/61973)  
Adds recoil animations to player and NPCs. Recoil strength is calculated based on weapon base damage, requirements, condition and weight, and the character's skill and strength. Aiming down sights and crouching also reduces recoil.

[**Viewmodel Recoil 0.308**](https://www.nexusmods.com/newvegas/mods/71852)  
Adds a visual recoil mod that affects first person model only and doesn't move the camera at all.

[**B42 Weapon Inertia**](https://www.nexusmods.com/newvegas/mods/64335)  
Adds weapon inertia, causing weapons to slightly lag behind camera movement to give a feeling of weight to them.

[**Ragdolls**](https://www.nexusmods.com/newvegas/mods/59147)  
Improves ragdoll behaviour for all NPC/Creatures in the game and restores hit reactions. Very configurable.

Files to install:
- **Ragdolls** (Main files)

[**Ragdolls Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Ragdolls%20Custom%20INI.7z)  
Custom configuration that enables ragdoll momentum, corpse toucher, hit reactions, and complex death reactions features. 

[**Ragdolls YUP Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for Yukichigai Unofficial Patch.

[**Ragdolls DLC Enhancements Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for Essential DLC Enhancements.

[**Diagonal movement**](https://www.nexusmods.com/newvegas/mods/64333)  
Adds diagonal movement.

[**360 Movement**](https://www.nexusmods.com/newvegas/mods/71940)  
Adds 360 degrees movements with procedural leaning, and auto vanity mode to make the game feel more like later Bethesda games.
- Also install the **Diagonal Movement Patch** in the FOMOD installer.

[**Player Headtracking**](https://www.nexusmods.com/newvegas/mods/66741?)  
Enables headtracking for the player character.

[**NV Compatibility Skeleton**](https://www.nexusmods.com/newvegas/mods/68776)  
A compatible skeleton for many animation mods.
- FOMOD options to install:
  - [X] Vanilla Weights

### VFX

[**IMPACT**](https://www.nexusmods.com/newvegas/mods/57113)  
Ballistic VFX overhaul. Bullet holes match ammo, casings match ammo, new custom particle effects impacts.

Files to install:
- **IMPACT - The Michael Bay** (Main files)

[**IMPACT - Compatibility Edition**](https://www.nexusmods.com/newvegas/mods/62050)  
Scripted ESP replacer that automatically patches all weapons in the game, DLC, and mods, to have the appropriate shell casings and Impact Data Sets based on their ammo types.

[**EXE - Effect teXtures Enhanced**](https://www.nexusmods.com/newvegas/mods/62989)  
Remakes all visual effects in the game.

[**Enhanced Blood Textures**](https://www.nexusmods.com/newvegas/mods/34917)  
Remakes blood visual effects, including the addition of new types of wounds based on weapon type.

[**Gore Overhaul**](https://www.nexusmods.com/newvegas/mods/67666)  
Retextures the gore assets to give them a severely detailed look with attention to minor details. Also improves on the exploding head meshes to give it more gore bits.

[**Gore Overhaul Optimized Textures**](https://www.nexusmods.com/newvegas/mods/75268)  
Optimizes the very high resolution textures, without noticeably sacrificing quality.

[**Better Gas Leak Effect**](https://www.nexusmods.com/newvegas/mods/55606)  
Improves the gas leak refraction effect, making it easier to spot.

[**More Subtle Hidden Valley Dust Storm**](https://www.nexusmods.com/newvegas/mods/70275)  
Tones down the dust storm effect near the Hidden Valley bunkers.

### Characters

[**Character Expansions Revised**](https://www.nexusmods.com/newvegas/mods/64862)  
Visual overhaul of characters' faces, following vanilla aesthetics. 

[**Character Expansions Revised - YUP - JSU - UW - MR**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Character%20Expansions%20Revised%20-%20YUP%20-%20JSU%20-%20UW%20-%20MR.7z)  
Merged compatibility patch for Yukichigai Unofficial Patch, JSawyer Ultimate, Uncut Wasteland, and Mojave Raiders.

[**Character Expansions Revised - UW Extra Collection**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Character%20Expansions%20Revised%20-%20UW%20Extra%20Collection.7z)  
Addendum compatibility patch for Uncut Wasteland Extra Collection.

[**Character Expansions Revised - FaceGen Tint Fix**](https://www.nexusmods.com/newvegas/mods/75268)  
Fixes colored tints on character faces.
- [**Visual comparison.**](https://imgsli.com/ODY2MzE)

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/71577?) to original mod by **BobG123**, whose fixed meshes were used as a resource for this mod.

[**Eyelashes New Vegas**](https://www.nexusmods.com/newvegas/mods/34790)  
Adds animated eyelashes to NPCs and the player character.

Files to install:
- **tkEyelashesFNV** (Main files)
  - Hide **tkEyelashesFNV_FemalesOnly.esp**.

[**Eyelashes New Vegas ESP Replacer**](https://www.nexusmods.com/newvegas/mods/75268)  
ESP Replacer that fixes issues with the plugin, and extends support to Honest Hearts' tribals and Dead Money's Christine.

[**HD Teeth and Natural Eyelashes and Eyebrows**](https://www.nexusmods.com/newvegas/mods/53695)  
Improves teeth, eyelashes, and eyebrow textures.

Files to install:
- **Eyelashes 1.3** (Main files)  
- **HD teeth 3.0** (Main files)
- **HQ eyebrows** (Main files)

[**Natural Eyes by zzjay**](https://www.nexusmods.com/newvegas/mods/62811)  
Improves eye textures.

Files to install:
- **00 - Natural Eyes - Shadow** (Main files)

[**Vanilla Hair - No Shine**](https://www.nexusmods.com/newvegas/mods/50285)  
Removes shine from vanilla hairs.

[**No Pip-Boy Glove**](https://www.nexusmods.com/newvegas/mods/69258)  
Removes the completely useless and ugly Pip-Boy glove from the player.

[**Pip-Boy 2000 Mk VI**](https://www.nexusmods.com/newvegas/mods/65980)  
Pip-Boy replacer with custom scratch-made meshes, textures and working clock like in Fallout 76.

Files to install:
- **Pip-Boy 2000 Mk VI replacer version** (Main files)
- **Working date and clock for replacer** (Optional files)

[**Pip-Boy 2000 Mk VI Working Buttons**](https://www.nexusmods.com/newvegas/mods/75268)  
Makes the Pip-Boy 2000 Mk VI's buttons functional. Mod by **AleksMarch**.

[**NPC Arm Mounted Pip-Boy 2000 Mk VI**](https://www.nexusmods.com/newvegas/mods/75268)  
Makes NPCs wear the new Pip-Boy 2000 Mk VI.

[**Pip-Boy 2000 MK VI (Wasteland Edition) Retexture**](https://www.nexusmods.com/newvegas/mods/65999)  
Gives the Pip-Boy 2000 Mk VI a grittier texture.

### Environment

[**A Little More Lamplight**](https://www.nexusmods.com/newvegas/mods/69226)  
Enhances the shoddy work on the vanilla functional streetlamps and lights of Outer Vegas, Camp McCarran, Camp Golf, and the NCRCF. 

[**Clean Lucky 38**](https://www.nexusmods.com/newvegas/mods/74796)  
Retextures and cleanups the interior of the Lucky 38.

Files to install:
- **Clean Lucky 38 Mesh Fix** (Update files)

> ℹ️ This file is not an update, but the latest version of the mod.

[**LSO - A Lightweight Strip Overhaul**](https://www.nexusmods.com/newvegas/mods/65665)  
Turns walls from junk to brick, cleans the litter up off of the street, and buffs out the cracked marble and peeling wallpaper as well as much more, making the Strip far more pleasing to the eye.

Files to install:
- **Lightweight Strip Overhaul - No Walls** (Main files)
- **Lightweight Strip Overhaul - Uncut Wasteland Patch** (Optional files)

[**Strip Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/73324)  
Adds lights to the Strip where lights existed but where not producing light. Also fixes a number of vanilla bugs via editing the environment and certain meshes.

[**Strip Lighting Overhaul LSO Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for Lightweight Strip Overhaul.

[**Palm Tree Replacer**](https://www.nexusmods.com/newvegas/mods/72917)  
Replaces the dated palm trees seen on the Strip with way better custom models. Installed for consistency with The Strip Planters Fixed.

[**The Strip Planters Fixed**](https://www.nexusmods.com/newvegas/mods/73406/)  
Fixes the planters on the Strip.

[**Ultra-Luxe Fountain Expanded**](https://www.nexusmods.com/newvegas/mods/69781)  
Improves the Ultra-Luxe fountain by adding additional water streams with accompanying sound effects as well as eight new light beams above the embedded lights in the base of the fountain.

[**Wasteland Flora Overhaul Grass**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Wasteland%20Flora%20Overhaul%20Grass.7z)  
Improves grass textures.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/39856) to original mod by **vurt**. The featured version omits non-grass related meshes and textures.

[**Windows of the Mojave**](https://www.nexusmods.com/newvegas/mods/67247)  
Improves interior atmosphere, fixing inconsistencies with cell interiors where the buildings had outside windows but no interior windows whatsoever.

[**More Subtle New Vegas Light Pollution**](https://www.nexusmods.com/newvegas/mods/73579)  
Reduces the distant glow of New Vegas for the sake of darker nights.

Files to install:
- **Slightly Brighter** (Main files)

[**Desert Natural Weathers**](https://www.nexusmods.com/newvegas/mods/75437)  
An overhaul of the weathers in New Vegas with 360 panoramic cloud textures, DLC support, and optional presets for Reshade and ENB.

Files to install:
- **Desert Natural Weathers 3.0** (Main files)
- **Desert Natural Weathers 3.0 Hotfix** (Update files)
- **Restore fake interior godrays.** (Optional files)

[**Desert Natural Weathers - Zion Ambient Music**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Desert%20Natural%20Weathers%20-%20Zion%20Ambient%20Music.7z)  
Adds vanilla ambient music to the Zion worldspace.

[**HD Moon 2K - Dark Side of the Moon**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/HD%20Moon%202K%20-%20Dark%20Side%20of%20the%20Moon.7z)  
High quality retexture of the moon using NASA satellite images.

[**Accurate NASA Stars**](https://www.nexusmods.com/newvegas/mods/75522)  
Star texture and mesh using NASA satellite images to create a real-world accurate starfield.

Files to install:
- **Accurate Stars 4k** (Main files)

[**HD Mist**](https://www.nexusmods.com/newvegas/mods/58955)  
High resolution retexture for mist.

Files to install:
- **HD Mist 2K** (Main files)

[**HQ Dust Storm FX**](https://www.nexusmods.com/newvegas/mods/53863)  
High resolution retexture for dust storms.

[**Night Sky Tweaks**](https://www.nexusmods.com/newvegas/mods/73529)  
Fixes the bright night sky horizons.

Files to install:
- **Night Sky Tweaks (Script Runner)** (Main files)

## LOD RESOURCES

[**Improved LOD Noise Texture**](https://www.nexusmods.com/newvegas/mods/46451)  
Vastly improves the LOD noise texture used on distant land.

Files to install:
- **Improved LOD noise Texture** (Main files)

[**FNVLODGen Resources**](https://www.nexusmods.com/newvegas/mods/58562)  
Adds extra meshes for LOD generation.

Files to install:
- **FNVLODGen Resources** (Main files)  

[**LOD Additions and Improvements**](https://www.nexusmods.com/newvegas/mods/61206)  
Adds extra meshes for LOD generation.

[**LOD Additions and Improvements YUP Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for Yukichigai Unofficial Patch.

[**FNV LOD Supplementation**](https://www.nexusmods.com/newvegas/mods/72099)  
Adds extra meshes for LOD generation.

[**TCM's LOD Overhaul**](https://www.nexusmods.com/newvegas/mods/70155)  
Adds extra meshes for LOD generation.

[**Much Needed LOD**](https://www.nexusmods.com/newvegas/mods/64805)  
Adds extra meshes for LOD generation.

[**Much Needed LOD YUP Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for Yukichigai Unofficial Patch.

[**Better Strip View**](https://www.nexusmods.com/newvegas/mods/73261)  
Adds visible Strip signs and moves the Strip buildings to where they should be.

Files to install:
- **Better Strip View** (Main files)

[**Better Strip View - More Subtle New Vegas Light Pollution Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for More Subtle New Vegas Light Pollution.

[**Hoover Dam Jets Restored and Distant**](https://www.nexusmods.com/newvegas/mods/72135)  
Restores the cut outflow jets to Hoover Dam and makes them visible up and down the Colorado.

Files to install:
- **Hoover Dam Jets Restored and Distant** (Main files)
- **HDJRaD - Much Needed LOD Patch** (Optional files)  

[**Strip Lights Region Fix**](https://www.nexusmods.com/newvegas/mods/73596)  
Fixes a vanilla issue about the Strip lights not showing in certain parts of the map.

Files to install:
- **Strip Lights Region Fix** (Main files)
- **Strip Lights Region Fix - Hoover Dam Jets Restored and Distant** (Optional files)
- **Strip Lights Region Fix - Uncut Wasteland** (Optional files)

[**Lucky 38 Lights Redone**](https://www.nexusmods.com/newvegas/mods/73273)  
Modifies the Lucky 38 lights before and after they have been turned on during the Mr. House/Yes Man questlines.

Files to install:
- **Lucky 38 Lights Redone - Full Model** (Main files)
- **Lucky 38 Lights Redone - Full Model - Better Strip View** (Optional files)

## GENERATED LOD

[**FNVLODGen Output Extended**](https://drive.google.com/file/d/1fT7k67vv-K6QLhiJ9UrIMheJXuBewwNT/view?usp=sharing)  
Generated LOD for users who have followed the guide from beginning to bottom. Uses vanilla textures.

> ⚠️ ONLY INSTALL THIS MOD IF YOU'VE FOLLOWED THE **VISUALS** AND **LOD** SECTIONS TO THE LETTER. Else, you will have to generate your own LOD following the instructions in the following section.

## FINISHING TOUCHES

### Mod order and load order

[**I Heart New Vegas MO2 Profile Files**](https://github.com/Sigourn/iheartnewvegas/blob/main/I%20Heart%20New%20Vegas%20MO2%20Profile%20Files.7z)  
Adjusts mod order and load order for I Heart New Vegas to work as intended.
- Extract the files into **C:\Games\Fallout New Vegas Mods\MO2\profiles\I Heart New Vegas**, overwriting when prompted.

> ℹ️ Mod order dictates the priority a given mod's assets have over the mods installed before it. This is handled by **modlist.txt**.
 
> ℹ️ Load order dictates the priority a given mod's plugins have over the mods' plugins loaded before them. This is handled by **loadorder.txt**.

### Settings config

The following settings need to be configured after you've already started a new save, using the in-game **Settings** option.

**Gameplay**:
- Set **Killcam Mode** to None.
- Set **Difficulty** to Hard.

**Controls -> Action Mapping**:
- Set **VATS** to Esc in order to disable the keybinding.
- Set **Ammo Swap** to Esc in order to disable the keybinding.

### MCM config

The following settings need to be configured after you've already started a new save, using the in-game **Mod Configuration** option.

**Quick Grenade Hotkey**:
- Set **Grenade Hotkey** to **G**.
- Set **Grenade Swap Hotkey** to **C**.

**RAD**:
- Set **Hardcore** to **ON**.
- Set **JSawyer Increments** to **ON**.

> ℹ️ Sleep deprivation, hunger, and thirst will affect max AP; makes the former setting follow JSawyer's stat penalties progression.

### INI config

**falloutcustom.ini (Optional)**:
- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Paste the following into **falloutcustom.ini**.

```
[Imagespace]
bDoDepthOfField=0

[Interface]
fDlgFocus=5.0000
uPipboyColor=1022886143

[Grass]
iMinGrassSize=40
```

> ℹ️ Disables vanilla depth of field effect seen during dialogue; reduces the amount of zoom when engaging in dialogue; tweaks the Pip-Boy HUD color to match that of classic Fallout; increases grass density.

### Generating LOD

> ⚠️ Assuming you use a different mod setup than the one recommended in the guide, you will have to generate LOD yourself.

- Run **FNVLODGen** in MO2.
- Right click on the list of worldspaces, and click **Select All**.
- Click **Generate**. The process will take some time.
- After the **LOD Generator: finished (you can close this application now)** message appears, close the program.

Now all that's left is to install our generated LOD.

- Navigate to your **Fallout New Vegas Mods\FNVLODGen Output** folder, and make an archive out of the **textures** and **meshes** folder. Name it **FNVLODGen Output**.
- Install **FNVLODGen Output** with MO2.

# MOD KEYBINDINGS

This is a handy reference table which will hopefully help you have a better idea of what new hotkeys are available to you, having followed this guide from beginning to end.

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

# CHANGELOG

<details>
	<summary>Click to expand</summary>

03-03-2022
- Updated **Desert Natural Weathers** installation instructions (Visuals).
- Updated **RAD** MCM config instructions (**MCM Config**).

03-02-2022
- Moved the additional NVSE bug fixes, Pip-Boy related mods, and the additional LOD resources, into the main guide. Now only one FNVLODGen Output is provided as a result.
- Moved FNVLODGen instructions to the bottom of **Finishing Touches**, as it's the only thing that's entirely optional about that section.
- Updated **Desert Natural Weathers** installation instructions (Visuals).
- Re-added **B42 Melee Bash** (Gameplay).
- Added **Accurate NASA Stars** (Visuals).
- Removed **RAD - Radiation (is) Actually Dangerous**. The **Overhaul** completely replaces this mod now.

02-28-2022
- Updated **Desert Natural Weathers** installation instructions (Visuals).
- Removed **JSawyer Ultimate - Mojave Arsenal Patch (GRA Merged) - Hunting Revolver Iron Sights Patch** from modlist.txt (the plugin was removed in an earlier update).
	
02-27-2022
- Updated **Weapon Mesh Improvement Mod** install instructions (Patches).
- Updated **Weapon Mesh Improvement Mod ESP Replacer** (Patches).
- Updated **JSawyer Ultimate Edition Fixes** with latest WMIM fixes, and renamed the .esp (Overhauls).
- Updated **JSawyer Ultimate Edition Patches** with latest WMIM fixes (Overhauls).
- Added **No NPC Throwing Weapon Consumption - WMIM Patch** (Content).
- Removed **Laser Weapon Iron Sights** (Gameplay QOL).
	
02-26-2022
- Renamed text files to **I Heart New Vegas MO2 Profile Files**.
- Added **Food Effect Tweaks - Custom Food Healing** (Overhauls).
- Added **Uncut Extra Collection** file to **Uncut Wasteland**'s installation instructions (Content).
- Added **Uncut Extra Collection - JSawyer Ultimate Patch** (Content).
- Added **Character Expansions Revised - UW Extra Collection** (Visuals).
- Added **Desert Natural Weathers** (Visuals). HD Mist and HQ Dust Storm FX have been moved after it in the mod order.
- Added **Desert Natural Weathers - Zion Ambient Music** (Visuals).
- Added **HD Moon 2K - Dark Side of the Moon** (Visuals).
- Added grass density tweaks (INI Config).
- Removed **Altitude** (Visuals). Replaced by Desert Natural Weathers.
- Removed **Elegant Sunglare Retexture** (Visuals). Included in Desert Natural Weathers.
- Removed **HD Moon 2K - NASA Satellite Images** (Visuals). Replaced by HD Moon 2K - Dark Side of the Moon.
- Removed **Enhanced Vanilla Stars 2K** (Visuals). Included in Desert Natural Weathers.

02-25-2022
- Added **ISControl Enabler** (Visuals).
- Removed **Misc Gameplay Merge YUP Patch** (Gameplay).
- Removed **JSawyer Ultimate Tweaks** (Overhauls).
- Removed **Weapon Mesh Improvement Mod Patch** from **Anniversary Anim Pack** (Visuals).
	
02-21-2022
- Modified **Vanilla UI Plus (New Vegas)** to use the Classic Pip-Boy Font option instead of Default Font Tweaks (User Interface).
- Added **JIP LN NVSE Plugin Custom INI** (xNVSE Plugins).
- Added **yUI - User Ynterface Custom INI** (xNVSE Plugins).
- Added **Vanilla UI Plus (New Vegas) Custom Settings** (User Interface).
- Added **yUI - Sorting Ycons** (User Interface).
- Added **Barton Thorn Acts Normally** (Addendum).
- Added **Cannibal Reborn** (Addendum).
- Added **Cannibal Reborn Expanded** (Addendum).
- Added **Empty Clicks - Improved Dry Fire Sounds** (Addendum).
- Added **Even More Accurate Geiger Clicking** (Addendum).
- Added **Gun Runners Kiosk Glass Fix** (Addendum).
- Added **High-Quality Classic Music** (Addendum).
- Added **Immersive Pickup Sounds Patched** (Addendum).
- Added **Improved Duster Coats - YUP Edition** (Addendum).
- Added **Lower-sitting Ranger Hat** (Addendum).
- Added **Lucky 38 Mainframe No Fingerprints** (Addendum).
- Added **Red Vault 19 Jumpsuits** (Addendum).
- Added **Securitrons in CRT** (Addendum).
- Added **Simple Glowing Ranger Visors** (Addendum).
- Added **Snowglobe Tweaks Fix** (Addendum).

02-18-2022
- Removed **Less Map Markers**.
- Updated **lStewieAl's Tweaks Custom INI** to remove increased XP gain for discovering locations.
- Updated **Miscellaneous Tweaks Collection Tweaks** to restore removed map markers.

02-17-2022
After careful consideration of the pros and cons, the guide now recommends the 1.3 version of **Weapon Mesh Improvement Mod**. The following changes are made with this in mind.
- Updated **WMIM ESP Replacer** (Patches)
- Updated **Throwable Weapon Fixes - WMIM Patch** (Patches)
- Updated **JSUE Fixes** (Overhauls)
- Updated **JSawyer Ultimate Edition Patches** (Overhauls)
- Re-added **Laser Weapon Iron Sights** (Gameplay QOL)
- Re-added **Anniversary Anim Pack** (Visuals)
- Re-added **Anniversary Anim Pack - General Bugfix** (Visuals)
- Re-added **FNV Clean Animations** (Visuals)
- Removed **No NPC Throwing Weapon Consumption - WMIM Patch** (Content), as it is no longer needed.
In addition, the modlist and loadorder files now contemplate for the recommended mods in my **Misc Immersion Merge** page.

02-16-2022 Hotfix  
In lieu of **Weapon Mesh Improvement Mod**'s update, which includes iron sights for energy weapons, and which makes it incompatible with many other mods present in this guide, the following have been removed.
- Removed **Laser Weapon Iron Sights** (Gameplay QOL)
- Removed **Anniversary Anim Pack** (Visuals)
- Removed **Anniversary Anim Pack - General Bugfix** (Visuals)
- Removed **FNV Clean Animations** (Visuals)

And, since we are at it, the following mods have also been removed for simplicity:
- Removed **B42 Melee Bash** (Gameplay)
- Removed **Enhanced Vision** (Gameplay)
- Removed **Khans Friendly to Fiends** (Content)
- Removed **Canvas Backpacks - Remade** (Content)
- Removed **Canvas Backpacks - Remade - JSawyer Ultimate Edition Patch** (Content)
- Removed **Crippled Limb Reaction Enforcer** (Addendum)
- Removed **Equip Reload and Movement Speed Fix** (Addendum)
- Removed **Gauss Rifle VATS Fix - JIP** (Addendum)
- Removed **Meltdown NVSE Upgrade** (Addendum)
- Removed **Mine and Explosion Tweaks** (Addendum)
- Removed **Miss Fortune NVSE Upgrade** (Addendum)
- Removed **Spore Plant Melee Attack and Tweaks** (Addendum)
- Removed **Spore Plant Melee Attack and Tweaks YUP Patch** (Addendum)
- Removed **Well Rested Overhaul** (Addendum)

02-16-2022
- Updated **JSawyer Ultimate Edition Fixes**. Missed a few changes regarding the pre-order Broad Machete.
- Updated **WMIM ESP Replacer**. Removed records relating to the unimplemented Weathered 10mm Pistol (Tale of Two Wastelands left-over). These were overwriting the fixed pre-order Weathered 10mm Pistol from Yukichigai Unofficial Patch.
- Added **Throwable Weapon Fixes - WMIM Patch**.
- Added **No NPC Throwing Weapon Consumption - WMIM Patch**.

02-15-2022
- Updated **WMIM ESP Replacer** for the latest Weapon Mesh Improvement Mod release (1.4).
- Updated **JSawyer Ultimate Edition Patches**. Added WMIM patch.
- Added **JSawyer Ultimate Edition Tweaks** and **JSawyer Ultimate Edition Fixes**. These replaces **JSawyer Ultimate Edition - Tweaks**. The former is Qolore's original mod (JSUE Tweaks.esp), while the latter is my all-in-one compatibility patch for YUP, WMIM and Throwable Weapon Fixes (JSUE Fixes.esp). This was done to improve compatibility with the Viva New Vegas guide.
- Load order properly reflects the latest version of **Famine - A Loot Rarity Mod** (was missing Famine - Flora.esp).

02-12-2022
- Updated **Character Expansions Revised - FaceGen Tint Fix**. It includes BSA compression thanks to **doodlez**. Make sure to reinstall the mod using this name.
- Updated **Mojave Raiders** installation instructions. Now the additional **Nipton Takeover Disabled** optional file is recommended for installation.
- Updated **lStewieAl's Tweaks Custom INI**. The capping of skills based on SPECIAL has been disabled.

02-11-2022
- Added **Better Gas Leak Effect** (Visuals).
- Added **HD Mist** (Visuals).
- Added **HQ Dust Storm FX** (Visuals).
- Added **More Subtle Hidden Valley Dust Storm** (Visuals).
- Added **Helmet Armor Rebalance** (Gameplay).
- Added **Equip Reload and Movement Speed Fix** (Addendum).
- Added **Melee VATS Animation Restoration** (Addendum).
- Added **Mine and Explosion Tweaks** (Addendum).
- Added **Spore Plant Melee Attack and Tweaks** (Addendum).
- Added Body Replacers sub-section (Addendum).

02-10-2022
- Added **Altitude** (Visuals). Replaces **FNV Realistic Wasteland Lighting**. It also requires no region or worldspace patch.
- Added **Elegant Sunglare Retexture** (Visuals).
- Added **Enhanced Vanilla Stars 2K** (Visuals).
- Added **HD Moon 2K - NASA Satellite Images** (Visuals).
- Removed **Mojave Nights**.

02-09-2022
All the removed mods in this update are compatible with the guide.
- Moved **B42 Melee Bash** to the main guide (Gameplay). Updated Mod Keybindings section.
- Moved **Enhanced Vision** to the main guide (Gameplay). Updated Mod Keybindings section and MCM Config section.
- Moved **Realistic Movement** to the main guide (Gameplay).
- Moved **Canvas Backpacks - Remade** to the main guide (Content).
- Removed **B42 Inspect - aka Animated Ammo and Weapon Condition Checking** (Addendum).
- Removed **Cannibal Reborn** (Addendum).
- Removed **Cannibal Reborn Expanded** (Addendum).
- Removed **Even More Accurate Geiger Clicking** (Addendum).
- Removed **Immersive Pickup Sounds** (Addendum). For an updated version of the mod, check out [**Immersive Pickup Sounds Patched**](https://www.nexusmods.com/newvegas/mods/70552).
- Removed **No Cocking Sound on Rifle Equip** (Addendum).
- Removed **Snowglobe Tweaks Fix** (Addendum).

02-07-2022
- Added **Misc Immersion Merge** (Gameplay).
- Moved **Essential DLC Enhancements Merged** to (Gameplay).
- Added link to addendum guide.

02-06-2022
- Reworked the guide as it will be split into a main and add-on documents, like my Morrowind guide is. Pretty much every mod removed since the last update will be present in this add-on guide.
- Mod order and load order is now handled by a download that needs to be installed on your MO2 profile folder. These require mods to be installed under specific names, those of which are provided by default by MO2. The ones that require a different name are mentioned in the guide.
- **No Stealing After Repair** is now included in **lStewieAl's Tweaks Custom INI**.
- **FNVLODGen Output** has been updated to reflect the removal of many LOD mods.
- Added **Much Needed LOD YUP Patch**.
</details>

# ADDITIONAL MODS

For additional mods that tackle more specific aspects of the game, [**check out the addendum guide**](https://github.com/Sigourn/iheartnewvegas/blob/main/addendum.md).

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)
