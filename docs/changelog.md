---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
# layout: bare
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---

# Changelog
  
| modName    | DaMichel's CargoBays (DCB)                                        |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-3.0                                                      |
| author     | DaMichel, Bezzier and zer0Kerbal                                  |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/207351-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/CargoBays)              |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/CargoBays)            |
| spacedock  | (https://spacedock.info/mod/2339)                                 |
| ckan       | DMTanks-CargoBays                                                 |

## Version 2.1.99.0-prerelease - `<Split'n'Polish: CargoBays>`

* 09 May 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Add

* Dependency
  * DaMichel Ltd (agency, flag, common files)

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts
* updates #28 - Asset Updates

### Localization

* Update
  * <us-en.cfg>
* Add
  * Localization/
    * [readme.md]
    * [quickstart.md]
* updates #7 - American English <us-en.cfg>
* updates #6 - Localization - Master

### Status

* Issues
  * closes #2 - Cargo Bays (DCB) 1.1.99.0-prerelease `<Split'n'Polish: CargoBays>`
  * closes #3 - 1.1.99.0 Verify Legal Mumbo Jumbo
  * closes #4 - 1.1.99.0 Update Documentation
  * closes #5 - 1.1.99.0 Social Media

---

## Version 1.1.0.1-prerelease - `<Spit'n'Polish>`

* 2020-02-24
* Released for Kerbal Space Program 1.8.1

* thank you to BenjaminCronin
  * for pointed out decorative right brace in changelogs
  * wite-out applied
* Also dangling VERSION
  * superglue applied.
* updated product hero shots
* created SpaceDock header

### NEW

* ***Introducing***
  * 3.75m models
    * 1.5m, 3m, 6m lengths
    * [TechRequired] = largeVolumeContainment

### Localization

* Update
  * <us-en.cfg>
  * url's updated and updated to 2.5m
  * corrected several small typo's in the localization dictionary
* Add
  * Localization/
    * [readme.md]
    * [quickstart.md]
* updates #7 - American English <us-en.cfg>
* updates #6 - Localization - Master

### Add

* [ghostparts.cfg]
  * introduced
  * original three parts have had their internal part names changed
  * this file should prevent any Kraken attacks.
* automatic GitHub action:
  * Validate AVC .version files
  * corresponding shield to Readme's
  * Thank you @DasSkelett, and @HebaruSan

### Moved

* FSAnimateGeneric
  * into patch

### Updated

* integrated TweakScale patches
  * if you don't have TweakScale installed, won't show up and won't hurt anything
* corrected
  * integrated tweakscale scale module
    * reduced scales available
  * 2.5m parts
    * [techRequired] = largeVolumeContainment, specializedConstruction, largeVolumeContainment
  * 3.75m parts
    * [techRequired] = metaMaterials, largeVolumeContainment, metaMaterials
* new KERBALCHANGELOG formating
  * hopefully I got it right this time :o

### Status

* Issues
  * closes #24 - Previous Releases
  * closes #26 - 1.1.0.1-prerelease
  * updates #28 - Asset Updates

---

## Version 1.1.0.0-adoption - `<Fresh Coat of Paint: CargoBays>`

* 2020-02-17
* Released for Kerbal Space Program 1.8.1

### Adopted by zer0Kerbal

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts
* updates #28 - Asset Updates

### Localization

* Add
  * Localization/
    * [readme.md]
    * [quickstart.md]
    * <en-us.cfg>
  * translations welcomed through GitHub Push Request
  * updates #6 - Localization - Master
  * closes #7 - American English <us-en.cfg>
  * closes #32 - Part Localization

* updated license to CC BY-SA 4.0
* file structure and modernization
* modernized part.cfg
* many little changes to patches/parts.

### Created

* Kerbal Changelog
* Readme
* github repo
* SpaceDock entry
* CKAN entry
* Curseforge entry
* Forum post
* .json
* Forum thread

### Status

* Issues
  * updates #24 - Previous Releases
  * closes #25 - 1.1.0.0-adoption
  * updates #28 - Asset Updates

---

## Version - 1.0.1.0-release - Cost Increase

* Nov 03, 2017
* Kerbal Space Progrtam 1.3.1

* This release increases the cost of the AeroRTG by 50%, to offset its aerodynamic nature as compared to the original RTG.
* The part continues to function, so this brings it up to date for 1.3.1.

---

## Version - 1.0.0.0-release - colorcurves update

* May 10, 2016
* Kerbal Space Progrtam 1.0.5
* adopted by Bezzier (Color Curves)

### This brings these parts up to date by

Correcting typos

* Correcting typos
* Rebalancing to stock values
  * costs
  * masses
  * temperatures
  * drag
* Adding Core Heat
* [techRequired] to experimentalElectrics

---

## Version - 0.0.0.0-release - Original by DaMichel

* unknown version number
* Apr 18-2014
* First release

---

<!-- This File CC BY-ND 4.0 by zer0Kerbal -->