---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/5
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Skitterwidget"]
---
# [Skitterwidget](Mechanics\bestiary\construct/skitterwidget-cm.md)
*Source: Candlekeep Mysteries p. 136*  

A skitterwidget is made of metal and bears a passing resemblance to a giant dog-headed cockroach. No two skitterwidgets look exactly alike, but all are surprisingly cute.

```statblock
"name": "Skitterwidget (CM)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d8 + 40"
"stats":
- !!int "16"
- !!int "14"
- !!int "18"
- !!int "3"
- !!int "10"
- !!int "1"
"speed": "30 ft., climb 30 ft."
"damage_immunities": "lightning, poison"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened),\
  \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Skitterwidget"
"cr": "5"
"traits":
- "desc": "Whenever the skitterwidget is subjected to lightning damage, it takes no\
    \ damage and instead regains a number of hit points equal to the lightning damage\
    \ dealt."
  "name": "Lightning Absorption"
- "desc": "The skitterwidget doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The skitterwidget makes two attacks: one with its bite and one with its\
    \ tail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) piercing damage. If the target is a creature, it is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the skitterwidget (escape DC 13)."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 10 (3d6) lightning damage, and if the target is\
    \ a creature, it must succeed on a DC 15 Constitution saving throw or be [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ until the end of its next turn."
  "name": "Tail"
"reactions":
- "desc": "The skitterwidget imposes disadvantage on one attack roll made against\
    \ a kiddywidget it can see within 5 feet of it."
  "name": "Good Parent"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Skitterwidget.webp"
```
^statblock