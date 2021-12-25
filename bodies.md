[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md)  
[<< Back to Main](https://github.com/Sigourn/iheartnewvegas/blob/main/main.md)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# BODIES ADD-ON

## Disclaimer

The guide presented here assumes you have already followed all instructions found in **Left My Heart In New Vegas**. Please abstain from using this guide until you've correctly set up Fallout: New Vegas.

This document will guide you through the installation of face and hair textures, as well as the **TYPE 4** and **Improved Vanilla Male Body** body replaceres. Do note, however, that this guide is intended for my personal use only, and you shouldn't expect anything on the way of support if you decide to go through with it.

## Preliminary steps

The following mods should be reinstalled if you plan on using **TYPE 4**.

[**Dirty Pre-War Businesswear Fix**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Dirty%20Pre-War%20Businesswear%20Fix%201.0.7z)  
Fixes the Dirty Pre-War Businesswear having the incorrect texture.
- BAIN options to install:
  - [X] 00 Core
  - [X] 02 TYPE 4

[**Honest Hearts Gecko Leathers Improved ESP Replacer and JSUE Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Honest%20Hearts%20Gecko%20Leathers%20Improved%20ESP%20Replacer%20and%20JSUE%20Patch.7z). Forwards **YUP** fixes and adds a patch for **JSawyer Ultimate Edition**.
- BAIN options to install:
  - [X] 00 ESP Replacer Compatibility Version
  - [X] 01 JSUE Patch Compatibility Version

The following mod should be edited if you plan on using **TYPE 4**.

[**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)  
Compilation of small gameplay mods by various authors, all fully fixed, optimized, and updated by Qolore7.
- Open **NVSE\plugins\scripts\gr_MiscEquipmentChanges.txt** using a text editor, and delete the following lines:
  - SetBipedModelPathAlt ArmorNVCLExplorer 1 "FIXforLegionArmors\ExplorerFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLRecruit 1 "FIXforLegionArmors\RecruitFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLPrime 1 "FIXforLegionArmors\PrimeFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLVeteran 1 "FIXforLegionArmors\VeteranFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLVexillarius 1 "FIXforLegionArmors\VexillariusFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLPraetorian 1 "FIXforLegionArmors\PraetorianFemale.nif"
  - SetBipedModelPathAlt ArmorNVCLCenturion 1 "FIXforLegionArmors\CenturionFemale.nif"
  - SetBipedModelPathAlt ArmorNVCaesar 1 "FIXforLegionArmors\CaesarFemale.nif"

> This will revert the female model tweaks in favor of **TYPE 4**'s adjusted models.

## Face and hair textures add-on

[**Eyelashes New Vegas**](https://www.nexusmods.com/newvegas/mods/34790)  
Adds animated eyelashes to NPCs and the player character.
- Install the **tkEyelashesFNV** main file.
- Hide both plugins.

Additional files to install:
- [**Eyelashes New Vegas ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Eyelashes%20New%20Vegas%20ESP%20Replacer.7z). Fixed version of the main plugin.

[**HD Teeth and Natural Eyelashes and Eyebrows**](https://www.nexusmods.com/newvegas/mods/53695)  
Improves teeth, eyelashes, and eyebrow textures.
- Install all three main files.

[**Natural Eyes**](https://www.nexusmods.com/newvegas/mods/62811)  
Improves eye textures.
- Install the **00 - Natural Eyes - Shadow** main file.

[**Vanilla Hair - No Shine**](https://www.nexusmods.com/newvegas/mods/50285)  
Removes shine from vanilla hairs.

## Body replacers add-on

[**TYPE4 - Body and Armors**](https://www.nexusmods.com/newvegas/mods/66903)  
Female body replacer featuring no neckseams and much improved arms and upperbody. Complete set of armor and clothing with support for all DLCs.
- Delete the following records in **FNVEdit**.
  - ArmorRadiationSuit
  - ArmorRadiationSuitAdvanced
  - MS03EnvironmentSuit
  - CSArmorRadiationSuit
- Hide the **meshes\armor\enclavescientist** folder.
- Hide the **meshes\characters\ _male\locomotion** folder.
- Hide the **meshes\pipboy3000** folder.

> This removes the changes to the Radiation Suit and related outfits, and fixes compatibility issues with **Pip-Boy 2500 Mk VI** and animation mods.

Additional files to install:
- [**TYPE 4 Armor Fixes**](https://www.nexusmods.com/newvegas/mods/73885). Fixes a glitch that caused light reflections to flicker with TYPE 4 vanilla armors.
  - Install the **T4 Armor Mesh Fixes (Vanilla)** Main file.
  - Hide the **meshes\armor\enclavescientist** folder.
- [**TYPE 4 Patches**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/TYPE%204%20Patches%20(Dec%2015th).7z). Patches **TYPE 4** for compatibility with **Yukichigai Unofficial Patch**, **JSawyer Ultimate Edition**, **Power Armor Gloves**, and **Eyelashes New Vegas**.

[**Mannequin Races**](https://www.nexusmods.com/newvegas/mods/62785)  
Adds seven new custom races to Fallout New Vegas.

Additional files to install:
- **00 - EGM files for hairs** (under Optional files).

[**Mannequin Races - TYPE4**](https://www.nexusmods.com/newvegas/mods/68994)  
TYPE4 textures and meshes for Mannequin Races.

Additional files to install:
- **01 - TYPE4 Underwear** (under Optional files).

[**Body and Face Textures Workshop**](https://www.nexusmods.com/newvegas/mods/55174)  
High resolution textures for Type-based female bodies.
- Install the **00 - Default Version - CORE** and **00b - Raider Textures** main files.

Additional files to install:
- **00 - Dead Money DLC - Christine face** (under Update files).
- **01 - Old Female** (under Update files).
- **01 - Detailed Face Normalmap** (under Optional files).
- **03 - Body Hairy Clean** (under Optional files).
- **05 - Face Vanilla Feel** (under Optional files).

[**T6M Neck Adjusted Outfit Replacers**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/T6M%20Neck%20Adjusted%20Outfit%20Replacers.7z)  
Outfit replacers for Combat Armor (including variations), Prostitute Outfits, and Raider Outfits.

[**Improved Vanilla Male Body - Seamless - 4k**](https://www.nexusmods.com/newvegas/mods/70160)  
High poly, improved and seamless version of the male body. Compatible with vanilla outfits.
- Install the **01 - Improved Male Body - FOMOD Installer** main file.
- FOMOD options to install:
  - [X] 00 - Main
  - [X] 05 - Underwear Options
    - [X] 08 - Legacy Underwear

Additional files to install:
- **00 - Outfit Conversions - Hotfix** (under Update files). Work in progress outfit conversion for most of the openfoot meshes.

## Finishing touches

### Mod order and load order

The mods installed in this guide can be placed at the very end of **Left My ♥ In New Vegas**. **FaceGen Tint Fixes for Character Expansions Revised**, installed in the main guide, should be loaded after **TYPE 4 - Body and Armors** (for simplicity it is listed at the end of the mod order).

<details>
<summary>Mod order</summary>

```
Eyelashes New Vegas
Eyelashes New Vegas ESP Replacer
HD Teeth and Natural Eyelashes and Eyebrows
Vanilla Hair - No Shine
Natural Eyes
TYPE 4 - Body and Armors
TYPE 4 - Armor Fixes
TYPE 4 Patches
Mannequin Races
Mannequin Races - TYPE 4
T6M Neck Adjusted Outfit Replacers
Body and Face Textures Workshop
Improved Vanilla Male Body - Seamless - 4K
00 - Outfit Conversions - Hotfix
FaceGen Tint Fixes for Character Expansions Revised
```
</details>

<details>
<summary>Load order</summary>

```
tkEyelashesFNV.esp
T4-plugin.esp
TYPE 4 YUP Patch.esp
TYPE 4 Dirty Pre-War Businesswear Fix.esp
TYPE 4 JSUE Patch.esp
TYPE 4 Power Armor Gloves Patch.esp
TYPE 4 Eyelashes NV Patch.esp
ImprovedGeckoLeatherArmor.esp
ImprovedGeckoLeatherArmor JSUE Patch.esp
Mannequin Rce.esp
```
</details>

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md)  
[<< Back to Main](https://github.com/Sigourn/iheartnewvegas/blob/main/main.md)