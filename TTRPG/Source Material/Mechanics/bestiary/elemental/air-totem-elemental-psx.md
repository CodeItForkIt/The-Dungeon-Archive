---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/large
- monster/type/elemental
statblock: inline
aliases: ["Air Totem Elemental"]
---
# [Air Totem Elemental](Mechanics\bestiary\elemental/air-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](Mechanics/bestiary/elemental/air-elemental.md), [earth](Mechanics/bestiary/elemental/earth-elemental.md), and [water elementals](Mechanics/bestiary/elemental/water-elemental.md), or to [treants](Mechanics/bestiary/plant/treant.md), blights, [shambling mounds](Mechanics/bestiary/plant/shambling-mound.md), or [awakened trees](Mechanics/bestiary/plant/awakened-tree.md) and [awakened shrubs](Mechanics/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](Mechanics/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Air Totem Elemental (PSX)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "15"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"stats":
- !!int "14"
- !!int "20"
- !!int "14"
- !!int "6"
- !!int "10"
- !!int "6"
"speed": "fly 90 ft. (hover)"
"damage_resistances": "lightning; thunder; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Auran"
"cr": "5"
"traits":
- "desc": "The totem elemental can enter a hostile creature's space and stop there.\
    \ It can move through a space as narrow as 1 inch wide without squeezing."
  "name": "Air Form"
"actions":
- "desc": "The totem elemental makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) bludgeoning damage."
  "name": "Slam"
- "desc": "Each creature in the totem elemental's space must make a DC 13 Strength\
    \ saving throw. On a failure, a target takes 15 (3d8 + 2) bludgeoning damage\
    \ and is flung up 20 feet away from the totem elemental in a random direction\
    \ and knocked [prone](Mechanics/Rules/conditions.md#Prone). If a thrown target\
    \ strikes an object, such as a wall or floor, the target takes 3 (1d6) bludgeoning\
    \ damage for every 10 feet it was thrown. If the target is thrown at another creature,\
    \ that creature must succeed on a DC 13 Dexterity saving throw or take the same\
    \ damage and be knocked [prone](Mechanics/Rules/conditions.md#Prone).\n\nIf the\
    \ saving throw is successful, the target takes half the bludgeoning damage and\
    \ isn't flung away or knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Whirlwind (Recharge 4-6)"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Air%20Totem%20Elemental.webp"
```
^statblock