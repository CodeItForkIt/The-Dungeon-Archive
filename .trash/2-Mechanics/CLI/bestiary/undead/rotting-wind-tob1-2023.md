---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/farmland
- monster/environment/urban
- monster/size/large
- monster/type/undead
aliases: ["Rotting Wind"]
---
# Rotting Wind
*Source: Tome of Beasts 1 (2023 Edition) p. 311*  

*A noxious wind brings a chilling gust to the air, turning nearby foliage to rot.*

## Air of Tombs

A rotting wind is an undead creature made up of the foul air and grave dust sloughed off by innumerable undead creatures within lost tombs and grand necropolises.

## Scouts for Undead Armies

A rotting wind carries the foul stench of death upon it, sometimes flying before undead armies and tomb legions or circling around long-extinct cities and civilizations.

## Withering Crops

Rotting winds sometimes drift mindlessly across a moor or desert, blighting all life they find and leaving only famine and death in their wake. This is especially dangerous when they drift across fields full of crops. They can destroy an entire harvest in minutes.

## Statblock

```ad-statblock
title: Rotting Wind
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Rotting%20Wind.webp#token)
*Large undead, Neutral Evil*

- **Armor Class** 15
- **Hit Points** 110 (`13d10 + 39`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|20 (+5)|16 (+3)| 7 (-2)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 11
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** —
- **Challenge** 6

## Traits

***Air Form.*** The rotting wind can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.

***Invisibility.*** The rotting wind is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible).

***Poisonous Aura.*** The rotting wind radiates an aura of poison and decay that slowly pollutes the area within 30 feet of it. Each hour the rotting wind stays in a place, nonmagical plants in the aura begin to wither, and water in the aura becomes [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). Nonmagical plants in the aura for 24 hours die. A creature that drinks water [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) by the aura must succeed on a DC 14 Constitution saving throw or contract the tomb rot disease (see the Tomb Rot trait). Creatures immune to the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition are immune to this disease.

***Tomb Rot.*** A creature infested with this disease manifests symptoms `dice:1d4|noform|avg` (`1d4`) days after infection, which include muscle weakness and rotten-smelling breath as its body rots from the inside out. Until the disease is cured, at the end of each long rest, the infected creature must succeed on a DC 14 Constitution saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage and suffer one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). This [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) lasts until the creature finishes a long rest after the disease is cured. A creature that succeeds on two saving throws recovers from the disease.

***Undead Nature.*** The rotting wind doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The rotting wind makes two Wind of Decay attacks. If both attacks hit one creature, the target must succeed on a DC 14 Constitution saving throw or contract the tomb rot disease (see the Tomb Rot trait).

***Wind of Decay.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 0 ft., one target in the rotting wind's space. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.
```
^statblock

## Environment

farmland, urban