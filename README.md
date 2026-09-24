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

#### Automaton Frames
- ROM4/0/55.DAT | Events 620/621/622

  ```
  Patas (16419)          -> Tigerfangs (16422)
  Heavy Crossbow (17220) -> Repeating Crossbow (17221)
  ```

  Restores the pre-March-2015 automaton frame materials in Ghatsad's dialogue
  to match the era_choosing_an_automaton_frame server module.

#### Conquest Overseer Shops
- ROM/21/39.DAT | Southern San d'Oria
- ROM/21/40.DAT | Northern San d'Oria
- ROM/21/43.DAT | Bastok Mines
- ROM/21/44.DAT | Bastok Markets
- ROM/21/45.DAT | Port Bastok
- ROM/21/46.DAT | Metalworks
- ROM/21/47.DAT | Windurst Waters
- ROM/21/49.DAT | Port Windurst
- ROM/21/50.DAT | Windurst Woods
- ROM/21/52.DAT | Ru'Lude Gardens
- ROM/21/53.DAT | Upper Jeuno
- ROM/21/54.DAT | Lower Jeuno
- ROM/21/55.DAT | Port Jeuno

  Hides common items page 2 (Warp Ring, Ciphers, chair sets, nation flag) and the Emperor Band row.
  Sets Scroll of Instant Reraise to 500 CP and Scroll of Instant Warp to 750 CP
  to match the era_conquest_costs server module.

#### Adventurer Coupons
- ROM/21/39.DAT | Southern San d'Oria
- ROM/21/40.DAT | Northern San d'Oria
- ROM/21/41.DAT | Port San d'Oria
- ROM/21/43.DAT | Bastok Mines
- ROM/21/44.DAT | Bastok Markets
- ROM/21/45.DAT | Port Bastok
- ROM/21/47.DAT | Windurst Waters
- ROM/21/48.DAT | Windurst Walls
- ROM/21/49.DAT | Port Windurst
- ROM/21/50.DAT | Windurst Woods

  Removes the post-2008 "go speak to the tutorial guard" line from the coupon trade NPCs.
  Client-only.

#### Outpost Teleports
- ROM/20/37.DAT  | West Ronfaure
- ROM/20/40.DAT  | Valkurm Dunes
- ROM/20/41.DAT  | Jugner Forest
- ROM/20/43.DAT  | North Gustaberg
- ROM/20/46.DAT  | Pashhow Marshlands
- ROM/20/48.DAT  | Beaucedine Glacier
- ROM/20/49.DAT  | Xarcabard
- ROM/20/52.DAT  | West Sarutabaruta
- ROM/20/55.DAT  | Buburimu Peninsula
- ROM/20/56.DAT  | Meriphataud Mountains
- ROM/20/63.DAT  | Qufim Island
- ROM/21/40.DAT  | Northern San d'Oria
- ROM/21/43.DAT  | Bastok Mines
- ROM/21/49.DAT  | Port Windurst
- ROM/24/37.DAT  | West Ronfaure (Dialogue)
- ROM/24/40.DAT  | Valkurm Dunes (Dialogue)
- ROM/24/41.DAT  | Jugner Forest (Dialogue)
- ROM/24/43.DAT  | North Gustaberg (Dialogue)
- ROM/24/46.DAT  | Pashhow Marshlands (Dialogue)
- ROM/24/48.DAT  | Beaucedine Glacier (Dialogue)
- ROM/24/49.DAT  | Xarcabard (Dialogue)
- ROM/24/52.DAT  | West Sarutabaruta (Dialogue)
- ROM/24/55.DAT  | Buburimu Peninsula (Dialogue)
- ROM/24/56.DAT  | Meriphataud Mountains (Dialogue)
- ROM/24/63.DAT  | Qufim Island (Dialogue)
- ROM/25/40.DAT  | Northern San d'Oria (Dialogue)
- ROM/25/43.DAT  | Bastok Mines (Dialogue)
- ROM/25/49.DAT  | Port Windurst (Dialogue)
- ROM2/13/5.DAT  | Cape Teriggan
- ROM2/13/6.DAT  | Eastern Altepa Desert
- ROM2/13/7.DAT  | The Sanctuary of Zi'Tah
- ROM2/13/9.DAT  | Yuhtunga Jungle
- ROM2/13/10.DAT | Yhoator Jungle
- ROM2/17/46.DAT | Cape Teriggan (Dialogue)
- ROM2/17/47.DAT | Eastern Altepa Desert (Dialogue)
- ROM2/17/54.DAT | The Sanctuary of Zi'Tah (Dialogue)
- ROM2/17/56.DAT | Yuhtunga Jungle (Dialogue)
- ROM2/17/57.DAT | Yhoator Jungle (Dialogue)
- ROM3/0/77.DAT  | Oldton Movalpolos
- ROM3/0/90.DAT  | Lufaise Meadows
- ROM3/2/21.DAT  | Oldton Movalpolos (Dialogue)
- ROM3/2/34.DAT  | Lufaise Meadows (Dialogue)

  Removes the conquest point teleport option and fee text, leaving a gil-only Yes/No menu.
  Removes the "I now also deal in evoliths" greeting from outpost vendors
  to match the era_outpost_teleport_payment server module (ENABLE_VOIDWATCH = 0).

