---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/6
- monster/size/huge
- monster/type/aberration
aliases: ["Protean Abomination"]
---
# Protean Abomination
*Source: Dungeons of Drakkenheim p. 201*  

Occasionally, a creature's rapid mutations become too much for its body to withstand. In a horrific shower of gore, such wretches explode into a quivering mass of cancerous tumors, babbling mouths, shifting eyes, and grasping limbs that twist, expand, and retract in grotesque and bizarre ways.

```ad-statblock
title: Protean Abomination
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Protean%20Abomination.webp#token)
*Huge aberration, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 168 (`16d12 + 64`)
- **Speed** 30 ft., climb 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)| 8 (-1)|18 (+4)| 5 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft., passive Perception 10
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 6

## Traits

***Absorption.*** When the protean abomination kills a creature that is neither a construct nor undead, it absorbs the corpse into its body and regains 20 hit points.

***Amorphous.*** The protean abomination can move through a space as narrow as 1 inch wide without squeezing.

***Spider Climb.*** The protean abomination can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The protean abomination makes two slam attacks. If both attacks hit a Large or smaller target, the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15), and the protean abomination uses Engulf on it.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(19)` (`3d8 + 5`) bludgeoning damage.

***Engulf.*** The protean abomination engulfs a Large or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. Until the grapple ends the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and unable to breathe, and it must succeed on a DC 15 Constitution saving throw at the start of each of the abomination's turns or take `dice:3d8+5|noform|avg|text(19)` (`3d8 + 5`) bludgeoning damage. If the abomination moves, the engulfed target moves with it. The abomination can have only one creature engulfed at a time.
```
^statblock