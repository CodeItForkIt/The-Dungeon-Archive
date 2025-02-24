---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/13
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Skyswimmer"]
---
# Skyswimmer
*Source: Guildmasters' Guide to Ravnica p. 220*  

Skyswimmers are enormous, predatory leviathans that feed on drakes, rocs, griffins, and anything else they encounter as they soar through the clouds above Ravnica.

```ad-statblock
title: Skyswimmer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Skyswimmer.webp#token)
*Gargantuan monstrosity, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 216 (`16d20 + 48`)
- **Speed** 10 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|15 (+2)|16 (+3)| 7 (-2)|12 (+1)| 6 (-2)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +8
- **Skills** Perception +6
- **Senses** passive Perception 16
- **Languages** —
- **Challenge** 13

## Traits

***Amphibious.*** The skyswimmer can breathe air and water.

## Actions

***Multiattack.*** The skyswimmer makes three attacks: one with its bite and two with its slam.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Dexterity saving throw or be swallowed by the skyswimmer. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the skyswimmer, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the skyswimmer's turns. If the skyswimmer takes 30 damage or more on a single turn from the swallowed creature, the skyswimmer must succeed on a DC 18 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the skyswimmer. If the skyswimmer dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Slam.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 30 ft., one target. *Hit:* `dice:2d12+6|noform|avg|text(19)` (`2d12 + 6`) bludgeoning damage.
```
^statblock