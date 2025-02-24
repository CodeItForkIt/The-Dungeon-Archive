---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/14
- monster/size/huge
- monster/type/monstrosity
aliases: ["Wurm"]
---
# Wurm
*Source: Guildmasters' Guide to Ravnica p. 225*  

Wurms are huge creatures that resemble limbless, wingless dragons. They burrow through the earth and eat virtually anything they come across, and their movement accounts for much of the destruction in the rubblebelt regions of Ravnica. A wurm burrows through loose earth by using deep sonic vibrations to liquefy the earth in front of it and swim through the area. The soil resolidifies and closes behind it. Moving through rock is slower and more difficult, and the wurm leaves a tunnel in its wake. The Gruul Clans appreciate the devastation wurms can create, and the clans sometimes lure them into civilized areas where the destruction can be vast.

```ad-statblock
title: Wurm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Wurm.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 200 (`16d12 + 96`)
- **Speed** 50 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|10 (+0)|22 (+6)| 3 (-4)|12 (+1)| 4 (-3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +11, Wisdom +6
- **Skills** ⏤
- **Senses** blindsight 60 ft., tremorsense 60 ft., passive Perception 11
- **Languages** —
- **Challenge** 14

## Traits

***Siege Monster.*** The wurm deals double damage to objects and structures.

***Earth Tremors.*** The wurm creates earth tremors as it moves overland or underground. Any creature that comes within 30 feet of the moving wurm for the first time on a turn must succeed on a DC 20 Dexterity saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) bludgeoning damage and fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone). Any structure or object anchored to the ground that comes within 30 feet of the moving wurm for the first time on a turn takes `dice:3d6|noform|avg|text(10)` (`3d6`) force damage.

***Tunneler.*** The wurm can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:5d6+7|noform|avg|text(24)` (`5d6 + 7`) piercing damage. If the target is a Medium or smaller creature, it must succeed on a DC 20 Dexterity saving throw or be swallowed by the wurm. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), has total cover against attacks and other effects outside the wurm, and takes `dice:5d6|noform|avg|text(17)` (`5d6`) acid damage at the start of each of the wurm's turns. If the wurm takes 30 damage or more on a single turn from a creature inside it, the wurm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the wurm. If the wurm dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock