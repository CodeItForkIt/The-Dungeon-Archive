---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/planar
- monster/size/medium
- monster/type/undead
aliases: ["Deathwisp"]
---
# Deathwisp
*Source: Tome of Beasts 1 (2023 Edition) p. 71*  

*A shadowy figure flickers in and out of view. Its indistinct shape betrays a sylvan ancestry, and its eyes are malevolent blue points of light.*

## Fey Undead

A deathwisp is a wraith-like spirit created in the Shadow Realm from the violent death of a shadow fey or evil fey.

## Rift Walkers

Many deathwisps remain among the shadows, but a few enter the natural world through planar rifts and gates or by walking along the shadowy roads between the worlds. Retaining only a trace of their former personality and knowledge, their lost kindness has been replaced with malice.

## Devour Breath

A deathwisp feasts on the breath of living things, and it invariably seeks to devour animals and solitary, intelligent prey. It is quite intelligent and avoids fights against greater numbers.

## Statblock

```ad-statblock
title: Deathwisp
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Deathwisp.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 15
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|20 (+5)|16 (+3)|18 (+4)|16 (+3)|20 (+5)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +8, Constitution +6, Wisdom +6
- **Skills** Perception +6, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 16
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** the languages it knew in life
- **Challenge** 7

## Traits

***Flicker.*** The deathwisp flickers in and out of sight. Ranged weapon attacks against it are made with disadvantage.

***Incorporeal Movement.*** The deathwisp can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside a solid object.

***Sunlight Sensitivity.*** While in sunlight, the deathwisp has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Undead Nature.*** The deathwisp doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The deathwisp makes two Ghostly Pike attacks, or it can make one Ghostly Pike attack and one Life Drain attack.

***Ghostly Pike.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) force damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage.

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:4d8+5|noform|avg|text(23)` (`4d8 + 5`) necrotic damage. The target must succeed on a DC 15 Constitution saving throw or its hp maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hp maximum to 0.

***Create Specter.*** The deathwisp targets a Humanoid within 10 feet of it that has been dead for no longer than 1 minute and died violently. The target's spirit rises as a specter in the space of its corpse or in the nearest unoccupied space. This specter is under the deathwisp's control. The deathwisp can have no more than twelve specters under its control at one time.

## Bonus Actions

***Shadow Traveler (3/Day).*** While in shadows, dim light, or darkness, the deathwisp disappears into the darkness and reappears in an unoccupied space it can see within 30 feet. A tendril of inky smoke appears at the origin and destination when it uses this bonus action.
```
^statblock

## Environment

planar