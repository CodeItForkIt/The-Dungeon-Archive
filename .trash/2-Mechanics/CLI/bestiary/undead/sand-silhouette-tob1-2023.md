---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/desert
- monster/size/medium
- monster/type/undead
aliases: ["Sand Silhouette"]
---
# Sand Silhouette
*Source: Tome of Beasts 1 (2023 Edition) p. 312*  

*A person made of sand emerges from the dune, a sandstorm of wailing souls swirling around it.*

Sand silhouettes are spirits of those who died in desperation in sandy ground, buried during sandstorms, thrown into dry wells, or the victims of a dune collapse.

## Sand Bodies

If disturbed or agitated, these restless souls cause the sand around them to swirl and form into a loose vortex that vaguely resembles their physical body in life. They can control these shapes as they controlled their physical bodies.

## Traceless Movement

Sand silhouettes glide through the sand without leaving a trace or creating any telltale sign of their approach, which makes it easy for them to surprise even cautious travelers with sudden attacks from below.

## Statblock

```ad-statblock
title: Sand Silhouette
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Sand%20Silhouette.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|12 (+1)|17 (+3)| 7 (-2)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., tremorsense 60 ft., passive Perception 11
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** The languages it knew in life
- **Challenge** 6

## Traits

***Sand Camouflage.*** The sand silhouette has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in desert terrain.

***Sand Form.*** The sand silhouette can move through a space as narrow as 1 inch wide without squeezing.

***Sand Glide.*** The sand silhouette can burrow through nonmagical, loose sand without disturbing the material it is moving through.

***Undead Nature.*** The sand silhouette doesn't require air, food, drink, or sleep.

***Water Hypersusceptibility.*** For every 5 feet the sand silhouette moves in water, or for every gallon of water splashed on it, it takes `dice:1d4|noform|avg|text(2)` (`1d4`) cold damage. In addition, the silhouette takes 10 cold damage when it starts its turn at least partially submerged in water.

## Actions

***Multiattack.*** The sand silhouette makes two Slam attacks. If both attacks hit a Medium or smaller target, the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15), and the silhouette uses its Engulf on the target.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) bludgeoning damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) necrotic damage.

***Engulf.*** The sand silhouette engulfs a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The engulfed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and it must succeed on a DC 15 Constitution saving throw at the start of each of the sand silhouette's turns or take `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. If the sand silhouette moves, the engulfed target moves with it. The sand silhouette can have only one creature engulfed at a time.

***Haunted Haboob (3/Day).*** The sand silhouette creates a storm of whirling sand and wailing souls around itself. The storm is a 10-foot radius, 30-foot-tall cylinder centered on the silhouette and moves with the silhouette for 1 minute, until it ends the storm as a bonus action, or until its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) ends (as if concentrating on a spell). The sandstorm's area is lightly obscured, and a creature that starts its turn in the sandstorm's area or enters it for the first time on a turn must succeed on a DC 15 Wisdom saving throw or take `dice:1d6|noform|avg|text(3)` (`1d6`) necrotic damage and be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. An engulfed creature automatically succeeds on this saving throw. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

desert