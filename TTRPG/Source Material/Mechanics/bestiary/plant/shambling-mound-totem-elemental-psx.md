---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/large
- monster/type/plant
statblock: inline
aliases: ["Shambling Mound Totem Elemental"]
---
# [Shambling Mound Totem Elemental](Mechanics\bestiary\plant/shambling-mound-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](Mechanics/bestiary/elemental/air-elemental.md), [earth](Mechanics/bestiary/elemental/earth-elemental.md), and [water elementals](Mechanics/bestiary/elemental/water-elemental.md), or to [treants](Mechanics/bestiary/plant/treant.md), blights, [shambling mounds](Mechanics/bestiary/plant/shambling-mound.md), or [awakened trees](Mechanics/bestiary/plant/awakened-tree.md) and [awakened shrubs](Mechanics/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](Mechanics/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Shambling Mound Totem Elemental (PSX)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "18"
- !!int "8"
- !!int "16"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "20 ft., swim 20 ft."
"skillsaves":
  "Stealth": !!int "2"
"damage_resistances": "cold, fire"
"damage_immunities": "lightning"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened),\
  \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "5"
"traits":
- "desc": "Whenever the shambling mound totem is subjected to lightning damage, it\
    \ takes no damage and regains a number of hit points equal to the lightning damage\
    \ dealt."
  "name": "Lightning Absorption"
"actions":
- "desc": "The shambling mound totem makes two slam attacks. If both attacks hit a\
    \ Medium or smaller target, the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 14), and the shambling mound totem uses its Engulf on it."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage."
  "name": "Slam"
- "desc": "The shambling mound totem engulfs a Medium or smaller creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by it. The engulfed target is [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained), and unable to breathe,\
    \ and it must succeed on a DC 14 Constitution saving throw at the start of each\
    \ of the mound's turns or take 13 (2d8 + 4) bludgeoning damage. If the mound\
    \ moves, the engulfed target moves with it. The mound can have only one creature\
    \ engulfed at a time."
  "name": "Engulf"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Shambling%20Mound%20Totem%20Elemental.webp"
```
^statblock