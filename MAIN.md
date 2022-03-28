[<< Back to Readme](https://github.com/Code-Moss/I-Heart-New-Vegas-Mossy-Cut/blob/main/README.md)  
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

## NVSE PLUGINS

[**JIP LN NVSE Plugin**](https://www.nexusmods.com/newvegas/mods/58277)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**JIP LN NVSE Plugin Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JIP%20LN%20NVSE%20Plugin%20Custom%20INI.7z)  
Enables Fallout 3-style repair, localized damage (allowing headshots to be more powerful when the enemy has no helmet), and a chance for random NPCs to have weapon mods. Disables the voice modulation fix, which could cause noticeable audio popping, particularly in Elijah's dialogue.

[**JohnnyGuitar NVSE**](https://www.nexusmods.com/newvegas/mods/66927)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**ShowOff NVSE**](https://github.com/Demorome/Showoff-NVSE/releases)  
Adds new functions, engine bug fixes and tweaks.
- Click the **ShowOffNVSE.7z** under **Assets** to download it.
 
[**kNVSE Animation Plugin**](https://www.nexusmods.com/newvegas/mods/71336)  
Enables having custom animations for weapons and actors. Also fixes the engine-bound anim group limit problem.

[**OneTweak 2.1.0.2**](https://www.nexusmods.com/newvegas/mods/75685)  
Enables borderless window mode for safe alt-tabbing.
- After installing the mod in MO2, click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button.
- Click **INI Editor**. Select the **FalloutCustom.ini** tab.
- Set **bFull Screen** to 0.

[**NVAC - New Vegas Anti Crash**](https://www.nexusmods.com/newvegas/mods/53635)  
Implements structured exception handling and sanity checking to reduce frequency of game crashes.

[**NVTF - New Vegas Tick Fix**](https://www.nexusmods.com/newvegas/mods/66537)  
Fixes the tick count bug (which creates noticable micro stutter), optimizes hash tables (helping performance and decreasing menu load times), and fixes the high FPS bug (fixing physics and lipsync at high framerates).

[**NVTF Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/NVTF%20Custom%20INI.7z)  
Custom configuration that enables a number of settings to achieve the best balance between performance and stability.

[**FNV Mod Limit Fix**](https://www.nexusmods.com/newvegas/mods/68714)  
Allows a maximum of 255 plugins to be loaded, as well as improving FPS, removing game stutter, and allowing for faster loading times (particularly when using a large number of mods).

[**Improved lighting Shaders**](https://www.nexusmods.com/newvegas/mods/69833)  
Almost completely fixes the exterior lighting bug, and allows up to four times the number of active lights.

[**yUI - User Ynterface**](https://www.nexusmods.com/newvegas/mods/74357)  
Aims to fix UI bugs and add new UI features. 

Files to install:
- **yUI** (Main files)
- **Matched Cursor - Fallout New Vegas** (Optional files)  

[**yUI - User Ynterface Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/yUI%20-%20User%20Ynterface%20Custom%20INI.7z)  
Matches cursor color to HUD color,  required for the Matched Cursor - Fallout New Vegas file we installed earlier.

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

[**WMIM ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/WMIM%20ESP%20Replacer%201.4.7z)  
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

> ℹ️ Unfortunately there were many mods that I would have liked to include in this compilation, but couldn't. For the sake of this guide these are not considered essential, but know that I Heart New Vegas does account for them in its mod and load order. If you wish to install them, see the following summary of mods.

<details>
	<summary>Misc Immersion Merge Addendum</summary>

[**Cannibal Reborn**](https://www.nexusmods.com/newvegas/mods/64789)  
Adds gore effects when devouring corpses, makes health and hunger restored from cannibalism scale with Survival, and adds numerous quality of life improvements.

Files to install:
- **Cannibal Reborn** (Main files)

[**Cannibal Reborn Expanded**](https://www.nexusmods.com/newvegas/mods/75054)  
Applies the cannibalism effects and quality of life improvements from Cannibal Reborn to the Ghastly Scavenger perk.

[**Empty Clicks - Improved Dry Fire Sounds**](https://www.nexusmods.com/newvegas/mods/68941)  
Different dry fire (empty magazine) sounds depending on a weapon type and some other improvements.

[**Even More Accurate Geiger Clicking**](https://www.nexusmods.com/newvegas/mods/74901)  
Increases the Pip-Boy Geiger clicking beyond the vanilla default. Increases the accuracy of the radiation meter. Forces the speed effects of the Atomic! perk to apply immediately.

Files to install:
- **Even More Accurate Geiger Clicking** (Main files)

[**Gun Runners Kiosk Glass Fix**](https://www.nexusmods.com/newvegas/mods/70293)  
Fixes the glass texture in the Gun Runners' kiosk.

Files to install:
- **Gun Runners Kiosk Glass Fix Alternate Version** (Optional files)

[**High-Quality Classic Music**](https://www.nexusmods.com/newvegas/mods/72150)  
Replaces the low-quality soundtrack from the classic Fallout games with high-quality versions.

[**Immersive Pickup Sounds Patched**](https://www.nexusmods.com/newvegas/mods/70552)  
Adds a variety of sound effects for picking up numerous items.

[**Improved Duster Coats - YUP Edition**](https://www.nexusmods.com/newvegas/mods/66629)  
Modifies the overcoats on the NCR Ranger and Desert Ranger armors so they hang straight rather than flaring out at the base. Includes mesh fixes from Yukichigai Unofficial Patch.

[**Lower-sitting Ranger Hat**](https://www.nexusmods.com/newvegas/mods/68799)  
Modifies the Ranger Hat and the Park Ranger Hat so they sit slightly lower on the head. 

[**Lucky 38 Mainframe No Fingerprints**](https://www.nexusmods.com/newvegas/mods/74055)  
Gets rid of the big fingerprint on Mr. House/Yes Man's screen. 

[**Red Vault 19 Jumpsuits**](https://www.nexusmods.com/newvegas/mods/67135)  
Adds red versions of the Vault 19 jumpsuit to the red sections of the vault.

[**Securitrons in CRT**](https://www.nexusmods.com/newvegas/mods/63258)  
Adds CRT lines to the monitors of Securitrons.

Files to install:
- **Securitrons in CRT 1.0** (Main files)
- **OWB in CRT** (Optional files)

[**Simple Glowing Ranger Visors**](https://www.nexusmods.com/newvegas/mods/66628)  
Makes the visors of all the Ranger Helmets (NCR, Desert, Riot, Advanced Riot, Elite Riot) have a neat glowing effect.

Files to install:
- **Simple Glowing Ranger Visors (No Neck Covers)** (Main files)

[**Snowglobe Tweaks Fix**](https://www.nexusmods.com/newvegas/mods/67466)  
Makes it so you need to first discover the snow globe display in the Lucky 38 Presidential Suite then ask Jane in the Penthouse about the snow globe collection in order to sell them. DLCs snow globes now need to be sold to Jane, instead of automatically rewarding the player. If Mr. House is dead, you can place the snow globes on the display yourself (you won't get the caps reward, however).
</details>

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

[**Consistent Pip-Boy Icons - Mod Patches**](https://www.nexusmods.com/newvegas/mods/65046)  
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
- **Mojave Raiders - No NPC Throwing Weapon Consumption** (Optional files)

[**No NPC Throwing Weapon Consumption - WMIM Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/No%20NPC%20Throwing%20Weapon%20Consumption%20-%20WMIM%20Patch.7z)  
Compatibility patch for Weapon Mesh Improvement Mod.

[**JSawyer Ultimate - Mojave Raiders Patch**](https://www.nexusmods.com/newvegas/mods/62933)  
Compatibility patch for JSawyer Ultimate.

[**Khans Friendly to Fiends**](https://www.nexusmods.com/newvegas/mods/72381)  
Makes Fiends passive to Great Khans and the player when wearing Great Khan outfits. The cut dialogues for the fiend leaders have also been reactivated.

Files to install:
- **Khans Friendly to Fiends** (Main files)
- **Mojave Raiders Patch** (Main files)

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

[**Character Expansions Revised Patches**](https://www.nexusmods.com/newvegas/mods/75268/?)  
Merged compatibility patch for Yukichigai Unofficial Patch, JSawyer Ultimate, Uncut Wasteland and Extra Collection, Mojave Raiders, and Khans Friendly to Fiends.
- BAIN options to install:
  - [X] 00 AIO Complete

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

[**Natural Eyes**](https://www.nexusmods.com/newvegas/mods/62811)  
Improves eye textures.

Files to install:
- **00 - Natural Eyes - Shadow** (Main files)

[**Vanilla Hair - No Shine**](https://www.nexusmods.com/newvegas/mods/50285)  
Removes shine from vanilla hairs.

[**No More Pip-Boy Glove**](https://www.nexusmods.com/newvegas/mods/69258)  
Removes the completely useless and ugly Pip-Boy glove from the player.

[**Pip-Boy 2000 Mk VI**](https://www.nexusmods.com/newvegas/mods/65980)  
Pip-Boy replacer with custom scratch-made meshes, textures and working clock like in Fallout 76.

Files to install:
- **Pip-Boy 2000 Mk VI replacer version** (Main files)
- **Working date and clock for replacer** (Optional files)

[**Pip-Boy 2000 Mk VI Working Buttons**](https://www.nexusmods.com/newvegas/mods/75268)  
Makes the Pip-Boy 2000 Mk VI's buttons functional. Mod by **AleksMarch**.

[**Pip-Boy 2000 MK VI (Wasteland Edition) Retexture**](https://www.nexusmods.com/newvegas/mods/65999)  
Gives the Pip-Boy 2000 Mk VI a grittier texture.

[**NPC Arm Mounted Pip-Boy 2000 Mk VI**](https://www.nexusmods.com/newvegas/mods/75268)  
Makes NPCs wear the new Pip-Boy 2000 Mk VI.

### Environment

[**A Little More Lamplight**](https://www.nexusmods.com/newvegas/mods/69226)  
Enhances the shoddy work on the vanilla functional streetlamps and lights of Outer Vegas, Camp McCarran, Camp Golf, and the NCRCF. 

[**Strip Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/73324)  
Adds lights to the Strip where lights existed but where not producing light. Also fixes a number of vanilla bugs via editing the environment and certain meshes.

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
- **Desert Natural Weathers 3.3.5** (Main files)
- **Restore fake interior godrays.** (Optional files)

[**Desert Natural Weathers Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Desert%20Natural%20Weathers%20Custom%20INI.7z)  
Disables interior tint fix and increases sunlight during the day.

[**Desert Natural Weathers - Zion Ambient Music**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Desert%20Natural%20Weathers%20-%20Zion%20Ambient%20Music.7z)  
Adds vanilla ambient music to the Zion worldspace.

[**Accurate NASA Stars**](https://www.nexusmods.com/newvegas/mods/75522)  
Star texture and mesh using NASA satellite images to create a real-world accurate starfield.

Files to install:
- **Accurate Stars 4k** (Main files)

[**Night Sky Tweaks**](https://www.nexusmods.com/newvegas/mods/73529)  
Fixes the bright night sky horizons.

Files to install:
- **Night Sky Tweaks (Script Runner)** (Main files)

[**HD Mist**](https://www.nexusmods.com/newvegas/mods/58955)  
High resolution retexture for mist.

Files to install:
- **HD Mist 2K** (Main files)

[**HQ Dust Storm FX**](https://www.nexusmods.com/newvegas/mods/53863)  
High resolution retexture for dust storms.

## BODY REPLACERS

> ℹ️ This section uses modest (i.e. non-nude) outfits.

[**Improved Vanilla Male Body**](https://www.nexusmods.com/newvegas/mods/70160)  
High poly, improved and seamless version of the male body. Compatible with vanilla outfits.

Files to install:
- **01 - Improved Male Body - FOMOD Installer** (Main files)
  - FOMOD options to install:
    - [X] 00 - Main
    - [X] 05 - Underwear Options
      - [X] 08 - Legacy Underwear
- **00 - Outfit Conversions - Hotfix** (Update files)

[**TYPE4 - Body and Armors**](https://www.nexusmods.com/newvegas/mods/66903)  
Female body replacer featuring no neckseams and much improved arms and upperbody. Complete set of armor and clothing with support for all DLCs.
- Hide the **meshes\characters\ _male\locomotion** folder.
- Hide the **meshes\pipboy3000** folder.

> ℹ️ This fixes compatibility issues with animation mods and mods that replace the Pip-Boy model.

[**TYPE4 - Armor Fixes**](https://www.nexusmods.com/newvegas/mods/73885)  
Fixes a glitch that caused light reflections to flicker with TYPE4 armors.
  
Files to install:
- **T4 Armor Mesh Fixes (Vanilla)** (Main files)

[**TYPE4 Patches**](https://www.nexusmods.com/newvegas/mods/74893)  
Patches **TYPE4** for a variety of mods.
- BAIN options to install:
  - [X] 00 YUP Patch
  - [X] 01 Vanilla Radiation Suits
  - [X] 02 JSUE Patch
  - [X] 03 PA Gloves Patch
  - [X] 04 Eyelashes FNV Patch
  - [X] 05 Red Vault 19 Jumpsuits Patch

[**TYPE4 Misc Gameplay Merge Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/TYPE4%20Misc%20Gameplay%20Merge%20Patch.7z)  
Omits the armor fixes related to Legion armors in Misc Gameplay Merge's script to prevent it from overriding TYPE4's Legion armor meshes.

[**Body and Face Textures Workshop**](https://www.nexusmods.com/newvegas/mods/55174)  
High resolution textures for Type-based female bodies.

Files to install:
- **00 - Default Version - CORE** (Main files)
- **00b - Raider Textures** (Main files)
- **00 - Dead Money DLC - Christine face** (Update files)
- **01 - Old Female** (Update files)  
- **01 - Detailed Face Normalmap** (Optional files)  
- **03 - Body Hairy Clean** (Optional files)  
- **05 - Face Vanilla Feel** (Optional files)  

> ⚠️ The following are outfit replacers to address some rather skimpy outfits in **TYPE4**. As such, they are entirely optional.

[**More Modest TYPE4 Body and Armor**](https://www.nexusmods.com/newvegas/mods/69642)  
Less skimpy outfits for many TYPE4 outfits.
- Hide **jumpsuit fix.esp**

[**More Modest TYPE4 Fixes**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/More%20Modest%20T4%20Fixes.7z)  
Fixes mismatching textures on a number of More Modest TYPE4 outfits.

[**TYPE4 Alternative Outfits**](https://www.nexusmods.com/newvegas/mods/66993)  
Less skimpy Wasteland Wanderer and Raider outfits.
  
Files to install:
- **Raider armors** (Main files)
- **Wasteland Wanderer** (Main files)

[**T6M Prostitute Outfits and Combat Armor**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/T6M%20Prostitute%20Outfits%20and%20Combat%20Armor.7z)  
Less skimpy Prostitute outfits and less goofy Reinforced Combat Armors.
- BAIN options to install:
  - [X] 00 Prostitute Outfits
  - [X] 01 Combat Armor

## LOD

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

### Generated LOD

[**I Heart New Vegas LOD**](https://drive.google.com/file/d/1fT7k67vv-K6QLhiJ9UrIMheJXuBewwNT/view?usp=sharing)  
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

03-13-2022
- Merged in Addendum guide for simplicity.
- Updated **OneTweak** installation instructions (NVSE Plugins).

03-10-2022
- Re-added **Khans Friendly to Fiends** (Content).
- Updated **Character Expansions Revised Patches** (Visuals) installation instructions.

03-09-2022
- Updated **Desert Natural Weathers** installation instructions (Visuals).
	
03-05-2022
- Updated **Desert Natural Weathers** installation instructions (Visuals).
- Removed **HD Moon 2K** (Visuals). The latest update of **Desert Natural Weathers** finally fixes the white outline bug on the Moon, so it is no longer needed.

03-03-2022
- Updated **Desert Natural Weathers** installation instructions (Visuals).
- Updated **RAD** MCM config instructions (**MCM Config**).

03-02-2022
- Updated **Desert Natural Weathers** installation instructions (Visuals).
- Re-added **B42 Melee Bash** (Gameplay).
- Added **Accurate NASA Stars** (Visuals).
- Removed **RAD - Radiation (is) Actually Dangerous**. The **Overhaul** completely replaces this mod now.
</details>

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)
