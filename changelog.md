# Changelog
  
| modName    | DaMichel's CargoBays (DCB)                                        |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | DaMichel, Bezzier and zer0Kerbal                                  |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/207351-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/CargoBays)              |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/CargoBays)            |
| spacedock  | (https://spacedock.info/mod/2339)                                 |
| ckan       | DMTanks-CargoBays                                                 |

## CargoBays (DCB) 1.1.99.0-prerelease `<Split'n'Polish: CargoBays>`

* 27 Jul 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

***DELETE EXISTING INSTALLATION THEN RE-INSTALL***

### Summary 1.1.99.0

* Initial Prerelease
* New Dependency
  * [DaMichel Ltd (agency, flag, common files)(DM/L)][DML]
* All thumbs should now be available.
* Can now search for 'DCB' or `DM` in the editor search bar to find all CargoBay parts.
* ***NEW*** Parts!
  * 1.25m in three lengths: 0.5m, 1m, and 2m
  * 1.875m in three lengths: 0.75m, 1.5m, and 3m
  * 5.00m in three lengths: 2m, 4m, and 8m

[DML]: https://forum.kerbalspaceprogram.com/index.php?/topic/208107-*/ "DaMichel Ltd (DM/L)"

### License

* Updated License: CC-BY-SA-4.0
  * was: CC-BY-SA-3.0
* closes #34 - Update License

* ### Add

* Initial Prerelease
* Dependency
  * DaMichel Ltd (agency, flag, common files)

### Compatibility

* [FSAnimate.cfg] v1.0.1.0
  * [FSanimateGeneric]
    * Localization
      * [startEventGUIName] = #autoLOC_502058 // Open Doors
      * [endEventGUIName] = #autoLOC_502058 // Open Doors
      * [actionGUIName] = #autoLOC_502077 // Toggle Bay Doors

### Config

* Update
  * [ghostparts.cfg] v1.3.0.0
    * moved from Compatibility/ to Config/
    * Ghosts:
      * v1.1.0.1
        * 2.5m --> dm-round-cargobay
      * v1.1.99.0
        * 2.5m --> dm-round-cargobay250
        * 3.75m --> dm-round-cargobay375
    * Will be deactivated / removed in future releases.
* Add
  * [CargoBays.cfg] v1.0.0.0
    * updates parts with localization strings
    * adds three localizations strings together

### Parts

* ***NEW*** Parts!
  * 1.25m in three lengths: 0.5m, 1m, and 2m
  * 1.875m in three lengths: 0.75m, 1.5m, and 3m
  * 5.00m in three lengths: 2m, 4m, and 8m
* Add
  * header
  * [DRAG_CUBE]
  * @thumbs
  * [ModuleCargoPart] = packedVolume = -1
  * [ModuleConductionMultiplier]
* Update
  * [manufacturer] = #DML-Agency-titl
  * [tags] now #autoLOC_500899
  * [dcb-???-?] v1.0.1.0
  * lint and reorganize
* closes #38 - Update Parts
* closes #39 - Add Parts: 1.25 (size1) (I)
* closes #40 - Add Parts: 1.875 (size1p6) (IS)
* closes #41 - Add Parts: 1.25 (size4) (IV)

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
  * clean and update all localizations
    * <en-us.cfg> v1.1.0.0
    * <es-es.cfg> v1.1.0.0
    * <fr-fr.cfg> v1.1.0.0
    * <it-it.cfg> v1.1.0.0
  * [readme.md] v2.1.2.0
  * [quickstart.md] v1.0.1.1
  * Parts
    * [ModuleToggleCrossfeed]
      * {toggleText} = #autoLOC_236032
      * {enableText} = #autoLOC_236028
      * {disableText} = #autoLOC_236030
    * [ModuleAnimateGeneric]
      * {startEventGUIName} = #autoLOC_502069 //#autoLOC_502069 = Open
      * {endEventGUIName} = #autoLOC_502051 //#autoLOC_502051 = Close
      * {actionGUIName} = #autoLOC_502077 //#autoLOC_502077 = Toggle Bay Doors
* updates #6 - Localization - Master
* closes #7 - English <en-us.cfg>
* closes #10 - Spanish (Español) <es-es.cfg>
* closes #11 - French (Français) <fr-fr.cfg>
* closes #12 - Italian (Italiano) <it-it.cfg>
* closes #35 - Add localized tags to parts
* closes #23 - Part Localization

### docs/

* Add/Update
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Part-Catalog.md] v1.1.4.0
  * [Why.md] v1.1.0.0
  * [_config.yml]
  * [changelog.md]
    * add header for docs/
* closes #36 - docs/

### Documentation

* Update
  * [Readme.md] v1.6.9.2
  * [ReleaseNotes.md] v1.3.1.1
  * [CargoBays.version]
    * remove
      * [KSP_VERSION_MAX]
* closes #37 - Update Documentation

### Status

* Issues
  * closes #2 - CargoBays (DCB) 1.1.99.0-prerelease `<Split'n'Polish: CargoBays>`
  * closes #3 - 1.1.99.0 Verify Legal Mumbo Jumbo
  * closes #4 - 1.1.99.0 Update Documentation
  * closes #5 - 1.1.99.0 Update Social Media

---

## Version 1.1.0.1-prerelease - `<Spit'n'Polish>`

* 2020-02-24
* Released for Kerbal Space Program 1.9.1

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
  * <es-es.cfg>
    * translate.google.com
  * <fr-fr.cfg>
    * translate.google.com
  * <it-it.cfg>
    * translate.google.com
  * Localization/
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.0
* updates #7 - American English <us-en.cfg>
* updates #6 - Localization - Master
* closes #10 - Spanish (Español) <es-es.cfg>
* closes #11 - French (Français) <fr-fr.cfg>
* closes #12 - Italian (Italiano) <it-it.cfg>

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
* closes #28 - Asset Updates

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

<!-- This File CC BY-ND 4.0 by zer0Kerbal -->