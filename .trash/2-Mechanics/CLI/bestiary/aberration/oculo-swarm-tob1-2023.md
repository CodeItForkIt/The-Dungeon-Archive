---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/any
- monster/environment/urban
- monster/size/large
- monster/type/aberration
aliases: ["Oculo Swarm"]
---
# Oculo Swarm
*Source: Tome of Beasts 1 (2023 Edition) p. 288*  

*This collection of hundreds of eyes floats along, trailing ganglia and dripping caustic fluid that sizzles when it hits the ground.*

## Failed Experiment

Oculo swarms came about from failed experiments to create living scrying sensors. Once set loose, these horrors attain a form of distributed self-awareness. Exactly what motivates them is unknown, except that they are driven to survive.

## Flesh Stealers

A weakened oculo swarm can reinvigorate itself by tearing fresh eyes from almost any type of living creature. If a badly depleted oculo swarm escapes from battle, it attacks lone creatures or weak groups until the mass of gore-spattered eyeballs is replenished. The more dismembered eyeballs the swarm contains, the more powerful it becomes.

## Single Eye Scouts

The entire swarm sees what any single member sees. Before attacking or even entering a potentially dangerous area, individual eyes scout ahead for prospective victims or dangerous foes. Though harmless and easily destroyed, these lone eyes provide plenty of information to the oculo swarm before perishing.

> [!note] Oculo Swarms in Midgard
> 
> Bemmean wizards have been known to employ oculo swarms as lie detectors during negotiations. An oculo instinctively reads eye movements, and it can communicate what it sees to the wizard by moving in a specific way or by changing the color of its irises. If negotiations go poorly, the mage gives the swarm permission to add a fresh pair of eyes to its number.
^oculo-swarms-in-midgard

## Statblock

```ad-statblock
title: Oculo Swarm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Oculo%20Swarm.webp#token)
*Large aberration, Neutral Evil*

- **Armor Class** 15
- **Hit Points** 82 (`11d10 + 22`)
- **Speed** 5 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|20 (+5)|14 (+2)| 8 (-1)|15 (+2)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Insight +6, Perception +6, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 16
- **Damage Resistances** bludgeoning, piercing, slashing
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** understands Common but can't speak
- **Challenge** 4

## Traits

***Hundreds of Eyes.*** The oculo swarm has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight and on saving throws against being [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded). In addition, if the swarm isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), creatures attacking it can't benefit from traits and features that rely on a creature's allies distracting or surrounding the swarm, such as the Pack Tactics trait or Sneak Attack class feature.

***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny eyeball. The swarm can't regain hp or gain temporary hp.

## Actions

***Multiattack.*** The oculo swarm makes two Extract Eye attacks. If both attacks hit one creature, the target must succeed on a DC 13 Strength saving throw or the swarm removes one of its eyes. While missing half or fewer of its total number of eyes, the target has disadvantage on attack rolls and Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight. While missing more than half its total number of eyes, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until its sight is restored. If the target's eye is recovered from the defeated swarm, it can be reattached with a successful DC 12 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check, provided the eye is reattached within 1 hour of the target losing the eye.

***Extract Eye.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 0 ft., one creature in the swarm's space. *Hit:* `dice:4d8|noform|avg|text(18)` (`4d8`) piercing damage, or `dice:2d8|noform|avg|text(9)` (`2d8`) piercing damage if the swarm has half of its hp or fewer.

***Disorienting Gaze (Recharge 5-6).*** The swarm's many eyes suddenly turn in different directions. Each creature within 10 feet of the oculo swarm must make a DC 13 Charisma saving throw. On a failure, a creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage and is disoriented until the end of its next turn. On a success, a creature takes half the damage and isn't disoriented. A disoriented creature is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and moves in a random direction when it moves.
```
^statblock

## Environment

any, urban