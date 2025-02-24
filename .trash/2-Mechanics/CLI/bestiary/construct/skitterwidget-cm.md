---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/5
- monster/size/medium
- monster/type/construct
aliases: ["Skitterwidget"]
---
# Skitterwidget
*Source: Candlekeep Mysteries p. 136*  

A skitterwidget is made of metal and bears a passing resemblance to a giant dog-headed cockroach. No two skitterwidgets look exactly alike, but all are surprisingly cute.

```ad-statblock
title: Skitterwidget
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Skitterwidget.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 85 (`10d8 + 40`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|18 (+4)| 3 (-4)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** lightning, poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Skitterwidget
- **Challenge** 5

## Traits

***Lightning Absorption.*** Whenever the skitterwidget is subjected to lightning damage, it takes no damage and instead regains a number of hit points equal to the lightning damage dealt.

***Unusual Nature.*** The skitterwidget doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The skitterwidget makes two attacks: one with its bite and one with its tail.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage. If the target is a creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the skitterwidget (escape DC 13).

***Tail.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) lightning damage, and if the target is a creature, it must succeed on a DC 15 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.

## Reactions

***Good Parent.*** The skitterwidget imposes disadvantage on one attack roll made against a kiddywidget it can see within 5 feet of it.
```
^statblock