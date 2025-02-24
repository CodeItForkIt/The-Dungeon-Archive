---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/14
- monster/environment/underwater
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Isonade"]
---
# Isonade
*Source: Tome of Beasts 1 (2023 Edition) p. 240*  

*The creature's mighty tail thrashes ships, docks, and sailors in its path of destruction.*

## Coastal Destroyer

The isonade is a beast of destruction, sweeping away entire islands and villages. Though not very intelligent, it singles out a community and tries to lure residents into the waves by forcing plentiful fish to the surface, easy pickings for even the most amateur fishers.

## Ocean Sacrifices

When coastal villagers suffer from a hurricane or tsunami, they fall back on folklore and blame the stirrings of the isonade. Some say that a degenerate group seeks to draw the beast forth by dumping a long chain of bound and screaming sacrifices into the lightless depths of the sea.

## Ancient Being

The beast's age is unknown, and many coastal bards tell various legends of the creature. Some say it is the last of its kind, while others say that a small group of isonades lurks in the depths.

## Statblock

```ad-statblock
title: Isonade
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Isonade.webp#token)
*Gargantuan monstrosity, Chaotic Neutral*

- **Armor Class** 18 (natural armor)
- **Hit Points** 222 (`12d20 + 96`)
- **Speed** 10 ft., swim 100 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|14 (+2)|26 (+8)| 6 (-2)|18 (+4)| 8 (-1)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +15, Constitution +13, Wisdom +9
- **Skills** Athletics +15, Perception +9
- **Senses** darkvision 90 ft., passive Perception 19
- **Damage Immunities** cold
- **Languages** understands Aquan and Elvish, but can't speak
- **Challenge** 14

## Traits

***Influence Weather.*** Nearby weather responds to the isonade's desires. At the start of each minute, the isonade can choose to change the precipitation and wind within 1 mile of it by one stage, up or down (no action required). This effect works like the changing weather conditions aspect of the [control weather](2-Mechanics/CLI/spells/control-weather.md) spell, except the isonade can't change the temperature and the conditions change immediately.

***Magic Resistance.*** The isonade has advantage on saving throws against spells and other magical effects.

***Siege Monster.*** The isonade deals double damage to objects and structures.

***Water Breathing.*** The isonade can breathe only underwater.

## Actions

***Multiattack.*** The isonade makes one Bite attack and two Tail Slap attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one target. *Hit:* `dice:4d12+10|noform|avg|text(36)` (`4d12 + 10`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 18 Dexterity saving throw or be swallowed by the isonade. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the isonade, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the isonade's turns. An isonade can have no more than four creatures swallowed at a time. If the isonade takes 30 damage or more on a single turn from a creature inside it, it must succeed on a DC 23 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the isonade. If the isonade dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tail Slap.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one target. *Hit:* `dice:4d6+10|noform|avg|text(24)` (`4d6 + 10`) bludgeoning damage.

***Breach.*** If the isonade swims at least 20 feet as part of its movement, it can use this action to emerge in a space on the surface of the water that contains one or more other creatures. Each of those creatures and each creature within 10 of the isonade's space must make a DC 18 Dexterity saving throw. On a failure, a creature takes `dice:14d6|noform|avg|text(49)` (`14d6`) bludgeoning damage and is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). On a success, a creature takes half the damage and is pushed up to 10 feet out of the isonade's space into an unoccupied space of the creature's choice. If no unoccupied space is within range, the creature instead falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in the isonade's space.
```
^statblock

## Environment

underwater