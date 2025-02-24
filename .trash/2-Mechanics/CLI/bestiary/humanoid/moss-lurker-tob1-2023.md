---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1
- monster/environment/forest
- monster/environment/underdark
- monster/size/small
- monster/type/humanoid
aliases: ["Moss Lurker"]
---
# Moss Lurker
*Source: Tome of Beasts 1 (2023 Edition) p. 278*  

*Somewhat like the cruel crossbreed of troll and gnome, this creature has a long, greenish beard and hair. Its hide is peaty amber, and a vaguely fungal scent surrounds it.*

Like their trollish relatives, moss lurkers have large, often grotesque noses. Their claws are bright red when unsheathed, and their teeth tend toward the long and snaggly. They wear simple clothes of homespun wool or leather, or go naked in the summer. Their hats are sometimes festooned with toadstools or ferns as primitive camouflage.

## Large Rocks and Poisoned Gifts

Moss lurkers have a fondness for throwing large stones at enemies. Some stones even seem too large for the lurker to heft. They also enjoy poisoning food and drink then offering it to creatures lost in the forest.

## Statblock

```ad-statblock
title: Moss Lurker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Moss%20Lurker.webp#token)
*Small humanoid, Chaotic Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 45 (`10d6 + 10`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|14 (+2)|12 (+1)|12 (+1)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Strength +4, Dexterity +4
- **Skills** Perception +2, Stealth +4
- **Senses** blindsight 60 ft., passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Giant, Sylvan, Trollkin
- **Challenge** 1

## Traits

***Forest Camouflage.*** A moss lurker has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in forested terrain.

***Keen Hearing and Smell.*** The moss lurker has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or smell.

***Poisoned Gifts.*** A moss lurker can spend 1 minute stirring one of its red claws in a drink or cooked meal, contaminating the food or drink. A creature that eats or drinks the contaminated food or drink must succeed on a DC 12 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. A creature that fails this saving throw by 5 or more is also [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. The creature wakes up if it takes damage or if another creature takes an action to shake it awake.

## Actions

***Poisoned Claw.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and the target must succeed on a DC 12 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn.

***Throw Stone.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 20/60 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) bludgeoning damage. If the target is at least 10 feet below the moss lurker, such as at the base of a cliff where the moss lurker stands, the target must succeed on a DC 12 Strength saving throw or take `dice:1d4|noform|avg` (`1d4`) bludgeoning damage for every 10 feet the rock fell before hitting the target, to a maximum of `dice:10d4|noform|avg` (`10d4`).
```
^statblock

## Environment

forest, underdark