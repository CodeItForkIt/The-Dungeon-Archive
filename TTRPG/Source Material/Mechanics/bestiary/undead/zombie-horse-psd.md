---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psd
- monster/cr/1-4
- monster/size/large
- monster/type/undead
statblock: inline
aliases: ["Zombie Horse"]
---
# [Zombie Horse](Mechanics\bestiary\undead/zombie-horse-psd.md)
*Source: Plane Shift: Dominaria p. 17*  

```statblock
"name": "Zombie Horse (PSD)"
"size": "Large"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"stats":
- !!int "13"
- !!int "6"
- !!int "16"
- !!int "3"
- !!int "6"
- !!int "5"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands all languages it spoke in life but can't speak"
"cr": "1/4"
"traits":
- "desc": "If damage reduces the zombie to 0 hit points, it must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
    \ or from a critical hit. On a success, the zombie drops to 1 hit point instead."
  "name": "Undead Fortitude"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage."
  "name": "Slam"
"source":
- "PSD"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSD/Zombie%20Horse.webp"
```
^statblock