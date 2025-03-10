---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/12
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Ayperobo Swarm"]
---
# Ayperobo Swarm
*Source: Chains of Asmodeus p. 238*  

An individual ayperobo is practically harmless, and often eaten by larger devils as a delicacy. Recognizing their weakness, ayperobos gather together and create colonies that communicate using telepathy. These swarms are much stronger, capable of holding their own even against some of the greater devils.

## Something to Prove

Their perfect communication and collective strength, coupled with their ability for flight, allow the ayperobos to easily complete tasks with which larger devils struggle. They're happy to do so, as their goal is to prove their worth and, when possible, get revenge for their abusive treatment at the hands of larger devils.

## Small but Deadly

Each member of the swarm appears as a small, devilish being, with oversized heads and sparrow-like wings. Their teeth are razor sharp, and when working together in a swarm, they can devour a Humanoid in a matter of seconds. While swarming, ayperobos appear as a thick cloud of mosquitoes or a cloud of blood—and are known to hide among such phenomena. Some swarms have the power to control a "host" by burrowing under its skin and manipulating it from the inside—these hosts can even be other devils.

## Statblock

```ad-statblock
title: Ayperobo Swarm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Ayperobo%20Swarm.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 130 (`20d8 + 40`)
- **Speed** 5 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 3 (-4)|24 (+7)|14 (+2)| 8 (-1)|13 (+1)|13 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +11, Charisma +5
- **Skills** Intimidation +5, Perception +5, Stealth +11, Survival +5
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 15
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Celestial, Draconic, Infernal, telepathy 120 ft.
- **Challenge** 12

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the ayperobo swarm's darkvision.

***Magic Resistance.*** The ayperobo swarm has advantage on saving throws against spells and other magical effects.

***Swarm.*** The ayperobo swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny creature. The ayperobo swarm can't regain hit points or gain temporary hit points.

## Actions

***Multiattack.*** The ayperobo swarm makes three Bite attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 0 ft., one target. *Hit:* `dice:8d4+7|noform|avg|text(27)` (`8d4 + 7`) piercing damage, or `dice:4d4+7|noform|avg|text(17)` (`4d4 + 7`) piercing damage if the swarm has half of its hit points (65) or fewer.

***Burrow (Recharge 6).*** The ayperobo swarm makes a Bite attack. On a hit, the swarm burrows inside the creature, dealing an additional `dice:10d6|noform|avg|text(35)` (`10d6`) necrotic damage and taking control of the creature. At the start of each of its turns, the target may make a DC 17 Constitution saving throw, expelling the ayperobo swarm and taking `dice:4d6|noform|avg|text(14)` (`4d6`) piercing damage on a success.

While burrowed inside a creature, the ayperobo swarm has total cover against attacks targeting them, and no longer acts on their own initiative. Instead, they take total control over their host, gaining all of its abilities, attacks, and equipment.

They act during the host's turn, taking actions based on their host. If a host dies while the ayperobo swarm is burrowed, they leave the host at the end of the host's turn, rolling initiative if necessary. Creatures acting as hosts to the ayperobo swarm are fully aware of their actions and surroundings, but are incapable of physically operating their body.
```
^statblock