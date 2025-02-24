---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/8
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
aliases: ["Harmonium Captain"]
---
# [Harmonium Captain](Mechanics\bestiary\humanoid/harmonium-captain-mpp.md)
*Source: Morte's Planar Parade p. 58, Sigil and the Outlands, Turn of Fortune's Wheel*  

Harmonium captains lead peacekeeper patrols throughout Sigil. They bolster their subordinates in battle and bring the authority of the Harmonium crashing down on suspects with their commands.

```statblock
"name": "Harmonium Captain (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "20"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"stats":
- !!int "19"
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "16"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Strength": !!int "7"
"skillsaves":
  "Perception": !!int "6"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "passive Perception 16"
"languages": "Common plus one more language"
"cr": "8"
"traits":
- "desc": "Allies within 30 feet of the captain are immune to the [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ and [frightened](Mechanics/Rules/conditions.md#Frightened) conditions. This\
    \ aura is suppressed while the captain has the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition."
  "name": "Aura of Command"
"actions":
- "desc": "The captain makes three Harmonium Blade attacks. The captain can also use\
    \ Dictate if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 9 (1d10\
    \ + 4) piercing damage plus 10 (3d6) lightning damage."
  "name": "Harmonium Blade"
- "desc": "The captain verbally commands up to three creatures it can see within 60\
    \ feet of itself. This magical command must be to undertake an action or to refrain\
    \ from taking actions (for example, \"Throw down your weapons\").\n\nA target\
    \ must succeed on a DC 14 Wisdom saving throw or have the [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ condition for 1 minute, during which time it follows the captain's command.\
    \ The effect ends early if the target takes damage or if it successfully completes\
    \ the command. A target automatically succeeds on its saving throw if the command\
    \ is directly harmful to itself, such as commanding it to walk into fire.\n\n\
    A creature can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a successful save."
  "name": "Dictate (Recharge 5-6)"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Harmonium%20Captain.webp"
```
^statblock