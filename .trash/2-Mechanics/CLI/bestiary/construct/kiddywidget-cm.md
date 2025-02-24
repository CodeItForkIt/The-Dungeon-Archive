---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/1-2
- monster/size/small
- monster/type/construct
aliases: ["Kiddywidget"]
---
# Kiddywidget
*Source: Candlekeep Mysteries p. 136*  

A skitterwidget that gives birth to a kiddywidget can't procreate for `dice:3d6|noform|avg` (`3d6`) days afterward. Still, given that skitterwidgets are constructs with no natural life span, there is no telling how many kiddywidgets a pair of skitterwidgets can produce.

```ad-statblock
title: Kiddywidget
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Kiddywidget.webp#token)
*Small construct, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 15 (`2d6 + 8`)
- **Speed** 20 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|14 (+2)|18 (+4)| 1 (-5)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60, passive Perception 10
- **Damage Immunities** lightning, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Skitterwidget
- **Challenge** 1/2

## Traits

***Unusual Nature.*** The kiddywidget doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The kiddywidget makes two attacks: one with its bite and one with its tail.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage. If the target is a creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the kiddywidget (escape DC 8).

***Tail.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage plus `dice:1d4|noform|avg|text(2)` (`1d4`) lightning damage.
```
^statblock