---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/5
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Cavalier"]
---
# [Cavalier](Mechanics\bestiary\humanoid/cavalier-dodk.md)
*Source: Dungeons of Drakkenheim p. 218*  

These righteous knights take to battle upon heavily armoured steeds or winged griffons.

```statblock
"name": "Cavalier (DoDk)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "19"
"ac_class": "[splint](Mechanics/items/splint-armor.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"stats":
- !!int "18"
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "15"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "4"
"skillsaves":
  "Athletics": !!int "7"
  "Animal Handling": !!int "4"
  "Perception": !!int "4"
  "Persuasion": !!int "5"
"senses": "passive Perception 14"
"languages": "Any two"
"cr": "5"
"traits":
- "desc": "The cavalier is an 8th-level spellcaster that uses Charisma as its spellcasting\
    \ ability (spell save DC 13; +5 to hit with spell attacks). They have the following\
    \ paladin spells prepared:\n\n1st level (4 slots): [bless](Mechanics/spells/bless.md),\
    \ [command](Mechanics/spells/command.md), [cure wounds](Mechanics/spells/cure-wounds.md)\n\
    \n2nd level (3 slots): [branding smite](Mechanics/spells/branding-smite.md),\
    \ [find steed](Mechanics/spells/find-steed.md)"
  "name": "Spellcasting"
- "desc": "The cavalier has advantage on saving throws against being [frightened](Mechanics/Rules/conditions.md#Frightened)."
  "name": "Bravery"
- "desc": "The cavalier deals an extra 9 (2d8) radiant damage when it hits with\
    \ a weapon attack."
  "name": "Light's Fury"
- "desc": "While mounted, the cavalier may force an attack targeted at their mount\
    \ to target them instead."
  "name": "Skilled Rider"
"actions":
- "desc": "The cavalier makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit (with disadvantage against a target\
    \ within 5 ft.), reach 10 ft., one target. Hit: 10 (1d12 + 4) piercing damage\
    \ plus 9 (2d8) radiant damage."
  "name": "Lance"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 30/120\
    \ ft., one target Hit: 7 (1d6 + 4) piercing damage plus 9 (2d8) radiant\
    \ damage."
  "name": "Javelin"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Cavalier.webp"
```
^statblock