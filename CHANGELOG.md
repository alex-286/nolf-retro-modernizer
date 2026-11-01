# Changelog

## 0.9 - first release

First public release of the NOLF Retro Widescreen Patch for No One Lives
Forever 1 (version 1.003), for Windows 98 SE, Windows XP and newer.

### Added

- Widescreen resolutions such as 1920x1080 under **Options → Display**.
- Centered, scaled menus with shaded side areas; scaled Back/Continue arrows
  with matching mouse hit-testing.
- Scaled HUD, crosshairs and loading screens that refresh after a resolution
  change.
- Widescreen cinematics, with an option to keep 4:3 with black side bars.
- Black side bars around the sniper scope, also when zooming with the
  sunglasses.
- New **Interface** options folder with a HUD scale slider (`UIScale`) and a
  cinematic aspect ratio toggle (`RestrictCinematicsTo4x3`).
- 60 fps framerate cap (`FramerateLock`, default on) and an optional FPS
  counter (`ShowFramerate`).
- Developer console, opened with **Shift+Esc** or a key bound under
  *Customize Controls → Toggle Console*, with selectable backdrop
  (`ConsoleBackdrop`).
- Popup text (intelligence items) can be closed with the right mouse button.
- The last used ammo type is remembered per weapon.
- Opening screen shows the patch name, version, creator and the non-affiliation
  notice.
- `RetroDebug.log` in the game's working directory for bug reports.

### Fixed

- 3D weapon and item models were missing in the widescreen folders.
- The mission summary screen did not always show the **Continue** button.
- The Back arrow on the **Weapon Controls** screen crashed the game.

### Known limitations

- Client-side only: server-side Modernizer features are not included.
- The developer console is disabled in multiplayer and cannot run
  server-side console programs.
- The remembered ammo types are reset when the game is restarted.
