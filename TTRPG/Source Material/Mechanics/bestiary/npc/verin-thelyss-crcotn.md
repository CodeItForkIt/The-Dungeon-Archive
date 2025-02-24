---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/drow
- monster/type/humanoid/elf
statblock: inline
aliases: ["Verin Thelyss"]
---
# [Verin Thelyss](Mechanics\bestiary\npc/verin-thelyss-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 51*  

To the people of Bazzoxan, Verin is a beacon of hope amid the darkness that shrouds the town. But the weight of responsibility colors Verin's otherwise bright and youthful demeanor with melancholy. He cares about the town he has sworn to protect, but he is weary of the incessant threat posed by the denizens of the Betrayers' Rise.

```statblock
"name": "Verin Thelyss (CRCotN)"
"size": "Medium"
"type": "humanoid"
"subtype": "drow, elf"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "[half plate](Mechanics/items/half-plate-armor.md)"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"stats":
- !!int "18"
- !!int "15"
- !!int "14"
- !!int "13"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Strength": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "Athletics": !!int "7"
  "Perception": !!int "5"
  "History": !!int "4"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Common, Elvish, Undercommon"
"cr": "5"
"traits":
- "desc": "Verin casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 14):\n\nAt will:\
    \ [dancing lights](Mechanics/spells/dancing-lights.md)\n\n1/day each: [darkness](Mechanics/spells/darkness.md),\
    \ [faerie fire](Mechanics/spells/faerie-fire.md), [levitate](Mechanics/spells/levitate.md)\
    \ (self only)"
  "name": "Spellcasting"
- "desc": "Verin has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put him to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Verin has disadvantage on attack rolls, as well as on\
    \ Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Verin makes three Glaive attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 9\
    \ (1d10 + 4) slashing damage."
  "name": "Glaive"
- "desc": "Ranged Weapon Attack: +7 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage plus 22 (4d10) poison damage."
  "name": "Hand Crossbow"
"bonus_actions":
- "desc": "Verin magically creates an echo—a translucent, gray object that looks like\
    \ him. The echo appears in an unoccupied space Verin can see within 15 feet of\
    \ himself. While the echo exists, Verin chooses whether each of his attacks originates\
    \ from his space or the echo's space. On Verin's turn, the echo can move in accordance\
    \ with Verin's wishes. The echo has AC 17 and 1 hit point. It otherwise uses Verin's\
    \ statistics. The echo lasts for 1 minute or until it is destroyed, until Verin\
    \ ends his turn more than 30 feet away from it, until Verin manifests another\
    \ echo, or until Verin is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Manifest Echo"
- "desc": "Verin magically swaps places with his echo."
  "name": "Reposition"
"reactions":
- "desc": "Verin adds 3 to his AC against one melee attack that would hit him. To\
    \ do so, he must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "CRCotN"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Verin%20Thelyss.webp"
```
^statblock