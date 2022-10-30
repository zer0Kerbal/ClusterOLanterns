---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Cluster O'Lanterns (COL)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Cluster O'Lanterns (COL)

[Home](./index.md)

A kitbash of Porkjet's Jack O'Lantern and BahamutoD's Cluster Bomb to multiply your enjoyment x42.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `nli2work` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/nli2work/ClusterOLanterns`
* Extract the package's `nli2work/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/nli2work` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/nli2work/ClusterOLanterns`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/nli2work/ClusterOLanterns`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/nli2work/ClusterOLanterns`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [nli2work]
      + [ClusterOLanterns]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        + [Plugins]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-SA-4.0.txt
        * changelog.md
          ManualInstallation.htm
        * readme.htm
        * ClusterOLanterns.version
        ...
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [Jack-O'Lantern (JACK)][JACK] (so the Cluster O'Lanterns look good)
* [BDArmory][bda] (so things go boom)
* [NohArk's Pick'n'Pull (PNP)][PNP] (Agency)

[JACK]: https://forum.kerbalspaceprogram.com/index.php?/topic/189466-*/ "Jack-O'Lantern (JACK)"
[PNP]: https://forum.kerbalspaceprogram.com/index.php?/topic/209965-*/ "NohArk's Pick'n'Pull (PNP)"
[bda]: https://forum.kerbalspaceprogram.com/index.php?/topic/178156-*/ "BDArmory"