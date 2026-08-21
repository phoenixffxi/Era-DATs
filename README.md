# Era-DATs

A repository hosting custom DAT files for running a Level 75 era Final Fantasy XI private server using [Phoenix](https://github.com/phoenixffxi/Phoenix), a downstream fork of LandSandBoat.

## Overview

This repository contains game data files (DATs) required for implementing era-accurate content on the Phoenix repository. These files include custom Limbus content and other era-specific game data that restores Lv 75 era functionality and dialogues.

Tool used for editing DATs: https://github.com/Frankie-hz/Kraken

## Dat Lists

### Dynamis Zone DATs
- ROM2/13/121.DAT | Dynamis Sandoria
- ROM2/13/122.DAT | Dynamis Bastok
- ROM2/13/123.DAT | Dynamis Windurst
- ROM2/13/124.DAT | Dynamis Jeuno
- ROM2/13/104.DAT | Dynamis Beaucedine
- ROM2/13/105.DAT | Dynamis Xarcabard
- ROM3/3/21.DAT   | Dynamis Valkurm
- ROM3/3/22.DAT   | Dynamis Buburimu
- ROM3/3/23.DAT   | Dynamis Qufim
- ROM3/3/24.DAT   | Dynamis Tavnazia

### Armor and Item DATs
- ROM/0/4.dat	    | GeneralItems (JP)
- ROM/0/5.dat	    | UsableItems (JP)
- ROM/0/6.dat	    | Weapons (JP)
- ROM/0/7.dat	    | Armor (JP)
- ROM/0/8.dat	    | PuppetItems (JP)
- ROM/118/106.dat	| GeneralItems
- ROM/118/107.dat	| UsableItems
- ROM/118/108.dat	| Weapons
- ROM/118/109.dat	| Armor
- ROM/118/110.dat	| PuppetItems
- ROM/286/72.dat	| Armor2 (JP)
- ROM/286/73.dat	| Armor2
- ROM/301/114.dat	| GeneralItems2 (JP)
- ROM/301/115.dat	| GeneralItems2

### Spell DATs
- ROM\118\114     | Data Dat (Spell and abilities)
- ROM\181\73.DAT  | Names
- ROM\181\69.DAT  | Names (JP)
- ROM\181\75.DAT  | Descriptions
- ROM\181\71.DAT  | Descriptions (JP)

### Zone DATs
- ROM/26/103.DAT  | Ranguemont Pass
- ROM/26/104.DAT  | Bostaunieux Oubliette
- ROM/26/106.DAT  | Toraimarai Canal
- ROM/26/109.DAT  | Zeruhn Mines
- ROM/26/127.DAT  | King Ranperre's Tomb
- ROM/27/0.DAT    | Dangruf Wadi
- ROM/27/1.DAT    | Inner Horutoto Ruins
- ROM/27/2.DAT    | Ordelle's Caves
- ROM/27/3.DAT    | Outer Horutoto Ruins
- ROM/27/4.DAT    | The Eldieme Necropolis
- ROM/27/5.DAT    | Gusgen Mines
- ROM/27/6.DAT    | Crawlers Nest
- ROM/27/7.DAT    | Maze of Shakhrami
- ROM/27/9.DAT    | Garlaige Citadel
- ROM/27/13.DAT   | Fei'Yin
- ROM2/13/106.DAT | The Boyahda Tree
- ROM2/13/114.DAT | Kuftal Tunnel
- ROM2/13/117.DAT | The Shrine of Ru'Avitau
- ROM2/14/5.DAT   | Gustav Tunnel
- ROM2/14/6.DAT   | Labyrinth of Onzozo
- ROM3/2/114.DAT  | Bibiki Bay
- ROM3/2/115.DAT  | Uleguerand Range
- ROM3/2/126.DAT  | Promyvion - Holla
- ROM3/3/0.DAT    | Promyvion - Dem
- ROM3/3/2.DAT    | Promyvion - Mea
- ROM3/3/4.DAT    | Promyvion - Vahzl
- ROM3/3/7.DAT    | Misareaux Coast
- ROM3/3/9.DAT    | Phomiuna Aqueducts
- ROM3/3/10.DAT   | Sacrarium
- ROM3/3/11.DAT   | Riverne - Site B01
- ROM3/3/12.DAT   | Riverne - Site A01
- ROM4/1/51.DAT   | Bhaflau Thickets
- ROM4/1/53.DAT   | Arrapago Reef
- ROM4/1/67.DAT   | Aydeewa Subterrane
- ROM4/1/78.DAT   | Caedarva Mire

### Events
- ROM4/0/55.DAT | Events 620/621/622

  ```
  Patas (16419)          -> Tigerfangs (16422)
  Heavy Crossbow (17220) -> Repeating Crossbow (17221)
  ```

  Restores the pre-March-2015 automaton frame materials in Ghatsad's dialogue
  to match the era_choosing_an_automaton_frame server module.
