---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/1
- monster/size/small
- monster/type/construct
statblock: inline
aliases: ["Tin Soldier"]
---
# [Tin Soldier](Mechanics\bestiary\construct/tin-soldier-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 115*  

These automatons are fashioned to look like stout infantry soldiers, and they obey Skabatha without question. They charge forth to investigate any suspicious activity they see or hear, meaning that they are easily distracted.

```statblock
"name": "Tin Soldier (WBtW)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "6d6 + 6"
"stats":
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "1"
- !!int "3"
- !!int "1"
"speed": "25 ft."
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [deafened](Mechanics/Rules/conditions.md#Deafened), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "1"
"traits":
- "desc": "The tin soldier is incapacitated while in the area of an [antimagic field](Mechanics/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](Mechanics/spells/dispel-magic.md), the tin soldier\
    \ must succeed on a Constitution saving throw against the caster's spell save\
    \ DC or fall unconscious for 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While the tin soldier remains motionless, it is indistinguishable from\
    \ a normal suit of armor."
  "name": "False Appearance"
"actions":
- "desc": "The tin soldier makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Slam"
"source":
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Tin%20Soldier.webp"
```
^statblock