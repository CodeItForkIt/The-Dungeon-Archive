---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/arctic
- monster/environment/forest
- monster/size/large
- monster/type/monstrosity
aliases: ["Nightgarm"]
---
# Nightgarm
*Source: Tome of Beasts 1 (2023 Edition) p. 285*  

*This red-furred lupine creature has a too-wide mouth and blood-soaked claws.*

Created in a ritual performed over a pregnant worg, nightgarms are always born female and are followers of the Great Wolf.

## Wide-Jawed Lupines

Nightgarms resemble red-furred worgs with wide mouths, half-formed fingers, and comfort with bipedal and quadrupedal movement. They can hold items in their front paws, and their jaws can open to swallow especially large creatures.

## Mother of Falsehearts

If a nightgarm eats a humanoid corpse whole, it gives birth nine hours later to a duplicate of the victim, known as a falseheart (see the Falseheart Template sidebar). Falsehearts are loyal to the nightgarm that birthed them and retain enough of the victim's memories and capabilities to integrate into society as the victim.

> [!note] Falseheart Template
> 
> The corpse of any Humanoid can become a falseheart if eaten whole by a nightgarm. When a Humanoid becomes a falseheart, it retains its statistics, except as described below.
> 
> **Type.** The Humanoid's type changes to Monstrosity
> 
> **Alignment.** The falseheart's alignment changes to chaotic evil.
> 
> **New Trait Convincing Copy.** A creature very familiar with the Humanoid the falseheart replaced can tell the falseheart is an imitation with a successful DC 20 Wisdom ([Insight](2-Mechanics/CLI/rules/skills.md#Insight)) check.
> 
> **New Trait Keen Smell.** The falseheart has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.
> 
> **New Trait Mother's Love.** The falseheart is magically bound to the nightgarm that birthed it, following the nightgarm's telepathic commands.
^falseheart-template

## Statblock

```ad-statblock
title: Nightgarm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Nightgarm.webp#token)
*Large monstrosity, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 152 (`16d10 + 64`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|18 (+4)|10 (+0)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +5, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Vulnerabilities** radiant; bludgeoning, piercing, slashing by silvered weapons
- **Damage Resistances** lightning, thunder
- **Languages** Common, Giant, Goblin, telepathy 60 ft.
- **Challenge** 6

## Traits

***Telepathic Bond.*** The nightgarm ignores the range restriction on its telepathy when communicating with a falseheart it has birthed. The nightgarm and its falseheart don't need to be on the same plane of existence.

## Actions

***Multiattack.*** The nightgarm makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) piercing damage. If the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or be swallowed. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the nightgarm, and it takes `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage at the start of each of the nightgarm's turns. The nightgarm can have only one creature swallowed at a time. If the nightgarm takes 20 damage or more on a single turn from the swallowed creature, the nightgarm must succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 5 feet of the nightgarm. If the nightgarm dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by her and can escape from the corpse by using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage.

***Lupine Howl (1/Day).*** The nightgarm magically calls `dice:2d4|noform|avg` (`2d4`) wolves or 2 dire wolves. The wolves arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of the nightgarm and obeying her telepathic commands. The wolves remain for 1 hour, until the nightgarm dies, or until the nightgarm dismisses them as a bonus action.
```
^statblock

## Environment

arctic, forest