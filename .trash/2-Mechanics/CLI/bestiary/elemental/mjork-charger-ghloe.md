---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/7
- monster/size/large
- monster/type/elemental
aliases: ["Mjork Charger"]
---
# Mjork Charger
*Source: Grim Hollow: Lairs of Etharis p. 70*  

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
title: Mjork Charger
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Mjork%20Charger.webp#token)
*Large elemental, Chaotic Neutral*

- **Armor Class** 13 (natural armor)
- **Hit Points** 104 (`11d10 + 44`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|11 (+0)|18 (+4)| 6 (-2)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** thunder
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Ignan, Terran
- **Challenge** 7

## Traits

***Charge.*** If the mjork charger moves at least 20 feet straight toward a target and then hits it with a slam attack on the same turn, the target takes an extra `dice:1d8|noform|avg|text(4)` (`1d8`) bludgeoning damage and `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Fiery Body.*** A creature that touches the mjork charger or hits it with a melee attack while within 5 feet of it takes `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

***Illumination.*** The mjork charger sheds dim light in a 10-foot radius.

***Momentum.*** If the mjork charger moves on its turn before attacking, creatures have disadvantage on attack rolls for opportunity attacks against it.

***Smoke Sense.*** A mjork charger in contact with smoke has blindsight in that smoke's area in a radius of up to 120 feet.

***Water Susceptibility.*** For every 5 feet the mjork charger moves in water, or for every gallon of water splashed on it, it takes 1 cold damage.

## Actions

***Multiattack.*** The mjork makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage and `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.
```
^statblock