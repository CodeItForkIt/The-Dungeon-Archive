---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/large
- monster/type/elemental
statblock: inline
aliases: ["Earth Totem Elemental"]
---
# [Earth Totem Elemental](Mechanics\bestiary\elemental/earth-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](Mechanics/bestiary/elemental/air-elemental.md), [earth](Mechanics/bestiary/elemental/earth-elemental.md), and [water elementals](Mechanics/bestiary/elemental/water-elemental.md), or to [treants](Mechanics/bestiary/plant/treant.md), blights, [shambling mounds](Mechanics/bestiary/plant/shambling-mound.md), or [awakened trees](Mechanics/bestiary/plant/awakened-tree.md) and [awakened shrubs](Mechanics/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](Mechanics/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Earth Totem Elemental (PSX)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d10 + 60"
"stats":
- !!int "20"
- !!int "8"
- !!int "20"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "30 ft., burrow 30 ft."
"damage_vulnerabilities": "thunder"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 10"
"languages": "Terran"
"cr": "5"
"traits":
- "desc": "The totem elemental can burrow through nonmagical, unworked earth and stone.\
    \ While doing so, the totem elemental doesn't disturb the material it moves through."
  "name": "Earth Glide"
- "desc": "The totem elemental deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The totem elemental makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d8 + 5) bludgeoning damage."
  "name": "Slam"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Earth%20Totem%20Elemental.webp"
```
^statblock