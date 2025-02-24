---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/1-2
- monster/size/medium
- monster/type/plant
statblock: inline
aliases: ["Blight Totem Elemental"]
---
# [Blight Totem Elemental](Mechanics\bestiary\plant/blight-totem-elemental-psx.md)
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](Mechanics/bestiary/elemental/air-elemental.md), [earth](Mechanics/bestiary/elemental/earth-elemental.md), and [water elementals](Mechanics/bestiary/elemental/water-elemental.md), or to [treants](Mechanics/bestiary/plant/treant.md), blights, [shambling mounds](Mechanics/bestiary/plant/shambling-mound.md), or [awakened trees](Mechanics/bestiary/plant/awakened-tree.md) and [awakened shrubs](Mechanics/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](Mechanics/bestiary/elemental/fire-elemental.md).

```statblock
"name": "Blight Totem Elemental (PSX)"
"size": "Medium"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d8 + 4"
"stats":
- !!int "15"
- !!int "8"
- !!int "14"
- !!int "5"
- !!int "10"
- !!int "3"
"speed": "10 ft."
"skillsaves":
  "Stealth": !!int "1"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": "Common"
"cr": "1/2"
"traits":
- "desc": "While the blight totem remains motionless, it is indistinguishable from\
    \ a tangle of vines."
  "name": "False Appearance"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 10 ft., one target. Hit: 9\
    \ (2d6 + 2) bludgeoning damage, and a Large or smaller target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 12). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the blight totem can't constrict another target."
  "name": "Constrict"
- "desc": "Grasping roots and vines sprout in a 15-foot radius centered on the blight\
    \ totem, withering away after 1 minute. For the duration, that area is difficult\
    \ terrain for nonplant creatures. In addition, each creature of the blight totem's\
    \ choice in that area when the plants appear must succeed on a DC 12 Strength\
    \ saving throw or become [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ A creature can use its action to make a DC 12 Strength check, freeing itself\
    \ or another entangled creature within reach on a success."
  "name": "Entangling Plants (Recharge 5-6)"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Blight%20Totem%20Elemental.webp"
```
^statblock