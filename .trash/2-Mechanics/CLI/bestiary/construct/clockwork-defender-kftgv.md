---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/kftgv
- monster/cr/1
- monster/size/medium
- monster/type/construct
aliases: ["Clockwork Defender"]
---
# Clockwork Defender
*Source: Keys from the Golden Vault p. 85*  

A clockwork defender is a mechanical quadruped that vaguely resembles a hound. Its eyes glow and can project intense but harmless beams of light. It tirelessly protects whatever its creator wants, and it can be programmed by its creator not to attack certain kinds of creatures.

```ad-statblock
title: Clockwork Defender
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/KftGV/Clockwork%20Defender.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 42 (`5d8 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|15 (+2)|18 (+4)| 3 (-4)|14 (+2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +6, Stealth +4
- **Senses** passive Perception 16
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 1

## Traits

***Unusual Nature.*** The defender doesn't need air, food, drink, or sleep.

## Actions

***Electrified Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) lightning damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). A creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the defender takes the damage again at the start of each of the defender's turns. The defender can have only one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way at a time, and the defender can't make Electrified Bite attacks while grappling.

## Bonus Actions

***Light Beam.*** The defender emits bright light from its eyes in a 60-foot cone, or it shuts off this light.
```
^statblock