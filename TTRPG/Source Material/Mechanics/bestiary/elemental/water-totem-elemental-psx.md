---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/large
- monster/type/elemental
statblock: inline
aliases: ["Water Totem Elemental"]
---
# [Water Totem Elemental](Mechanics\bestiary\elemental/water-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](Mechanics/bestiary/elemental/air-elemental.md), [earth](Mechanics/bestiary/elemental/earth-elemental.md), and [water elementals](Mechanics/bestiary/elemental/water-elemental.md), or to [treants](Mechanics/bestiary/plant/treant.md), blights, [shambling mounds](Mechanics/bestiary/plant/shambling-mound.md), or [awakened trees](Mechanics/bestiary/plant/awakened-tree.md) and [awakened shrubs](Mechanics/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](Mechanics/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Water Totem Elemental (PSX)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "114"
"hit_dice": "12d10 + 48"
"stats":
- !!int "18"
- !!int "14"
- !!int "18"
- !!int "5"
- !!int "10"
- !!int "8"
"speed": "30 ft., swim 90 ft."
"damage_resistances": "acid; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Aquan"
"cr": "5"
"traits":
- "desc": "The totem elemental can enter a hostile creature's space and stop there.\
    \ It can move through a space as narrow as 1 inch wide without squeezing."
  "name": "Water Form"
- "desc": "If the totem elemental takes cold damage, it partially freezes; its speed\
    \ is reduced by 20 feet until the end of its next turn."
  "name": "Freeze"
"actions":
- "desc": "The totem elemental makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage."
  "name": "Slam"
- "desc": "Each creature in the totem elemental's space must make a DC 15 Strength\
    \ saving throw. On a failure, a target takes 13 (2d8 + 4) bludgeoning damage.\
    \ If it is Large or smaller, it is also [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 14). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ and unable to breathe unless it can breathe water. If the saving throw is successful,\
    \ the target is pushed out of the totem elemental's space.\n\nThe totem elemental\
    \ can grapple one Large creature or up to two Medium or smaller creatures at one\
    \ time. At the start of each of the totem elemental's turns, each target [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by it takes 13 (2d8 + 4) bludgeoning damage. A creature within 5 feet of the\
    \ totem elemental can pull a creature or object out of it by taking an action\
    \ to make a DC 14 Strength check and succeeding."
  "name": "Whelm (Recharge 4-6)"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Water%20Totem%20Elemental.webp"
```
^statblock