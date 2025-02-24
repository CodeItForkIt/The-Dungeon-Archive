---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/8
- monster/size/huge
- monster/type/construct
aliases: ["Scaladar"]
---
# Scaladar
*Source: Waterdeep: Dungeon of the Mad Mage p. 315*  

Scaladar are constructs created by Trobriand, one of Halaster's apprentices. They move and attack like giant scorpions, grabbing prey with two large pincer claws and delivering a deadly pulse of lightning with their metal stinger tails.

```ad-statblock
title: Scaladar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Scaladar.webp#token)
*Huge construct, Unaligned*

- **Armor Class** 19 (natural armor)
- **Hit Points** 94 (`7d12 + 49`)
- **Speed** 30 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|10 (+0)|25 (+7)| 1 (-5)|12 (+1)| 1 (-5)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** force, lightning, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 8

## Traits

***Lightning Absorption.*** Whenever the scaladar is subjected to lightning damage, it takes no damage, and its sting deals an extra `dice:2d10|noform|avg|text(11)` (`2d10`) lightning damage until the end of its next turn.

***Scaladar Link.*** The scaladar knows the location of other scaladar within 100 feet of it, and it can sense when any of them take damage.

## Actions

***Multiattack.*** The scaladar makes three attacks: two with its claws and one with its sting.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d12+4|noform|avg|text(10)` (`1d12 + 4`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). The scaladar has two claws, each of which can grapple one target.

***Sting.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) lightning damage.
```
^statblock