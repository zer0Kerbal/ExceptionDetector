---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.0.0
Exception Detector (EXCD)
created: 01 Apr 2022
updated: 29 Apr 2023

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->

# [Exception Detector (EXCD) (ABBV)][mod]

[Home](./index.md)

This add-on creates a log file by hooking into the logger callbacks in Unity and is able to extract more value from the available information. Assists in finding issues that you might not even be aware of and might be able to find any pesky add-on(s) that might be causing your issues. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `godarklight` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/godarklight/ExceptionDetector`
* Extract the package's `godarklight/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/godarklight` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/godarklight/ExceptionDetector`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/godarklight/ExceptionDetector`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/godarklight/ExceptionDetector`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [godarklight]
      + [ExceptionDetector]
        ...
      + [Icons]
        edu
        edu_large
        edu_small
        ...
      + [Localization]
        ...
      + [Plugins]
          ExceptionDetector.dll
          Settings.cfg
        [Log]
          ed.log
      * #.#.#.#.htm
      * Attributions.htm
      * BSD-2-Clause.txt
      * changelog.md
      * ExceptionDetector.version
      * ManualInstallation.htm
      * readme.htm
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/ExceptionDetector "Exception Detector (EXCD)"
