---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/6
- monster/size/large
- monster/type/monstrosity
aliases: ["Gloomstalker"]
---
# Gloomstalker
*Source: Explorer's Guide to Wildemount p. 291, Critical Role: Call of the Netherdeep p. 291*  

A gloomstalker is a terrifying, winged predator resembling a wyvern composed of twisting shadows, with glowing eyes and dagger-like teeth.

```ad-statblock
title: Gloomstalker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Gloomstalker.webp#token)
*Large monstrosity, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 90 (`12d10 + 24`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|16 (+3)|14 (+2)| 5 (-3)|17 (+3)|14 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +9, Dexterity +6
- **Skills** Athletics +9, Intimidation +5, Perception +6, Stealth +6
- **Senses** darkvision 240 ft, passive Perception 16
- **Damage Vulnerabilities** radiant
- **Languages** understands Common but can't speak
- **Challenge** 6

## Traits

***Shadowstep.*** As a bonus action, the gloomstalker can teleport up to 40 feet to an unoccupied space it can see.

***Sunlight Sensitivity.*** While in sunlight, the gloomstalker has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The gloomstalker makes two attacks: one with its bite and one with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.

***Snatch.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one Medium or smaller creature. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). While [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained).

***Shriek (Recharge 6).*** The gloomstalker emits a terrible shriek. Each enemy within 60 feet of the gloomstalker that can hear it must succeed on a DC 13 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the end of the enemy's next turn.
```
^statblock