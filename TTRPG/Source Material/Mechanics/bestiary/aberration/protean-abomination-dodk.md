---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/6
- monster/size/huge
- monster/type/aberration
statblock: inline
aliases: ["Protean Abomination"]
---
# [Protean Abomination](Mechanics\bestiary\aberration/protean-abomination-dodk.md)
*Source: Dungeons of Drakkenheim p. 201*  

Occasionally, a creature's rapid mutations become too much for its body to withstand. In a horrific shower of gore, such wretches explode into a quivering mass of cancerous tumors, babbling mouths, shifting eyes, and grasping limbs that twist, expand, and retract in grotesque and bizarre ways.

```statblock
"name": "Protean Abomination (DoDk)"
"size": "Huge"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d12 + 64"
"stats":
- !!int "21"
- !!int "8"
- !!int "18"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "30 ft., climb 10 ft."
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [prone](Mechanics/Rules/conditions.md#Prone)"
"senses": "blindsight 60 ft., passive Perception 10"
"languages": ""
"cr": "6"
"traits":
- "desc": "When the protean abomination kills a creature that is neither a construct\
    \ nor undead, it absorbs the corpse into its body and regains 20 hit points."
  "name": "Absorption"
- "desc": "The protean abomination can move through a space as narrow as 1 inch wide\
    \ without squeezing."
  "name": "Amorphous"
- "desc": "The protean abomination can climb difficult surfaces, including upside\
    \ down on ceilings, without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The protean abomination makes two slam attacks. If both attacks hit a Large\
    \ or smaller target, the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 15), and the protean abomination uses Engulf on it."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 19\
    \ (3d8 + 5) bludgeoning damage."
  "name": "Slam"
- "desc": "The protean abomination engulfs a Large or smaller creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by it. Until the grapple ends the target is [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained), and unable to breathe,\
    \ and it must succeed on a DC 15 Constitution saving throw at the start of each\
    \ of the abomination's turns or take 19 (3d8 + 5) bludgeoning damage. If the\
    \ abomination moves, the engulfed target moves with it. The abomination can have\
    \ only one creature engulfed at a time."
  "name": "Engulf"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Protean%20Abomination.webp"
```
^statblock