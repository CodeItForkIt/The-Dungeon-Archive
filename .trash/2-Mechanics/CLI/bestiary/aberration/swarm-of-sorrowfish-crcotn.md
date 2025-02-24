---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/6
- monster/size/medium
- monster/type/aberration
aliases: ["Swarm of Sorrowfish"]
---
# Swarm of Sorrowfish
*Source: Critical Role: Call of the Netherdeep p. 210*  

A swarm of sorrowfish attacks out of hunger. Although sorrowfish have no sense of fear, they often adopt the tactic of lurking among the petrifying tendrils of a death embrace, using the tendrils for protection against other predators.

## Sorrowfish

Sorrowfish dwell in deep underwater trenches and thus are rarely encountered by surface-dwelling creatures. Some say sorrowfish get their name from their flavor, which is distasteful enough to put the creatures that eat them in a dismal mood. The true sorrow for other creatures comes when the sorrowfish gather in swarms. The malevolent presences that lurk in the abysses of the ocean exert their influence on these fish, transforming their swarms into vicious hordes.

## Statblock

```ad-statblock
title: Swarm of Sorrowfish
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Swarm%20of%20Sorrowfish.webp#token)
*Medium aberration, Unaligned*

- **Armor Class** 14
- **Hit Points** 104 (`16d8 + 32`)
- **Speed** 0 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|19 (+4)|14 (+2)| 1 (-5)|11 (+0)| 3 (-4)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 6

## Traits

***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through an opening as narrow as 1 foot wide. The swarm can't regain hit points or gain temporary hit points.

***Virulent Sorrow.*** Each time the swarm takes damage, any creature within 5 feet of it must make a DC 13 Wisdom saving throw. On a failed saving throw, the creature suffers the following effects until the end of its next turn: it has disadvantage on its attack rolls, it can't take reactions, and its speed is halved.

***Water Breathing.*** The swarm can breathe only underwater.

## Actions

***Swarm of Bites.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 0 ft., one target in the swarm's space. *Hit:* `dice:6d6|noform|avg|text(21)` (`6d6`) piercing damage, or `dice:3d6|noform|avg|text(10)` (`3d6`) piercing damage if the swarm has half its hit points or fewer.

***Desolate Drain (Recharge 5-6).*** Each creature in the swarm's space must make a DC 13 Wisdom saving throw. On a failed saving throw, a creature takes `dice:7d6|noform|avg|text(24)` (`7d6`) psychic damage and is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn. The effect ends on a creature if the swarm moves out of the creature's space or if another creature within 5 feet of the swarm uses an action to make a DC 14 Strength check, pulling the affected creature out of the swarm on a successful check. On a successful saving throw, a creature takes half as much damage and suffers no other effects.
```
^statblock