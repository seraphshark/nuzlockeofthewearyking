---
layout: page
title: Nitty-Gritty
nav_order: 5
---
# The Nitty-Gritty

If you're interested in exactly what will be changed, I'll write it allllll out here.

## Evolutions
Evolutions remain mostly unchanged, with the exceptions of evolutions involving trading pokemon. Every pokemon that evolves by trade has been changed to a different method, written below. (this is specifically for black/white/2)

| Pokemon    | Evolution  | Old Method            | New Method                   |
| ---------- | ---------- | --------------------- | ---------------------------- |
| Poliwhirl  | Politoed   | Trade w/ King’s Rock  | Level w/ King’s Rock         |
| Kadabra    | Alakazam   | Trade                 | Level 37                     |
| Graveler   | Golem      | Trade                 | Level 37                     |
| Machoke    | Machamp    | Trade                 | Level 37                     |
| Slowpoke   | Slowking   | Trade w/ King’s Rock  | Water Stone                  |
| Haunter    | Gengar     | Trade                 | Level 37                     |
| Onix       | Steelix    | Trade w/ Metal Coat   | Level w/ Metal Coat          |
| Rhydon     | Rhyperior  | Trade w/ Protector    | Level w/ Protector           |
| Seadra     | Kingdra    | Trade w/ Dragon Scale | Level w/ Dragon Scale        |
| Scyther    | Scizor     | Trade w/ Metal Coat   | Level w/ Metal Coat          |
| Electabuzz | Electivire | Trade w/ Electirizer  | Level w/ Electirizer         |
| Magmar     | Magmortar  | Trade w/ Magmarizer   | Level w/ Magmarizer          |
| Porygon    | Porygon2   | Trade w/ Up-Grade     | Level w/ Up-Grade            |
| Porygon2   | Porygon-Z  | Trade w/ Dubious Disc | Level w/ Dubious Disc        |
| Feebas     | Milotic    | Trade w/ Prism Scale  | Level w/ Prism Scale         |
| Dusclops   | Dusknoir   | Trade w/ Reaper Cloth | Level w/ Reaper Cloth        |
| Clamperl   | Huntail    | Trade w/ DeepSeaTooth | Level w/ DeepSeaTooth        |
| Clamperl   | Gorebyss   | Trade w/ DeepSeaScale | Level w/ DeepSeaScale        |
| Boldore    | Gigalith   | Trade                 | Level 37                     |
| Gurdurr    | Conkeldurr | Trade                 | Level 37                     |
| Karrablast | Escavalier | Trade w/ Shelmet      | Level w/ Shelmet in Party    |
| Shelmet    | Accelgor   | Trade w/ Karrablast   | Level w/ Karrablast in Party |
|            |            |                       |                              |

## Pokemon Randomization
- STARTERS have been randomized to a basic pokemon with 2 evolutions.
- STATIC pokemon are randomized by swapping legendaries for another legendary, and regular pokemon for other regular pokemon.
- IN-GAME TRADE pokemon are completely random, both the requested and given pokemon.
- TRAINERS each have a random type assigned to them, and will be given random pokemon of that type. This includes Gyms and Elite Four.
  - Trainers cannot have legendaries.
  - Trainers will not have a Shedinja with Wonder Guard before level 20. Just in case.
  - Trainers will evolve their pokemon if the pokemon is high enough level, instead of hanging onto a level 50 rattata or something.
- WILD pokemon are randomized by replacing each pokemon available in a "set" of encounters based on map location.
    - I'll be honest, I'm not entirely sure how it differs from the option "1 Per Named Location" so we're just gonna have to see how it works.
    - Encounter types will remain separate, like surfing in an area will give you different pokemon than when youre just walking around in that same area.
    - Zone type themes are preserved, like if an area has for example, all pokemon that are grass or bug type in a forest, it'll randomly assign grass or bug pokemon.
    - Time-based encounters are enabled, so different pokemon will show up in different seasons or times (cant remember if black/white have time based encounters)
    - Legendaries ARE POSSIBLE to show up!
    - National dex is available at the start so you could see ANY pokemon in the game.

## Things Unchanged
Items, Moves, and TMs are all the same as usual!


The following is some of the raw text logs from the randomization settings:
```
( Overview of Randomization {OVRD} )

Pokemon Base Statistics: Unchanged
Pokemon Types: Unchanged
Pokemon Abilities: Unchanged
Pokemon Evolutions: Randomized/Changed
Starter Pokemon: Randomized/Changed
Static Pokemon: Randomized/Changed
In-Game Trades: Randomized/Changed
Move Data: Unchanged
Pokemon Movesets: Unchanged
Trainer Pokemon: Randomized/Changed
Trainer Movesets: Unchanged
Trainer Names: Unchanged
Wild Pokemon: Randomized/Changed
TM Moves: Unchanged
TM/HM Compatibility: Unchanged
Field Items: Unchanged
Shop Items: Unchanged
Pickup Items: Unchanged
Type Effectiveness: Unchanged
Pokemon Palettes: Unchanged

The following Misc. Tweaks were applied:
Fastest Text
Give National Dex at Start
Run Without Running Shoes
```
