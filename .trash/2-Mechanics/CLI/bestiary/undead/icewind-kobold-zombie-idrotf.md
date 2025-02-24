---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/1-8
- monster/size/small
- monster/type/undead
aliases: ["Icewind Kobold Zombie"]
---
# Icewind Kobold Zombie
*Source: Icewind Dale: Rime of the Frostmaiden p. 297*  

The necromancer Vellynne Harpell has Icewind kobold guides in her employ, including a pair that died and were turned into zombies using [animate dead](2-Mechanics/CLI/spells/animate-dead.md) spells. The cold climate helps to preserve their dead flesh.

```ad-statblock
title: Icewind Kobold Zombie
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Icewind%20Kobold%20Zombie.webp#token)
*Small undead, Neutral Evil*

- **Armor Class** 9 (scraps of hide armor)
- **Hit Points** 19 (`3d6 + 9`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)| 6 (-2)|16 (+3)| 3 (-4)| 6 (-2)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +0
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 8
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common and Draconic but can't speak
- **Challenge** 1/8

## Traits

***Undead Fortitude.*** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.

***Unusual Nature.*** The zombie doesn't require air, food, drink, or sleep.

## Actions

***Javelin.*** *Melee Weapon Attack:* `dice:1d20+1|noform|text(+1)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6-1|noform|avg|text(2)` (`1d6 - 1`) piercing damage.
```
^statblock