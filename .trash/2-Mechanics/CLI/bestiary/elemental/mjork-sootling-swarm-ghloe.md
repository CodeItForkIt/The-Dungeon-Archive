---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/elemental
aliases: ["Mjork Sootling Swarm"]
---
# Mjork Sootling Swarm
*Source: Grim Hollow: Lairs of Etharis p. 72*  

> [!quote]  
> 
> Is it just me, or does the darkness seem thicker? And did it just get really warm in here?

## Salvage

Within every mjork is a heart of ash hardened into smoky crystal. This crystal might already be broken in the remains of a slain mjork, making it useless. An intact crystal can be broken or hurled at a point up to 60 feet away as an action. When it breaks, which it does upon landing if hurled, the crystal releases a 20-foot-radius sphere of sooty smoke, centered on a point in the breaker's space or on the point where the crystal landed. The smoke spreads around corners, and its area is heavily obscured. It lasts for 1 minute, but a moderate wind (at least 10 miles per hour) disperses it in 4 rounds. A strong wind (20 or more miles per hour) disperses the smoke in 1 round. These crystals sell for 15 gp or more each.

The smaller crystals from sootlings or broken mjork crystals are like smoky quartz. These gems can be worth from 1 sp to 1 gp each, or more to collectors who believe they are mjork crystals. Someone who polishes them using jeweler's tools can increase their value as semiprecious stones.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Mjorks are made from earth and fire clashing together. These elementals often dwell near volcanoes.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Mjorks are vulnerable to thunder damage, which cracks their rocky skin. They can also sense through smoke as if the haze provided them blindsight.  

## Statblock

```ad-statblock
title: Mjork Sootling Swarm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Mjork%20Sootling%20Swarm.webp#token)
*Medium elemental, Chaotic Neutral*

- **Armor Class** 12
- **Hit Points** 33 (`6d8 + 6`)
- **Speed** 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|15 (+2)|12 (+1)| 4 (-3)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** thunder
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** understands Ignan and Terran but can't speak
- **Challenge** 2

## Traits

***Hot Soot.*** A creature that ends its turn in the sootling swarm's space takes `dice:2d4|noform|avg|text(5)` (`2d4`) fire damage, or `dice:1d4|noform|avg|text(2)` (`1d4`) fire damage if the swarm has half of its hit points or fewer. The creature must also succeed on a DC 11 Constitution saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and unable to breathe until the end of its next turn.

***Smoke Sense.*** A sootling swarm in contact with smoke has blindsight in that smoke's area in a radius of up to 120 feet.

***Swarm.*** The sootling swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny creature. The swarm can't regain hit points or gain temporary hit points

***Water Susceptibility.*** For every 5 feet the sootling swarm moves in water, or for every gallon of water splashed on it, it takes 2 cold damage.

## Actions

***Burns.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 0 ft., one target in the swarm's space. *Hit:* `dice:4d4|noform|avg|text(10)` (`4d4`) fire damage, or `dice:2d4|noform|avg|text(5)` (`2d4`) fire damage if the swarm has half of its hit points or fewer.
```
^statblock