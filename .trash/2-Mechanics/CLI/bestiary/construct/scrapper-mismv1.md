---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mismv1
- monster/cr/8
- monster/size/large
- monster/type/construct
aliases: ["Scrapper"]
---
# Scrapper
*Source: Misplaced Monsters: Volume 1 p. 10*  

> [!note]
> Created by Jake F.

Scrappers are tall, broad-shouldered automatons usually found in scrap yards. Sparks erupt from the loose wires that protrude from their hulking frames. Their quasi-mechanical minds are shielded with lead, protecting them from psychic damage.

A scrapper feeds on scrap metal and uses its electrified wires to grapple and reel in foes. It zaps enemies it can't reach with an energy beam fired from an extended eye.

```ad-statblock
title: Scrapper
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MisMV1/Scrapper.webp#token)
*Large construct, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 126 (`12d10 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|20 (+5)| 3 (-4)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6
- **Senses** darkvision 120 ft., passive Perception 16
- **Damage Resistances** lightning
- **Damage Immunities** poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 8

## Traits

***Electrified Chassis.*** A creature that hits the scrapper with a melee attack while within 5 feet of it takes `dice:3d12|noform|avg|text(19)` (`3d12`) lightning damage.

## Actions

***Multiattack.*** The scrapper makes two Spike Punch attacks. It can replace one of those with a Wires attack.

***Spike Punch.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) piercing damage.

***Wires.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 20 ft., one Large or smaller creature. *Hit:* The target has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 16) and must succeed on a DC 16 Strength saving throw or be pulled into an unoccupied space within 5 feet of the scrapper and take `dice:3d12|noform|avg|text(19)` (`3d12`) lightning damage. The scrapper can have only one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way at a time.

***Eye Beam (Recharge 5-6).*** The scrapper shoots a magical beam from its extended eye at one creature it can see within 120 feet of itself. The target must make a DC 16 Dexterity saving throw, taking `dice:8d10|noform|avg|text(44)` (`8d10`) force damage on a failed save, or half as much damage on a successful one.
```
^statblock