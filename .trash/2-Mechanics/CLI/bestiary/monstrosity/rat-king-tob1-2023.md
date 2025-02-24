---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/urban
- monster/size/medium
- monster/type/monstrosity
aliases: ["Rat King"]
---
# Rat King
*Source: Tome of Beasts 1 (2023 Edition) p. 300*  

*A great knot of scabrous rats scrabbles together as a mass, with skulls, bones, and flesh entangled in the whole. Teeth, eyes, and fur all flow as a single disturbing rat swarm walking on two legs.*

## Fused at the Tail

A rat king forms when dozens of rats twist their tails together in a thick knot of bone and lumpy cartilage—and offer praise to the rat demon Chittr'k'k (see*Creature Codex*). Its numbers and powers grow quickly

## Rule Sewers and Slums

The rat king is a cunning creature that stalks city sewers, boneyards, and slums. Some even command entire thieves' guilds or hordes of beggars that give it obeisance. They grow larger and more powerful over time until discovered.

## Plague and Dark Magic

The rat king is the result of plague infused with twisted magic, and a malignant ceremony that creates one is called "Enthroning the Rat King." Rats afflicted with virulent leavings of dark magic rites or twisted experiments become bound to one another. As more rats add to the mass, the creature's intelligence and force of will grow.

## Statblock

```ad-statblock
title: Rat King
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Rat%20King.webp#token)
*Medium monstrosity, Chaotic Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 76 (`9d8 + 36`)
- **Speed** 30 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|16 (+3)|18 (+4)|11 (+0)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Stealth +6
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Common, Thieves' cant
- **Challenge** 5

## Traits

***Keen Smell.*** The rat king has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Plague of Ill Omen.*** The rat king radiates a magical aura of misfortune. A creature that starts its turn within 15 feet of the rat king must succeed on a DC 14 Charisma saving throw or have disadvantage on attack rolls and saving throws until the start of its next turn.

## Actions

***Multiattack.*** The rat king makes two Bite attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or suffer one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) and become infected with a disease. Until the disease is cured, at the end of each long rest, the creature must repeat the saving throw. On a failure, the creature suffers another level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). The [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) lasts until the creature finishes a long rest after the disease is cured. A creature that succeeds on two saving throws recovers from the disease.

***Call Rats (1/Day).*** The rat king magically calls `dice:2d4|noform|avg` (`2d4`) rats, `dice:1d4|noform|avg` (`1d4`) giant rats, or 1 swarm of rats. The rats arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of the rat king and obeying its spoken commands. The rats remain for 1 hour, until the rat king dies, or until the rat king dismisses them as a bonus action.

## Reactions

***Absorption.*** When a friendly rat, giant rat, or swarm of rats starts its turn within 5 feet of the rat king, the rat king can absorb it. If the rat king does so, the target dies, and the rat king gains temporary hp equal to the target's remaining hp.
```
^statblock

## Environment

urban