#### Teamwork Quests
- ROM/24/37.DAT | West Ronfaure (Dialogue)

  Restores Vilatroire's six-member party requirement text for Introduction/Intermediate/Advanced Teamwork
  to match the era teamwork server modules.

#### Subjob Quests
- ROM/21/57.DAT | Selbina
- ROM/21/58.DAT | Mhaura

  Removes the Gilgamesh's Introductory Letter alternate-item line from Isacio (The Old Lady) and Vera (Elder Memories).
  Client-only.

#### Guild Point Shops
- ROM/21/39.DAT | Southern San d'Oria
- ROM/21/40.DAT | Northern San d'Oria
- ROM/21/43.DAT | Bastok Mines
- ROM/21/44.DAT | Bastok Markets
- ROM/21/46.DAT | Metalworks
- ROM/21/47.DAT | Windurst Waters
- ROM/21/49.DAT | Port Windurst
- ROM/21/50.DAT | Windurst Woods
- ROM/25/39.DAT | Southern San d'Oria (Dialogue)
- ROM/25/40.DAT | Northern San d'Oria (Dialogue)
- ROM/25/43.DAT | Bastok Mines (Dialogue)
- ROM/25/44.DAT | Bastok Markets (Dialogue)
- ROM/25/46.DAT | Metalworks (Dialogue)
- ROM/25/47.DAT | Windurst Waters (Dialogue)
- ROM/25/49.DAT | Port Windurst (Dialogue)
- ROM/25/50.DAT | Windurst Woods (Dialogue)

  Hides signboards, craft rings, guild tools and emblems.
  Sets Aurora Crystal and Twilight Crystal to 500 GP
  to match the guild_point_shop server module (ENABLE_WOTG = 0).

#### Guild Master Rank Dialogue
- ROM/21/39.DAT | Southern San d'Oria | Faulpie (Leathercraft)
- ROM/21/40.DAT | Northern San d'Oria | Cheupirudaux (Woodworking), Mevreauche (Smithing)
- ROM/21/43.DAT | Bastok Mines        | Abd-al-Raziq (Alchemy)
- ROM/21/44.DAT | Bastok Markets      | Reinberta (Goldsmithing)
- ROM/21/46.DAT | Metalworks          | Ghemp (Smithing)
- ROM/21/47.DAT | Windurst Waters     | Piketo-Puketo (Cooking)
- ROM/21/50.DAT | Windurst Woods      | Ponono (Clothcraft), Peshi Yohnts (Bonecraft)

  Moves the "other guilds" caution from the Artisan test offer to the Craftsman test offer (skill 58+).
  Test offer names the Craftsman title instead of Artisan.
  Adds the era "don't spread yourself across guilds" line to the Craftsman promotion and removes it from Artisan.
  Restores the era Craftsman promotion wording for Faulpie, Mevreauche and Reinberta.
  Client-only.
