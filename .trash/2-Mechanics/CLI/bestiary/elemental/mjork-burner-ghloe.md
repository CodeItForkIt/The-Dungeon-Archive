---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/6
- monster/size/large
- monster/type/elemental
aliases: ["Mjork Burner"]
---
# Mjork Burner
*Source: Grim Hollow: Lairs of Etharis p. 71*  

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
title: Mjork Burner
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Mjork%20Burner.webp#token)
*Large elemental, Chaotic Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 95 (`10d10 + 40`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|15 (+2)|18 (+4)| 7 (-2)|12 (+1)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Vulnerabilities** thunder
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Ignan, Terran
- **Challenge** 6

## Traits

***Fiery Body.*** A creature that touches the mjork burner or hits it with a melee attack while within 5 feet of it takes `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

***Fire Path.*** The mjork burner leaves fire behind in any space it moves through. Until the start of the mjork's next turn, any creature that enters this area for the first time on a turn or ends its turn there takes `dice:2d4|noform|avg|text(5)` (`2d4`) fire damage. The fire can ignite flammable objects (not creatures), causing the mjork's Fire Path to last longer.

***Ignite.*** A creature or flammable object ignites if it takes fire damage from the mjork burner's attacks. Until a creature takes an action to douse this fire, the target takes `dice:2d4|noform|avg|text(5)` (`2d4`) fire damage at the start of each of its turns.

***Illumination.*** The mjork burner sheds bright light in a 10-foot radius and dim light for another 10 feet.

***Smoke Sense.*** A mjork burner in contact with smoke has blindsight in that smoke's area in a radius of up to 120 feet.

***Water Susceptibility.*** For every 5 feet the mjork burner moves in water, or for every gallon of water splashed on it, it takes 1 cold damage.

## Actions

***Multiattack.*** The mjork burner makes two attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) bludgeoning damage, `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage, and Ignite.

***Hurl Fire.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, ranged 30/60 ft., one target. *Hit:* `dice:3d6+3|noform|avg|text(13)` (`3d6 + 3`) fire damage and Ignite.
```
^statblock