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
  * Cutscene SFX
  * Cutscene VFX
  * Placable units
  * Dialogue portraits
* Removes unlock requirements for the three unlockable commanders

## How to Use

Load up a custom map you want to work on, open the "Mods" menu and enable the Expanded Editor mod. Click "Reload map" and all of the features should now be accessible! When you're finished and wish to upload your map, simply disable the mod.

None of your changes to the map will be lost when the mod is removed, as they are all used in vanilla WarGroove!

Unlockable content will return to being locked once the mod is removed if you have not yet unlocked them.

## Installation

Download the latest release file of the packed mod. Drop the mod folder into your mods folder in the `%appdata%/chucklefish/wargroove/mods` directory. Reload your game and it should now show up in your "Mods" menu in the map editor.

Mods are currently only available for Windows Steam versions. It is not usable for XBox Gamepass, MacOS, or console versions.

## Unstable Tools

Not all unlocked features are 100% stable for use. If you do use them please be aware they may cause crashes or unexpected behaviour:
* The "Garrison" unit type will return you to the Main Menu if you open its Unit Info screen.
* The seperate commanders Errol and Orla (not to be confused with Errol & Orla) cannot move, attack, or groove. They are functionally useless as units.
* The "Ghost" unit cannot attack, move, or perform any actions (it cannot even "Wait"), and lacks most animations. Its colour will not show its Player alignment (however you can see it as the background colour of their corner icon). It will not cause any crashes, but is functionally a breakable wall.
* the "Volcano" terrain tile looks identical to Plains and is indistinquishably invisible.
* The button location highlights depend on the platform, showing different controls.
* The "victory" and "defeat" music tracks will never loop, and are barely a few seconds long.
* the "Groove Cutscene" event does not have an appropriate entry for Errol & Orla, and will display `#MISSING#` when used.
* All events checking Stars are based on the player's achieved Stars, which cannot be awarded in custom content and thus unlikely to be useful in the way it is used officially.
* Loaded Thief always begins with 300 Gold.

## Missing Features and Known Issues

Due to limitations of the Official Modpacker, not all features possible in the [Expanded Editor](https://www.nexusmods.com/wargroove/mods/28) mod by Unicarn are available. If you absolutely require these, I highly recommend installing and learning to use the [Unofficial Modpacker](https://www.nexusmods.com/wargroove/mods/1). These features include:

* No access to hidden menuing for map or player properties. This includes:
  * Exporting Campaign maps to individual map files
  * Importing working maps into a Campaign
  * Stars requirements to play maps
  * Screen filters
* Input restraints removed. This includes:
  * Negative starting gold for players

For the curious, these are a list of features not provided due to in-game lack of support:
* City terrain - Crashes due to lack of sprites
* smoke_producer, heal_area, and damage_area units - Crashes due to lack of sprites

## Future ideas

Below are some features I would like to implement, if it is found to be possible:
* Ambient sounds as 'music' options for maps
* Place more than one Commander on the map at a time even after the mod is disabled
* Allow terrain to be placed in any location regardless of adjacent terrain
* Allow custom values for Ammo and Gold of newly placed Rifleman, Thief, and Thief_with_gold
