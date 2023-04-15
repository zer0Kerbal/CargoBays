---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.99.1
Cargo Bays (DCB)
created: 17 Feb 2022
updated: 13 Apr 2023

TEMPLATE: ManualInstallation.md v1.1.9.0
created: 01 Feb 2022
updated: 27 Mar 2023

based upon work by Lisias -->

# [Cargo Bays (DCB)][mod]

[Home](./index.md)

A payload parts add-on that adds round stock-a-like cargo-bays of various stack sizes and lengths with fold-flat door design.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `DaMichel` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/DaMichel/CargoBays`
* Extract the package's `DaMichel` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/DaMichel` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/CargoBays`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/DaMichel/CargoBays`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/DaMichel/CargoBays`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [DaMichel]
      + [DaMichelLtd][DML]
        + [Agency]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        ...
      + [CargoBays][DCB]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CargoBays.version
        * CC-BY-SA-4.0.txt
        * changelog.md
        * ManualInstallation.htm
        * readme.htm
      ...
    ...
  * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [DaMichel Ltd (DML)][DML]

[DML]: https://www.curseforge.com/kerbal/ksp-mods/damichelltd "DaMichel Ltd (DML)"
[mod]: https://www.curseforge.com/kerbal/ksp-mods/CargoBays "Cargo Bays (DCB)"

THIS FILE: CC BY-ND 4.0 by zer0Kerbal