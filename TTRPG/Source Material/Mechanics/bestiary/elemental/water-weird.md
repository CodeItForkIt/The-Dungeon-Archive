---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/3
- monster/environment/underdark
- monster/environment/urban
- monster/size/large
- monster/type/elemental
statblock: inline
aliases: ["Water Weird"]
---
# [Water Weird](Mechanics\bestiary\elemental/water-weird.md)
*Source: Monster Manual p. 299, Princes of the Apocalypse, Dragon of Icespire Peak, Storm Lord's Wrath, Mythic Odysseys of Theros, Icewind Dale: Rime of the Frostmaiden, Candlekeep Mysteries, Journeys through the Radiant Citadel, Dragonlance: Shadow of the Dragon Queen, Phandelver and Below: The Shattered Obelisk, Lightning Keep, Vecna: Eve of Ruin, Quests from the Infinite Staircase*  

A water weird is an elemental guardian bound to a specific water-filled location, such as a pool or fountain.

Invisible while immersed in water, its serpentine shape becomes clear only when it emerges to attack, using its coils to crush any creature other than its summoner and those its summoner declares as off limits. When slain, a water weird becomes an inanimate pool of water.

## Good and Evil Weirds

Like most elementals, a water weird has no concept of good or evil. However, a water weird bound to a sacred or befouled source of water begins to take on the nature of that site, becoming neutral good or neutral evil.

A neutral good water weird tries to frighten away interlopers rather than kill them, while a neutral evil water weird kills its victims for pleasure and might turn against its summoner. A water weird loses its evil alignment if its waters are cleansed with a [purify food and drink](Mechanics/spells/purify-food-and-drink.md) spell.

## Elemental Nature

A water weird doesn't require air, food, drink, or sleep.

> [!quote] A quote from X the Mystic's 2nd rule of dungeon survival  
> 
> Before you drink from a fountain or pool, toss a copper coin into it. It's a small price to pay for your life.


```statblock
"name": "Water Weird"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "58"
"hit_dice": "9d10 + 9"
"stats":
- !!int "17"
- !!int "16"
- !!int "13"
- !!int "11"
- !!int "10"
- !!int "10"
"speed": "0 ft., swim 60 ft."
"damage_resistances": "fire; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "blindsight 30 ft., passive Perception 10"
"languages": "understands Aquan but doesn't speak"
"cr": "3"
"traits":
- "desc": "The water weird is [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ while fully immersed in water."
  "name": "Invisible in Water"
- "desc": "The water weird dies if it leaves the water to which it is bound or if\
    \ that water is destroyed."
  "name": "Water Bound"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one creature. Hit:\
    \ 13 (3d6 + 3) bludgeoning damage. If the target is Medium or smaller, it is\
    \ [grappled](Mechanics/Rules/conditions.md#Grappled) (escape DC 13) and pulled\
    \ 5 feet toward the water weird. Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ the water weird tries to drown it, and the water weird can't constrict another\
    \ target."
  "name": "Constrict"
"source":
- "MM"
- "PotA"
- "DIP"
- "SLW"
- "MOT"
- "IDRotF"
- "CM"
- "JttRC"
- "DSotDQ"
- "PaBTSO"
- "LK"
- "VEoR"
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Water%20Weird.webp"
```
^statblock

## Environment

underdark, urban