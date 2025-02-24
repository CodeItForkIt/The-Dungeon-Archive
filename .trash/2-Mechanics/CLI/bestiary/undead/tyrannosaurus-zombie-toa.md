---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/8
- monster/size/huge
- monster/type/undead
aliases: ["Tyrannosaurus Zombie"]
---
# Tyrannosaurus Zombie
*Source: Tomb of Annihilation p. 241*  

Several new zombie variants are presented below. For more information on zombies, see the Monster Manual.

## Ankylosaurus Zombie

This creature is slow and barely aware of its surroundings.

## Girallon Zombie

Girallons are four-armed apes with white fur. Girallon zombies are slower than their non-undead counterparts but no less fierce. The necromantic energy empowering them fuels their murderous hearts and their hunger for living flesh.

## Tyrannosaurus Zombie

A tyrannosaurus zombie has a gullet full of smaller zombies, which it can disgorge. These zombies aren't under the tyrannosaurus zombie's control.

## Statblock

```ad-statblock
title: Tyrannosaurus Zombie
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Tyrannosaurus%20Zombie.webp#token)
*Huge undead, Unaligned*

- **Armor Class** 11 (natural armor)
- **Hit Points** 136 (`13d12 + 52`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)| 6 (-2)|19 (+4)| 1 (-5)| 3 (-4)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 6
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 8

## Traits

***Disgorge Zombie.*** As a bonus action, the tyrannosaurus zombie can disgorge a normal [zombie](2-Mechanics/CLI/bestiary/undead/zombie.md), which appears in an unoccupied space within 10 feet of it. The disgorged [zombie](2-Mechanics/CLI/bestiary/undead/zombie.md) acts on its own initiative count. After a zombie is disgorged, roll a `dice:d6|noform|avg` (`d6`). On a roll of 1, the tyrannosaurus zombie runs out of zombies to disgorge and loses this trait. If the tyrannosaurus zombie still has this trait when it dies, `dice:1d4|noform|avg` (`1d4`) normal zombies erupt from its corpse at the start of its next turn. These zombies act on their own initiative count.

***Undead Fortitude.*** If damage reduces the tyrannosaurus zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5+the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

## Actions

***Multiattack.*** The tyrannosaurus zombie makes two attacks: one with its bite and one with its tail. It can't make both attacks against the same target.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:4d12+7|noform|avg|text(33)` (`4d12 + 7`) piercing damage. If the target is a Medium or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and the tyrannosaurus zombie can't bite another target or disgorge zombies.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) bludgeoning damage.
```
^statblock