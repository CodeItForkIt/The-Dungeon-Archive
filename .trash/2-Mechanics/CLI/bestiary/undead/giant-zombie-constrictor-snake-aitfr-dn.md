---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aitfr-dn
- monster/cr/8
- monster/size/huge
- monster/type/undead
aliases: ["Giant Zombie Constrictor Snake"]
---
# Giant Zombie Constrictor Snake
*Source: Adventures in the Forgotten Realms: Deepest Night p. 11*  

These enormous, rotten husks were living, Medium-sized constrictors when the yuan-ti brought them to honor and entice Kyrilla to share her knowledge and powers. They grew to their full, Huge size on a diet of supplicants and prisoners, many of whose bones can be found elsewhere in the lair. When the yuan-ti turned against Kyrilla, they fought and slew these snakes—only to find them slithering again through cursed, ambient magic in Kyrilla's lair.

The constrictors die if they leave the lair.

```ad-statblock
title: Giant Zombie Constrictor Snake
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AitFR-DN/Giant%20Zombie%20Constrictor%20Snake.webp#token)
*Huge undead, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 187 (`22d12 + 44`)
- **Speed** 30 ft., climb 20 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|16 (+3)|14 (+2)| 1 (-5)|15 (+2)| 4 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +5, Stealth +6
- **Senses** blindsight 15 ft., darkvision 60 ft., passive Perception 15
- **Damage Vulnerabilities** poison
- **Languages** —
- **Challenge** 8

## Traits

***Sunlight Vulnerability.*** While in sunlight, the snake has disadvantage on attack rolls and on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight. When the snake begins its turn in sunlight, it immediately suffers 10 radiant damage.

***Undead Fortitude.*** If damage reduces the snake to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the snake drops to 1 hit point instead.

## Actions

***Multiattack.*** The snake makes two attacks: one with its bite and one with a constrict attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+4|noform|avg|text(17)` (`3d8 + 4`) piercing damage, and the target must make a DC 15 Constitution saving throw, taking `dice:5d6|noform|avg|text(17)` (`5d6`) poison damage on a failed save, or half as much damage on a successful one.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+4|noform|avg|text(17)` (`3d8 + 4`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and the snake cannot constrict another target.
```
^statblock