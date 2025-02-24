---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xphb
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
aliases: ["Zombie"]
---
# [Zombie](Mechanics/bestiary/undead/zombie-xphb.md)
*Source: Player's Handbook (2024) p. 359*  

```statblock
"name": "Zombie (XPHB)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "8"
"hp": !!int "15"
"hit_dice": "2d8 + 6"
"stats":
- !!int "13"
- !!int "6"
- !!int "16"
- !!int "3"
- !!int "6"
- !!int "5"
"speed": "20 ft."
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/rules/conditions.md#Exhaustion), [poisoned](Mechanics/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands the languages it knew in life but can't speak"
"cr": "1/4"
"traits":
- "desc": "If damage reduces the zombie to 0 Hit Points, it must make a Constitution\
    \ saving throw with a DC of 5 plus the damage taken unless the damage is Radiant\
    \ or from a Critical Hit. On a successful save, the zombie drops to 1 Hit Point\
    \ instead."
  "name": "Undead Fortitude"
"actions":
- "desc": "Melee Attack: +3, reach 5 ft. Hit: 4 (1d6 + 1) Bludgeoning damage."
  "name": "Slam"
"source":
- "XPHB"
"image": "Mechanics/bestiary/undead/token/zombie-xphb.webp"
```
^statblock