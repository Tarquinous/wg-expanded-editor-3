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
  * Placable units
  * Dialogue portraits
* Removes unlock requirements for the three secret commanders
* Removes unlock requirements for music

## How to Use

Load up a custom map you want to work on, open the "Mods" menu and enable the Expanded Editor mod. Click "Save and Reload Map" and all of the features should now be accessible! When you're finished and wish to upload your map, simply disable the mod.

None of your changes to the map will be lost when the mod is removed, as they are all used in vanilla WarGroove!

Unlockable content will return to being locked once the mod is removed if you have not yet unlocked them.

## Installation

Download the latest release file of the packed mod. Drop the contained folder into your mods folder at the `%appdata%/chucklefish/wargroove/mods` directory. Reload your game and it should now show up in your "Mods" menu in the map editor.

Mods are currently only available for Windows Steam versions. It is not usable for XBox Gamepass, MacOS, or console versions.

## Unstable Tools

Not all unlocked features are 100% stable for use. If you do use them please be aware they may cause crashes or unexpected behaviour. Though they should not affect your game or save file, be considerate for online players, and be cautious of using these features.

Below is a list of documentated unusual behaviours:
* Units and Commanders
  * Garrison: opening its Unit Info screen, or any other unit who displays the Garrison on its Unit Info screen, will return the player to the Main Menu.
  * Ghost: cannot move, attack, or perform any actions. Lacks most animations, including death animations. Its colour will not show its Player alignment (however you can see it as the background colour of their corner icon).
  * Loaded Thief always begins with 300 Gold.
  * Errol: cannot move, attack, or groove. Will appear similar to Errol & Orla on the map. They are functionally useless as a unit.
  * Orla: cannot move, attack, or groove. Will appear similar to Errol & Orla on the map. They are functionally useless as a unit.
  * Vesper (Boss): Missing text or link to a Codex entry from the Unit Info screen. Will display as "Vesper (Boss)" on player card. 
  * Soldiers, Thief, and Soldiers 2: will use unusual and inconsistent portraits during combat scenes, and displays as their respective name on the player card.
* Terrain
  * Volcano: tile looks identical to Plains and is indistinquishably invisible.
  * Sky: tile behaves as Plains, but has broken graphics.
* Sounds and Music:
  * Victory: music track does not loop. Extremely short.
  * Defeat: music track does not loop. Extremely short.
* Events and Triggers:
  * Button location highlights: graphic is platform-dependent, showing different controls.
  * Groove cutscene: event does not have an appropriate entry for Errol & Orla, and will display `#MISSING#` when used.
  * Stars conditions: checks based on the player's achieved Stars, which cannot be awarded in custom content, and are tied to their progress in the official Campaign Arcade, and Puzzle modes.
  * Dialogue: when the mod is disabled, returning to edit any event using a hidden Dialogue Portrait (e.g. "Soldiers 2"), it will instantly revert back to Mercia.

## Missing Features and Known Issues

Due to limitations of the Official Modpacker, not all features possible in the [Expanded Editor](https://www.nexusmods.com/wargroove/mods/28) mod by Unicarn are available. If you absolutely require these, I highly recommend installing and learning to use the [Unofficial Modpacker](https://www.nexusmods.com/wargroove/mods/1). These features include:

* No access to hidden menuing for map or player propertie, including:
  * Exporting Campaign maps to individual map files
  * Importing working maps into a Campaign
  * Stars requirements to play maps
  * Screen filters
* Input restraints removed, including:
  * Negative starting gold for players

Not all features possible are provided, due to a lack of practical use in-game:
* City terrain - identical to "Sky" terrain.
* smoke_producer, heal_area, and damage_area units - Crashes game due to lack of sprites.

## Future ideas

Below are some features I would like to implement, if it is found to be possible:
* Ambient sounds as 'music' options for maps
* Place more than one Commander on the map at a time even after the mod is disabled
* Allow terrain to be placed in any location regardless of adjacent terrain
* Allow custom values for Ammo and Gold of newly placed Rifleman, Thief, and Thief_with_gold
