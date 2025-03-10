---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/8
- monster/size/large
- monster/type/giant
statblock: inline
aliases: ["Nivix Cyclops"]
---
# [Nivix Cyclops](Mechanics\bestiary\giant/nivix-cyclops-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 216*  

Cyclopes like those described in the Monster Manual are found primarily among the Gruul Clans. They are forces of nature, and even though they have occasionally been recruited into the Boros Legion, they can never truly be tamed.

Cyclopes serve the Izzet league as workshop guardians, personal protectors, and heavy laborers. They wear mizzium armor plating to minimize injuries from laboratory mishaps, piston gauntlets to increase their strength for lifting and punching, and telescopic helmets to minimize the shortcomings of their monocular vision. They are sometimes called monoclons or Nivix cyclopes, after the name of the Izzet guildhall.

```statblock
"name": "Nivix Cyclops (GGR)"
"size": "Large"
"type": "giant"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "[half plate armor](Mechanics/items/half-plate-armor.md)"
"hp": !!int "115"
"hit_dice": "10d10 + 60"
"stats":
- !!int "24"
- !!int "9"
- !!int "22"
- !!int "7"
- !!int "10"
- !!int "9"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Constitution": !!int "9"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Giant"
"cr": "8"
"traits":
- "desc": "The cyclops has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The cyclops makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 23\
    \ (3d10 + 7) bludgeoning damage."
  "name": "Slam"
"reactions":
- "desc": "Immediately after a creature casts a spell of 1st level or higher within\
    \ 120 feet of the cyclops, the cyclops can move up to twice its speed without\
    \ provoking opportunity attacks. It can then make one slam attack against a target\
    \ of its choice."
  "name": "Spell Vitalization"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Nivix%20Cyclops.webp"
```
^statblock