---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/3
- monster/size/medium
- monster/type/construct
aliases: ["Snow Golem"]
---
# Snow Golem
*Source: Icewind Dale: Rime of the Frostmaiden p. 308*  

A snow golem is a mass of snow brought to life through magic. Nonmagical weapons pass through its snowy form without dealing any appreciable damage to it, though heat is its doom.

```ad-statblock
title: Snow Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Snow%20Golem.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 8
- **Hit Points** 39 (`6d8 + 12`)
- **Speed** 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)| 6 (-2)|14 (+2)| 1 (-5)| 6 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Damage Vulnerabilities** fire
- **Damage Immunities** cold; poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 3

## Traits

***Cold Absorption.*** Whenever the golem is subjected to cold damage, it takes no damage and instead regains a number of hit points equal to the cold damage dealt.

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Melt.*** While in an area of extreme heat, the golem loses `dice:1d6|noform|avg` (`1d6`) hit points at the start of each of its turns.

***Unusual Nature.*** The golem doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The golem makes three melee attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) cold damage.

***Snowball.*** *Ranged Weapon Attack:* `dice:1d20+0|noform|text(+0)` to hit, range 60 ft., one target. *Hit:* `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) cold damage.
```
^statblock