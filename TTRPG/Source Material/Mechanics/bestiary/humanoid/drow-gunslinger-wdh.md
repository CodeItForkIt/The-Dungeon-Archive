---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdh
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/elf
statblock: inline
aliases: ["Drow Gunslinger"]
---
# [Drow Gunslinger](Mechanics\bestiary\humanoid/drow-gunslinger-wdh.md)
*Source: Waterdeep: Dragon Heist p. 201*  

Firearms aren't widely available in the North, but some members of Bregan D'aerthe are equipped with Lantanese pistols, bullets, and packets of smokepowder. These drow gunslingers are expert pistoleers, as skilled with their guns as the best archers are with their bows.

```statblock
"name": "Drow Gunslinger (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[studded leather](Mechanics/items/studded-leather-armor.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"stats":
- !!int "13"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "3"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "3"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Elvish, Undercommon"
"cr": "4"
"traits":
- "desc": "The drow's spellcasting ability is Charisma (spell save DC 12) It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](Mechanics/spells/dancing-lights.md)\n\n1/day each: [darkness](Mechanics/spells/darkness.md),\
    \ [faerie fire](Mechanics/spells/faerie-fire.md), [levitate](Mechanics/spells/levitate.md)\
    \ (self only)"
  "name": "Innate Spellcasting"
- "desc": "The drow has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put the drow to sleep."
  "name": "Fey Ancestry"
- "desc": "Being within 5 feet of a hostile creature or attacking at long range doesn't\
    \ impose disadvantage on the drow's ranged attack rolls with a pistol. In addition,\
    \ the drow ignores half cover and three-quarters cover when making ranged attacks\
    \ with a pistol."
  "name": "Gunslinger"
- "desc": "While in sunlight, the drow has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The drow makes two shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +6 to hit, range 30/90 ft., one target. Hit:\
    \ 9 (1d10 + 4) piercing damage plus 11 (2d10) poison damage."
  "name": "Poisonous Pistol"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDH/Drow%20Gunslinger.webp"
```
^statblock