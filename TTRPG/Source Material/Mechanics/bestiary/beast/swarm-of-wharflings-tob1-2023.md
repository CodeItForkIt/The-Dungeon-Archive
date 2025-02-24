---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/coastal
- monster/environment/underwater
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Swarm of Wharflings"]
---
# [Swarm of Wharflings](Mechanics\bestiary\beast/swarm-of-wharflings-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 395*  

*The hairless canine scurries along the pier, dripping with water and carrying a fish in its jaws. Its finned claws click on the planks as a fishmonger yells from behind it.*

## Waterborne Packs

Wharflings are hairless, aquatic canines with large, webbed feet and oversized mouths. Adept fish catchers, wharflings establish dens near the shores of oceans, lakes, and rivers, and they often move in family groups of three or more.

## Thieving Gits

Those who have been bitten by a wharfling rightly fear their needle-like teeth, but most coastal communities hate the animal more for its propensity for theft. Their lairs are filled with stolen metal trinkets.

## Beach Swarms

Periodically, wharflings congregate in huge numbers and tear along the shoreline for miles before returning to their dens. Why they gather this way is unknown, but most locals know to avoid the shore on these nights.

```statblock
"name": "Swarm of Wharflings (ToB1-2023)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "66"
"hit_dice": "12d10"
"stats":
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "2"
- !!int "12"
- !!int "8"
"speed": "30 ft., climb 10 ft., swim 30 ft."
"skillsaves":
  "Sleight of Hand": !!int "5"
  "Perception": !!int "3"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "3"
"traits":
- "desc": "The swarm of wharflings can breathe air and water."
  "name": "Amphibious"
- "desc": "A creature that attempts to move out of or through the swarm of wharflings\
    \ must succeed on a DC 13 Dexterity saving throw or take 7 (2d6) piercing damage."
  "name": "Snapping Jaws"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny wharfling. The swarm can't\
    \ regain hp or gain temporary hp."
  "name": "Swarm"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 0 ft., one creature in the swarm's\
    \ space. Hit: 28 (8d6) piercing damage, or 14 (4d6) piercing damage if the\
    \ swarm has half of its hp or fewer, and the target must succeed on a DC 13 Dexterity\
    \ saving throw or lose one item it is wearing or carrying to the swarm, provided\
    \ the item weighs no more than 10 pounds, isn't a weapon, and isn't wrapped around\
    \ or firmly attached to the target, such as a shirt or armor."
  "name": "Pilfering Bites"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Swarm%20of%20Wharflings.webp"
```
^statblock

## Environment

coastal, underwater