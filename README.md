# NOLF Retro Widescreen Patch

A free widescreen patch for **No One Lives Forever** (NOLF 1, version 1.003)
that runs on legacy systems such as **Windows 98 SE and Windows XP**, and also
on modern Windows. It adds widescreen resolutions such as 1920x1080, a scaled
menu and HUD, and a few quality-of-life features. It is built with Visual C++
2005, so no modern runtime is needed.

**Creator:** Alexander Schmidt, <alex-286@web.de>

*This add-on is not made by or supported by Monolith Productions, or any of its
affiliates and subsidiaries.*

> **Status:** work in progress, no release yet. Binary builds will be published
> on the [Releases](../../releases) page.

## About this repository

This repository only hosts the **binary releases** and the user documentation
of the patch. The source code is not published here: it is derived from the
NOLF Source Code v1.003, whose license (EULA) does not allow redistributing the
source. See [LICENSE.md](LICENSE.md).

## Requirements

- A licensed copy of No One Lives Forever, patched to version 1.003. The patch
  contains no game assets and does not replace the game.
- Windows 98 SE, Windows XP, or newer (tested on Windows 98 SE, XP and 10/11).

## Installation

The patch is a single `.rez` file. The original `NOLF.REZ` and `NOLF2.REZ` are
never modified, so you can remove the patch at any time.

Detailed installation instructions will be added with the first release.

## Features

- Widescreen resolutions (for example 1920x1080) selectable under
  **Options → Display**
- Centered, scaled menus; scaled HUD, crosshairs and loading screens
- Cinematics in widescreen, or with black side bars to keep 4:3
- Black side bars around the sniper scope
- New **Interface** options: HUD scale and cinematic aspect ratio
- 60 fps framerate cap and optional FPS counter
- Developer console (**Shift+Esc**)
- Right-click closes popup text; the last used ammo type is remembered per weapon
- Small fixes (mission summary **Continue** button, Weapon Controls crash)

A full feature documentation will follow with the first release.

## Credits

Several features follow the behavior of the
[NOLF Modernizer](https://github.com/haekb/nolf1-modernizer) by its authors,
re-implemented for Visual C++ 2005 and Windows 98. NOLF and the NOLF logo are
trademarks of their respective owners (Monolith Productions / Warner Bros.).

## Legal

This patch is a free *Variation* in the sense of the *NOLF Source Code v1.003
EULA*. It is and stays free of charge and works only with a full copy of NOLF.
See [LICENSE.md](LICENSE.md) for the terms of use and redistribution.
