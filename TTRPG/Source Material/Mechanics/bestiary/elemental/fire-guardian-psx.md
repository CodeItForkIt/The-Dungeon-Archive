---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/large
- monster/type/elemental
statblock: inline
aliases: ["Fire Guardian"]
---
# [Fire Guardian](Mechanics\bestiary\elemental/fire-guardian-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](Mechanics/bestiary/elemental/air-elemental.md), [earth](Mechanics/bestiary/elemental/earth-elemental.md), and [water elementals](Mechanics/bestiary/elemental/water-elemental.md), or to [treants](Mechanics/bestiary/plant/treant.md), blights, [shambling mounds](Mechanics/bestiary/plant/shambling-mound.md), or [awakened trees](Mechanics/bestiary/plant/awakened-tree.md) and [awakened shrubs](Mechanics/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](Mechanics/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Fire Guardian (PSX)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "102"
"hit_dice": "12d10 + 36"
"stats":
- !!int "10"
- !!int "17"
- !!int "16"
- !!int "6"
- !!int "10"
- !!int "7"
"speed": "50 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Ignan"
"cr": "5"
"traits":
- "desc": "The fire guardian can move through a space as narrow as 1 inch wide without\
    \ squeezing. A creature that touches the fire guardian or hits it with a melee\
    \ attack while within 5 feet of it takes 5 (1d10) fire damage. In addition,\
    \ the fire guardian can enter a hostile creature's space and stop there. The first\
    \ time it enters a creature's space on a turn, that creature takes 5 (1d10)\
    \ fire damage and catches fire; until someone takes an action to douse the fire,\
    \ the creature takes 5 (1d10) fire damage at the start of each of its turns."
  "name": "Fire Form"
- "desc": "The fire guardian sheds bright light in a 30-foot radius and dim light\
    \ in an additional 30 feet."
  "name": "Illumination"
- "desc": "For every 5 feet the fire guardian moves in water, or for every gallon\
    \ of water splashed on it, it takes 1 cold damage."
  "name": "Water Susceptibility"
"actions":
- "desc": "The fire guardian makes two touch attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) fire damage. If the target is a creature or a flammable object,\
    \ it ignites. Until a creature takes an action to douse the fire, the target takes\
    \ 5 (1d10) fire damage at the start of each of its turns."
  "name": "Touch"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Fire%20Guardian.webp"
```
^statblock