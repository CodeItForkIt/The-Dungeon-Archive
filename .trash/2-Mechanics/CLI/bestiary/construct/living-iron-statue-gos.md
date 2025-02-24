---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/gos
- monster/cr/5
- monster/size/medium
- monster/type/construct
aliases: ["Living Iron Statue"]
---
# Living Iron Statue
*Source: Ghosts of Saltmarsh p. 241*  

This squat, solid-looking statue, currently guarding the evil cult's treasure in Isle of the Abbey, is made from pure iron. Its hands are shaped into deadly weapons.

```ad-statblock
title: Living Iron Statue
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Living%20Iron%20Statue.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 102 (`12d8 + 48`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|18 (+4)| 6 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** acid
- **Damage Immunities** lightning, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 5

## Traits

***Immutable Form.*** The statue is immune to any spell or effect that would alter its form.

## Actions

***Multiattack.*** The statue makes two attacks: one with its blade and one with its hammer.

***Blade.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage.

***Hammer.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage, and the target is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Whirl (Recharge 5-6).*** The statue can use its action to spin at the waist, targeting creatures of its choice within 10 feet of it. Each target must make a DC 13 Dexterity saving throw, taking `dice:3d10+3|noform|avg|text(19)` (`3d10 + 3`) bludgeoning damage on a failed save, or half as much damage on a successful one.
```
^statblock