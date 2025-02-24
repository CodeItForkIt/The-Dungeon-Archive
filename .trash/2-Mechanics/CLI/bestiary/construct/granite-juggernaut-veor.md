---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/12
- monster/size/large
- monster/type/construct
aliases: ["Granite Juggernaut"]
---
# Granite Juggernaut
*Source: Vecna: Eve of Ruin p. 221*  

> [!quote] A quote from Teythorn, Oerthian Adventurer  
> 
> If you're close enough to see the expression carved onto a granite juggernaut's face, you're as good as dead.

A granite juggernaut is a lumbering Construct that can be found trundling across battlefields and down dungeon corridors. Granite juggernauts have dense, boxy bodies atop massive rollers they use for locomotion. Their fronts and rollers are often adorned with fearsome heads, such as those of enraged rhinos. Granite juggernauts are found on many worlds and typically are used to protect high-value locations.

```ad-statblock
title: Granite Juggernaut
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Granite%20Juggernaut.webp#token)
*Large construct, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 157 (`15d10 + 75`)
- **Speed** 30 ft. (in a straight line)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)| 1 (-5)|20 (+5)| 2 (-4)|11 (+0)| 3 (-4)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 120 ft., passive Perception 10
- **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 12

## Traits

***Magic Resistance.*** The juggernaut has advantage on saving throws against spells and other magical effects.

***Siege Monster.*** The juggernaut deals double damage to objects and structures.

## Actions

***Slam.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+6|noform|avg|text(11)` (`1d10 + 6`) bludgeoning damage, and if the target is a Large or smaller creature, it must succeed on a DC 18 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

## Bonus Actions

***Devastating Roll.*** The juggernaut moves up to its speed. During this movement, the juggernaut can move through the spaces of creatures with the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. When the juggernaut enters the space of a [prone](2-Mechanics/CLI/rules/conditions.md#Prone) creature for the first time during this movement, the creature must make a DC 18 Dexterity saving throw, taking `dice:10d10|noform|avg|text(55)` (`10d10`) bludgeoning damage on a failed save or half as much damage on a successful one.
```
^statblock