---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/7
- monster/size/huge
- monster/type/monstrosity
aliases: ["Swavain Basilisk"]
---
# Swavain Basilisk
*Source: Explorer's Guide to Wildemount p. 300*  

Pearl divers and seafloor scavengers sometimes tell tales of mysterious ocean gardens filled with statues of sea creatures and sailors—the underwater grottoes of the deadly Swavain basilisk. Though named for the Swavain Islands where they are most commonly found, these dangerous hunters have been known to wander inland waterways, and have even been spotted in subterranean sewer systems.

```ad-statblock
title: Swavain Basilisk
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Swavain%20Basilisk.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 85 (`10d12 + 20`)
- **Speed** 15 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|16 (+3)|15 (+2)| 2 (-4)| 8 (-1)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 7

## Traits

***Amphibious.*** The basilisk can breathe air and water.

***Petrifying Secretions.*** A creature must make a DC 13 Constitution saving throw if it hits the basilisk with a weapon attack while within 5 feet of it or if it starts its turn [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the basilisk. Unless the save succeeds, the creature magically begins to turn to stone and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and it must repeat the saving throw at the end of its next turn. On a successful save, the effect ends. On a failure, the creature is [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified).

## Actions

***Multiattack.*** The basilisk makes two attacks: one with its bite and one with its tail.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:3d6+3|noform|avg|text(13)` (`3d6 + 3`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+3|noform|avg|text(14)` (`2d10 + 3`) bludgeoning damage. If the target is a Large or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 12).
```
^statblock