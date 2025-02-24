---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgg
- monster/cr/21
- monster/size/gargantuan
- monster/type/construct
aliases: ["Runic Colossus"]
---
# Runic Colossus
*Source: Bigby Presents: Glory of the Giants p. 163*  

According to*The Saga of the Dragon Queller*, told by giants on some worlds, a disparate group of giants combined their efforts to protect their ancient empire from a particularly vicious dragon. Stone and hill giants hewed a mighty form from living stone. Cloud and frost giants gathered rare metals, and fire giants shaped them into flexible joints and plated armor. Storm giants inscribed runes into the inert form to give it the semblance of life. The fruit of these labors was an everlasting guardian: the first runic colossus.

A runic colossus stands 30 feet tall. It regards all non-giants as a threat, and unless it has other orders, it attacks such creatures on sight.

The art of crafting a runic colossus is lost to modern giants, but many tales suggest the instructions might be buried deep in ruins from ancient giants' empires.

```ad-statblock
title: Runic Colossus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGG/Runic%20Colossus.webp#token)
*Gargantuan construct, Unaligned*

- **Armor Class** 20 (natural armor)
- **Hit Points** 315 (`18d20 + 126`)
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)| 9 (-1)|24 (+7)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +7
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Resistances** acid, cold, fire, lightning
- **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Giant but can't speak
- **Challenge** 21

## Traits

***Immutable Form.*** The colossus is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The colossus has advantage on saving throws against spells and other magical effects.

***Siege Monster.*** The colossus deals double damage to objects and structures.

## Actions

***Multiattack.*** The colossus makes two Slam attacks and then uses Stomp.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 20 ft., one target. *Hit:* `dice:3d12+7|noform|avg|text(26)` (`3d12 + 7`) bludgeoning damage.

***Stomp.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 20 ft., one target. *Hit:* `dice:4d10+7|noform|avg|text(29)` (`4d10 + 7`) bludgeoning damage. If the target is a Huge or smaller creature, it must succeed on a DC 22 Dexterity saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. Until the colossus uses its Stomp again or moves, the creature has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. The [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature or another creature within 5 feet of it can use its action to make a DC 22 Strength check. On a successful check, the affected creature relocates to an unoccupied space of its choice within 5 feet of the colossus and is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained).

***Arcane Beam (Recharge 5-6).*** The colossus fires a beam of magical force from its chest, hands, or head in a 150-foot line that is 10 feet wide. Each creature in that area must make a DC 22 Dexterity saving throw, taking `dice:9d12|noform|avg|text(58)` (`9d12`) force damage on a failed save, or half as much damage on a successful one.

## Reactions

***Spell Reflection (2/Day).*** *Ranged Spell Attack:* `dice:1d20+14|noform|text(+14)` to hit, range 120 ft., one creature casting a spell of 5th level or lower. *Hit:* `dice:4d12|noform|avg|text(26)` (`4d12`) force damage, and the target must succeed on a DC 15 Intelligence saving throw or the spell fails and has no effect.
```
^statblock