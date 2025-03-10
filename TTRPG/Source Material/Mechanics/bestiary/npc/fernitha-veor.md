---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/12
- monster/size/medium
- monster/type/fiend/devil
statblock: inline
aliases: ["Fernitha"]
---
# [Fernitha](Mechanics\bestiary\npc/fernitha-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Fernitha (VEoR)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md)"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"stats":
- !!int "18"
- !!int "16"
- !!int "18"
- !!int "14"
- !!int "14"
- !!int "18"
"speed": "30 ft., fly 60 ft."
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "7"
  "Wisdom": !!int "6"
  "Constitution": !!int "8"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 12"
"languages": "Infernal, telepathy 120 ft."
"cr": "12"
"traits":
- "desc": "Fernitha's weapon attacks are magical and deal an extra 13 (3d8) poison\
    \ damage on a hit (included in the attacks)."
  "name": "Hellish Weapons"
- "desc": "Fernitha has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Fernitha makes three attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands,\
    \ plus 13 (3d8) poison damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage plus 13 (3d8) poison damage, and the target\
    \ must succeed on a DC 14 Constitution saving throw or be [poisoned](Mechanics/Rules/conditions.md#Poisoned).\
    \ The poison lasts until it is removed by the [lesser restoration](Mechanics/spells/lesser-restoration.md)\
    \ spell or similar magic."
  "name": "Longbow"
"reactions":
- "desc": "Fernitha adds 4 to its AC against one melee attack that would hit it. To\
    \ do so, Fernitha must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "VEoR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Fernitha.webp"
```
^statblock