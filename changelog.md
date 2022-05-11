# Changelog  
  
| modName    | DaMichel's Cargo Bays (DCB)                                         |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-3.0                                                      |
| author     | DaMichel, Bezzier and zer0Kerbal                                  |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/208131-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/Fuselage)               |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/Fuselage)             |
| spacedock  | (https://spacedock.info/mod/2340)                                 |
| ckan       | DMTanks-Fuselage                                                  |

## Version 2.1.99.0-prerelease - `<Split'n'Polish: AeroRadial>`

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
* closes #36 - Asset Updates

### Localization

* Update
  * <us-en.cfg>
* Add
  * Localization/
    * [readme.md]
    * [quickstart.md]
* updates #6 - American English <us-en.cfg>
* updates #5 - Localization - Master

### Status

* Issues
  * closes #1 - Cargo Bays (DCB) 1.1.99.0-prerelease `<Split'n'Polish: AeroRadial>`
  * closes #2 - 1.1.99.0 Verify Legal Mumbo Jumbo
  * closes #3 - 1.1.99.0 Update Documentation
  * closes #4 - 1.1.99.0 Social Media

---

## Version 1.1.0.2 - for KSP 1.12.3 [22-Mar-2022]

* #4 - [ImgBot] Optimize images - contributed by imgbot[bot]
* #6 - [ImgBot] Optimize images

---

### Version 1.1.0.1-prerelease - `<Spit'n'Polish>`

* 2020-02-24
* Released for Kerbal Space Program 1.8.1

* thank you to BenjaminCronin
  * for pointed out decorative right brace in changelogs
  * wite-out applied
* Also dangling VERSION
  * superglue applied.
* added
  * attach node to the back (rear) of the parts
* updated
  * the DM-RFC texture.
* RTG
  * adjusted
    * [cost] from 34950 to 20000
    * [entryCost] from 58000 to 50000
    * [TechRequired] from experimentalElectrics to largeElectrics
* removed
  * tags.cfg (redundant patch since tags now in localization)
* updated product hero shots
* created SpaceDock header

### Status

* Issues
  * closes #33 - Previous Releases
  * closes #35 - 1.1.0.1-prerelease
  * updates #36 - Asset Updates

---

### Version 1.1.0.0-adoption - `<Fresh Coat of Paint: AeroRadial>`

* 2020-02-17
* Released for Kerbal Space Program 1.8.1

* adopted by zer0Kerbal
* for Kerbal Space Program (KSP) 1.9 (might work for earlier)

### Localization

* Added
  * <en-us.cfg>
  * translations welcomed through GitHub Push Request
  * updates #5 - Localization - Master
  * closes #7 - American English <us-en.cfg>
  * closes #32 - Part Localization

* updated license to CC BY-SA 4.0
* file structure and modernization
* modernized part.cfg
* many little changes to patches/parts.

### Added

* New Part
  * DM-RFC
  * Radial Fuel Cell
  * air breathing, liquid fuel powered generator
  * producing 1.5 EC/s
  * created DM-RFC texture
* Compatibility patch
  * On-Demand Fuel Cells (ODFC)

### Created

* Kerbal Changelog
* Readme
* github repo
* SpaceDock entry
* CKAN entry
* Curseforge entry
* Forum post
* .json

### Status

* Issues
  * updates #33 - Previous Releases
  * closes #34 - 1.1.0.0-adoption

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

<!-- This File CC BY-ND 4.0 by zer0Kerbal -->