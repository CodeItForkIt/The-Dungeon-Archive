---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/elf
statblock: inline
aliases: ["Ishel"]
---
# [Ishel](Mechanics\bestiary\npc/ishel-egw.md)
*Source: Explorer's Guide to Wildemount p. 231*  

Ishel—a drow ambassador from the Kryn Dynasty.

```statblock
"name": "Ishel (EGW)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[chain shirt](Mechanics/items/chain-shirt.md)"
"hp": !!int "24"
"hit_dice": "3d8"
"stats":
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "11"
- !!int "11"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Elvish, Undercommon"
"cr": "1/2"
"traits":
- "desc": "Ishel's spellcasting ability is Charisma (spell save DC 11). It can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](Mechanics/spells/dancing-lights.md)\n\n1/day each: [darkness](Mechanics/spells/darkness.md),\
    \ [faerie fire](Mechanics/spells/faerie-fire.md)"
  "name": "Innate Spellcasting"
- "desc": "Ishel has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put Ishel to sleep."
  "name": "Fey Ancestry"
- "desc": "While in sunlight, Ishel has disadvantage on attack rolls, as well as on\
    \ Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
    \ 5 (1d6 + 2) piercing damage, and the target must succeed on a DC 13 Constitution\
    \ saving throw or be [poisoned](Mechanics/Rules/conditions.md#Poisoned) for 1\
    \ hour. If the saving throw fails by 5 or more, the target is also [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ while [poisoned](Mechanics/Rules/conditions.md#Poisoned) in this way. The target\
    \ wakes up if it takes damage or if another creature takes an action to shake\
    \ it awake."
  "name": "Hand Crossbow"
"source":
- "EGW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Ishel.webp"
```
^statblock