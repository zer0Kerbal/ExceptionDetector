---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.1.0
ExceptionDetector (ED)
created: 01 Apr 2019
updated: 01 Apr 2022 -->

<!-- based upon work by Lisias -->

# ExceptionDetector (ED)

An add-on that adds a safety fence around the Kerbal Space Center, for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/ExceptionDetector`
* Extract the package's `ExceptionDetector/` folder into your KSP's as follows:
  * `<PACKAGE>/SimpleConstruction` --> `<KSP_ROOT>/GameData/ExceptionDetector`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/ExceptionDetector`
* Extract the package's `GameData/ExceptionDetector` folder into your KSP's as follows:
  * `<PACKAGE>/GameData/ExceptionDetector` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```
<KSP_ROOT>
  [GameData]
    [godarklight]
      [ExceptionDetector]
        [Plugins]
          [Log]
          ExceptionDetector.dll
          Settings.cfg
          ...
        1.3.0.0.htm
        changelog.md
        ExceptionDetector.version
        SimpleBSD.txt
        readme.htm
      ...
  KSP.log
  ...
```

### Dependencies

* none
