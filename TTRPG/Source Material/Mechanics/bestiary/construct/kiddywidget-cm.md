---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/1-2
- monster/size/small
- monster/type/construct
statblock: inline
aliases: ["Kiddywidget"]
---
# [Kiddywidget](Mechanics\bestiary\construct/kiddywidget-cm.md)
*Source: Candlekeep Mysteries p. 136*  

A skitterwidget that gives birth to a kiddywidget can't procreate for `3d6` days afterward. Still, given that skitterwidgets are constructs with no natural life span, there is no telling how many kiddywidgets a pair of skitterwidgets can produce.

```statblock
"name": "Kiddywidget (CM)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "15"
"hit_dice": "2d6 + 8"
"stats":
- !!int "6"
- !!int "14"
- !!int "18"
- !!int "1"
- !!int "10"
- !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "lightning, poison"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened),\
  \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60, passive Perception 10"
"languages": "Skitterwidget"
"cr": "1/2"
"traits":
- "desc": "The kiddywidget doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "The kiddywidget makes two attacks: one with its bite and one with its tail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage. If the target is a creature, it is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the kiddywidget (escape DC 8)."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) piercing damage plus 2 (1d4) lightning damage."
  "name": "Tail"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Kiddywidget.webp"
```
^statblock