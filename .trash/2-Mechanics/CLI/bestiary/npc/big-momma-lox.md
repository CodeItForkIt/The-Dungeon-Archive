---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/lox
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
aliases: ["Big Momma"]
---
# Big Momma
*Source: Light of Xaryxis p. 29*  

```ad-statblock
title: Big Momma
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LoX/Big%20Momma.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 157 (`15d12 + 60`)
- **Speed** 0 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|16 (+3)|19 (+4)| 4 (-3)|13 (+1)| 5 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +5, Stealth +11
- **Senses** darkvision 120 ft., passive Perception 15
- **Languages** —
- **Challenge** 11

## Traits

***Unusual Nature.*** Big Momma doesn't require air.

## Actions

***Swallowing Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:6d12+6|noform|avg|text(45)` (`6d12 + 6`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 16 Dexterity saving throw or be swallowed by Big Momma. Big Momma can have one creature swallowed at a time.

A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), has total cover against attacks and other effects outside Big Momma, and takes `dice:2d10|noform|avg|text(11)` (`2d10`) acid damage at the start of each of Big Momma's turns from the digestive juices in Big Momma's gullet.

If Big Momma takes 25 damage or more on a single turn from a creature inside it, Big Momma must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate the swallowed creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of Big Momma. If Big Momma dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Bonus Actions

***Ray of Fear (Recharge 4-6).*** Big Momma's eye emits an [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible), magical ray that targets one creature Big Momma can see within 60 feet of itself. The target must succeed on a DC 16 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of Big Momma until the start of Big Momma's next turn.
```
^statblock