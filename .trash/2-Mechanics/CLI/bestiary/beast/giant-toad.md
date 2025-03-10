---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/1
- monster/environment/coastal
- monster/environment/desert
- monster/environment/forest
- monster/environment/swamp
- monster/environment/underdark
- monster/size/large
- monster/type/beast
aliases: ["Giant Toad"]
---
# Giant Toad
*Source: Monster Manual p. 329, Waterdeep: Dungeon of the Mad Mage, Ghosts of Saltmarsh, Explorer's Guide to Wildemount, Tasha's Cauldron of Everything, The Wild Beyond the Witchlight, Keys from the Golden Vault, Quests from the Infinite Staircase. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```ad-statblock
title: Giant Toad
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Giant%20Toad.webp#token)
*Large beast, Unaligned*

- **Armor Class** 11
- **Hit Points** 39 (`6d10 + 6`)
- **Speed** 20 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|13 (+1)|13 (+1)| 2 (-4)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 30 ft., passive Perception 10
- **Languages** —
- **Challenge** 1

## Traits

***Amphibious.*** The toad can breathe air and water.

***Standing Leap.*** The toad's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) piercing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) poison damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the toad can't bite another target.

***Swallow.*** The toad makes one bite attack against a Medium or smaller target it is grappling. If the attack hits, the target is swallowed, and the grapple ends. The swallowed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the toad, and it takes `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage at the start of each of the toad's turns. The toad can have only one target swallowed at a time.

If the toad dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

underdark, forest, swamp, desert, coastal