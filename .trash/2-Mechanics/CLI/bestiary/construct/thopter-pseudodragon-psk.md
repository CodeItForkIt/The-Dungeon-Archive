---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/1-4
- monster/size/tiny
- monster/type/construct
aliases: ["Thopter (Pseudodragon)"]
---
# Thopter (Pseudodragon)
*Source: Plane Shift: Kaladesh p. 33*  

Thopters are small automatons that fly using some combination of whirling rotors and stretched-fabric wings. They are ubiquitous in Ghirapur and other settlements, where they carry messages like carrier pigeons, hunt gremlins like trained hawks, race each other in friendly and not-so-friendly competitions—and serve as remote viewing devices for Consulate authorities and crime lords alike. Thopters range from the size of pigeons to the size of eagles, with extremely intricate gearwork usually partly visible beneath glass orbs and filigree.

Different kinds of thopters could be represented by the statistics for a [bat](2-Mechanics/CLI/bestiary/beast/bat.md), [blood hawk](2-Mechanics/CLI/bestiary/beast/blood-hawk.md), [eagle](2-Mechanics/CLI/bestiary/beast/eagle.md), [hawk](2-Mechanics/CLI/bestiary/beast/hawk.md), [owl](2-Mechanics/CLI/bestiary/beast/owl.md), [pseudodragon](2-Mechanics/CLI/bestiary/dragon/pseudodragon.md), [raven](2-Mechanics/CLI/bestiary/beast/raven.md), or [vulture](2-Mechanics/CLI/bestiary/beast/vulture.md) from the "Monster Manual". All thopters have the construct type, immunity to poison damage, and immunity to the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) conditions.

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

## Statblock

```ad-statblock
title: Thopter (Pseudodragon)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Thopter%20%28Pseudodragon%29.webp#token)
*Tiny construct, Neutral Good*

- **Armor Class** 13
- **Hit Points** 7 (`2d4 + 2`)
- **Speed** 15 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|15 (+2)|13 (+1)|10 (+0)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +4
- **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 13
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common and Draconic but can't speak
- **Challenge** 1/4

## Traits

***Keen Senses.*** The thopter has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight, hearing, or smell.

***Magic Resistance.*** The thopter has advantage on saving throws against spells and other magical effects.

***Limited Telepathy.*** The thopter can magically communicate simple ideas, emotions, and images telepathically with any creature within 100 feet of it that can understand a language.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage.

***Sting.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage, and the target must succeed on a DC 11 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. If the saving throw fails by 5 or more, the target falls [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for the same duration, or until it takes damage or another creature uses an action to shake it awake.
```
^statblock