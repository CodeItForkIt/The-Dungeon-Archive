---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/1
- monster/size/small
- monster/type/aberration
statblock: inline
aliases: ["Derro Apprentice"]
---
# [Derro Apprentice](Mechanics\bestiary\aberration/derro-apprentice-qftis.md)
*Source: Quests from the Infinite Staircase p. 196*  

Derro who have just begun to discover and control their magic are called apprentices. The magic of a derro apprentice is dangerous and unpredictable.

## Derro

Derro are Underdark dwellers of dubious origin. According to the histories of some duergar, derro are descended from a community of dwarves that was left behind when the others escaped the rule of mind flayers. The mind flayers' psionic power eventually transformed these forsaken dwarves into Aberrations.

You can learn more about derro in*Mordenkainen Presents: Monsters of the Multiverse*.

```statblock
"name": "Derro Apprentice (QftIS)"
"size": "Small"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "[leather armor](Mechanics/items/leather-armor.md)"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"stats":
- !!int "9"
- !!int "14"
- !!int "12"
- !!int "11"
- !!int "5"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
"senses": "darkvision 120 ft., passive Perception 7"
"languages": "Dwarvish, Undercommon"
"cr": "1"
"traits":
- "desc": "The derro casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 11):\n\nAt will: [Message](Mechanics/spells/message.md),\
    \ [Prestidigitation](Mechanics/spells/prestidigitation.md)\n\n1/day: [Charm\
    \ Person](Mechanics/spells/charm-person.md)"
  "name": "Spellcasting"
- "desc": "The derro has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "While in sunlight, the derro has disadvantage on attack rolls."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee or Ranged Spell Attack: +3 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 10 (3d6) damage. Roll a d4 to determine the damage type:\
    \ 1, acid; 2, cold; 3, fire; 4, lightning."
  "name": "Chaos Blast"
- "desc": "Raw arcane magic bursts out from the derro. Each creature within 10 feet\
    \ of it must make a DC 11 Strength saving throw. On a failed save, the creature\
    \ takes 7 (2d6) force damage and has the [prone](Mechanics/Rules/conditions.md#Prone)\
    \ condition. On a successful save, the creature takes half as much damage only."
  "name": "Force Burst (Recharge 4-6)"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Derro%20Apprentice.webp"
```
^statblock