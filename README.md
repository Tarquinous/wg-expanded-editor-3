# Wargroove Expanded Editor 3

An Expanded Editor mod developed on the Official Modpacker.

Inspired and based off the [Expanded Editor](https://www.nexusmods.com/wargroove/mods/28) mod by Unicarn, this one aims to bring the mod tools without reliance upon the unsupported [Unofficial Modpacker](https://www.nexusmods.com/wargroove/mods/1).

The first mod to provide this functionality was the [Unlock Hidden Map Editor Contents](https://www.nexusmods.com/wargroove/mods/11) mod by Ophelia, making this the third mod in a series of editor feature mods!

## Features

* Reveals hidden Map Editor options including:
  * Decorations
  * Commanders
  * Event Conditions
  * Event Actions
  * Music
  * Location highlights
  * Terrain
  * Cutscene backgrounds
  * Cutscene props
  * Cutscene weather
  * Cutscene ambient sounds
  * Cutscene SFX
  * Cutscene VFX
  * Cutscene emotes
  * Cutscene voicelines
  * Placable units
  * Dialogue portraits
* Disables unlock requirements for the three secret commanders
* Disables unlock requirements for music

## How to Use

Load up a custom map you want to work on, open the "Mods" menu and enable the Expanded Editor mod. Click "Save and Reload Map" and all of the features should now be accessible! When you're finished and wish to upload your map, simply disable the mod.

None of your changes to the map will be lost when the mod is removed, as they are all used in vanilla WarGroove!

Unlockable content will return to being locked once the mod is removed if you have not yet unlocked them.

Additionally, I recommend new users check out my [Starter Guide](wiki/starter_guide)!

## Installation

Download the [latest release file](https://github.com/Tarquinous/wg-expanded-editor-3/releases/latest) of the packed mod (not to be confused with the Source Code!). Drop the contained folder into your mods folder at the `%appdata%/chucklefish/wargroove/mods` directory. Reload your game and it should now show up in your "Mods" menu in the map editor.

Mods are currently only available for Windows Steam versions. It is not usable for XBox Gamepass, MacOS, or console versions.

## Other Recommended Mods
Below are some other mods you might be interested in if you need even more ways to expand your Wargroove tools!

#### [Expanded Editor](https://www.nexusmods.com/wargroove/mods/28) by Unicarn.

Unlocks menus not possible with the usual modding tools, allowing for even more additional editing options. However, it requires the [Unofficial Modpacker](https://www.nexusmods.com/wargroove/mods/1) to use. Check the [Editor Comparisons](https://github.com/Tarquinous/wg-expanded-editor-3/wiki/Editor-Comparisons) for more information.

#### [**Expanded Terrain**](https://www.nexusmods.com/wargroove/mods/13) by Unicarn.

Completely overhauls how the terrain editor works. This lets you achieve impressively complex results, from lava rivers that work like roads, to simply placing a wall in water in an aesthetically pleasing way. It is, however, more complex to use.

#### [**Expanded Audio**](https://www.nexusmods.com/wargroove/mods/26) by Unicarn.

Allows Ambient sounds to be used as music on maps and cutscenes, and allowing music to be used as ambient sounds in cutscenes (allowing two overlapping songs, if you like). Similar functionality as this mod but doesn't requie disabling the mod any time you want to set something onto the Ambient slot.

## Features wishlist

Below are some features I would like to implement, if it is found to be possible:
* Ambient sounds as 'music' options for maps
* Place more than one Commander on the map at a time even after the mod is disabled
* Allow terrain to be placed in any location regardless of adjacent terrain
* Allow custom values for Ammo and Gold of newly placed Rifleman, Thief, and Thief_with_gold

## Version 1.4 checklist

- [x] Unhide previously hidden content to expand the mod
  - [x] Unhide emotes in the Cutscene Editor
  - [x] Unhide voicelines in the Cutscene Editor
- [ ] Improve usability of the mod with clearer UI
  - [ ] Introduce modified strings (e.g. removing "#MISSING#" from menues)
  - [x] Add custom icons for Volcano and Sky terrain
- [ ] Expand the wiki
  - [x] Shouts references list
  - [ ] Event actions/conditions images
  - [ ] Event actions/conditions descriptions
  - [x] Move "Unstable tools" list onto a dedicated page
  - [ ] Move unusued tools list onto a dedicated page
- [ ] Remove avoidable redundant overrides of game data (improves mod compatibility)
- [ ] Add commenting to old files to make source code easier to understand
- [ ] *Optional:* Make Volcano and Sky terrain have looser terrain limitations.
- [ ] Fix bugs / oversights
  - [x] Allow Ghost unit to be spawnable through events.
  - [x] Allow water units to be used in the Cutscene Editor
  - [x] Opening a Unit Info screen with Ghost present would cause an error (only when the mod is active).
