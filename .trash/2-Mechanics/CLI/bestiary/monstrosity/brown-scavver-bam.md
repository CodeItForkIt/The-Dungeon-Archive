---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/4
- monster/size/large
- monster/type/monstrosity
aliases: ["Brown Scavver"]
---
# Brown Scavver
*Source: Boo's Astral Menagerie p. 49, Light of Xaryxis*  

Brown scavvers are 10 feet long and range in color from sun-dappled brownish gold to dark umber. It takes them days to digest a meal, during which time they attack only in self-defense.

A brown scavver likes to swallow its prey whole. The creature's stomach is filled with poisonous gas, which kills off anything that survives being swallowed.

```ad-statblock
title: Brown Scavver
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Brown%20Scavver.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 51 (`6d10 + 18`)
- **Speed** 0 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|17 (+3)| 1 (-5)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Languages** —
- **Challenge** 4

## Traits

***Unusual Nature.*** The scavver doesn't require air.

## Actions

***Swallowing Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage. If the target is a Medium or smaller creature, it must succeed on a DC 13 Dexterity saving throw or be swallowed by the scavver. The scavver can have one creature swallowed at a time.

A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), has total cover against attacks and other effects outside the scavver, and takes `dice:3d8|noform|avg|text(13)` (`3d8`) poison damage at the start of each of the scavver's turns from the poisonous gas in the scavver's gullet.

If the scavver takes 15 damage or more on a single turn from a creature inside it, the scavver must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate the swallowed creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the scavver. If the scavver dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock