---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/8
- monster/size/gargantuan
- monster/type/beast
aliases: ["Sperm Whale"]
---
# Sperm Whale
*Source: Icewind Dale: Rime of the Frostmaiden p. 309*  

Sperm whales are toothed aquatic mammals that can grow to be up to 70 feet long. Their natural predators include whalers and fellow leviathans, such as dragon turtles and krakens.

```ad-statblock
title: Sperm Whale
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Sperm%20Whale.webp#token)
*Gargantuan beast, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 189 (`14d20 + 42`)
- **Speed** 0 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)| 8 (-1)|17 (+3)| 3 (-4)|12 (+1)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 120 ft., passive Perception 11
- **Languages** —
- **Challenge** 8

## Traits

***Echolocation.*** The whale can't use its blindsight while [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened).

***Hold Breath.*** The whale can hold its breath for 90 minutes.

***Keen Hearing.*** The whale has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing.

## Actions

***Multiattack.*** The whale makes two attacks: one with its bite and one with its tail.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+8|noform|avg|text(21)` (`3d8 + 8`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 14 Dexterity saving throw or be swallowed by the whale. A swallowed creature has total cover against attacks and other effects outside the whale, and it takes `dice:1d6|noform|avg|text(3)` (`1d6`) acid damage at the start of each of the whale's turns. If the whale takes 30 damage or more on a single turn from a creature inside it, the whale must succeed on a DC 16 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the whale. If the whale dies, a swallowed creature can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tail.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 15 ft., one target. *Hit:* `dice:3d6+8|noform|avg|text(18)` (`3d6 + 8`) bludgeoning damage, or `dice:6d6+16|noform|avg|text(37)` (`6d6 + 16`) bludgeoning damage if the target is an object.
```
^statblock