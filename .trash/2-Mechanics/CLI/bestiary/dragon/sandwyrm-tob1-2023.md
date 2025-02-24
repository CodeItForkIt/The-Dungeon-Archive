---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/desert
- monster/size/large
- monster/type/dragon
aliases: ["Sandwyrm"]
---
# Sandwyrm
*Source: Tome of Beasts 1 (2023 Edition) p. 314*  

*The large, bleached bones protruding from the desert sand suddenly shift and reveal themselves to be the boney spikes of a great reptile.*

## Hidden by Sand

These lethargic, horned, yellow-scaled lizards spend most of their lives underground, lying in wait under the desert sand with their long-necked, spine-tailed bulk hidden below the surface. Only the long, jagged bones lining their backs are exposed. These bones resemble a sun-bleached ribcage so perfectly that it attracts carrion birds—and curious travelers. When prey passes between the "ribs," the sandwyrm snaps the rows of bone tightly over its prey. Once its victim is restrained, the sandwyrm paralyzes its meal with repeated stings before carrying it away.

## Torpid and Slow

Sandwyrms sometimes wait for weeks in torpid hibernation before footsteps on the sand alert it to a fresh meal approaching. To guard against lean weeks, sandwyrms store excess prey in subterranean lairs. They're not above eating carrion if fresh meat isn't available. When outmatched in a fight, sandwyrms retreat to their lairs with their paralyzed prey.

## Peculiar Drakes

Sandwyrms evolved as an offshoot to drakes or wyverns rather than from true dragons; their anatomy suggests they were originally four-limbed creatures and that their forearms are recent additions to the animal's body. The bones on their backs may have once been wings, suggesting that sandwyrms are the remnants of some primordial, winged reptiles that migrated to the deep deserts.

## Statblock

```ad-statblock
title: Sandwyrm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Sandwyrm.webp#token)
*Large dragon, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 142 (`15d10 + 60`)
- **Speed** 20 ft., burrow 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|18 (+4)| 5 (-3)|13 (+1)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +7, Stealth +4
- **Senses** darkvision 60 ft., tremorsense 120 ft., passive Perception 17
- **Languages** —
- **Challenge** 6

## Actions

***Multiattack.*** The sandwyrm makes one Bite attack, one Gore attack, and one Stinger attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage.

***Gore.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d12+5|noform|avg|text(11)` (`1d12 + 5`) piercing damage.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one creature. *Hit:* `dice:1d4+5|noform|avg|text(9)` (`1d4 + 5`) piercing damage, and the target must make a DC 15 Constitution saving throw, taking `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hp, the target is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hp, and is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

## Reactions

***Spine Trap.*** When the sandwyrm is burrowed just below the surface of sand with its back spines exposed and a Medium or smaller creature enters the spines' space, the sandwyrm closes the spines on the creature. The creature must succeed on a DC 15 Dexterity saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). When the sandwyrm moves, a [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature moves with it. The sandwyrm can have only one creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) at a time. A creature, including the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature, can take an action to free the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature by succeeding on a DC 15 Strength check.
```
^statblock

## Environment

desert