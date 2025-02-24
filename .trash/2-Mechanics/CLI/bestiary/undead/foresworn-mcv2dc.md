---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv2dc
- monster/cr/6
- monster/size/medium
- monster/type/undead
aliases: ["Foresworn"]
---
# Foresworn
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 7*  

Foresworn are the spirits of fallen Solamnic knights who attend to their duty long after death. Armed with spectral armor and weaponry, a foresworn maintains the martial prowess it had in life and can call on magic and its fallen brethren for aid.

Like revenants, foresworn fixate on a singular purpose, and they refuse to abandon their undead state until the duty they had in life is fulfilled. For example, a foresworn might be pledged to protect a family's bloodline from harm or guard a dangerous artifact against thieves. If a foresworn is destroyed before it can complete its duty, it returns within a few days, its strength and purpose renewed.

```ad-statblock
title: Foresworn
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV2DC/Foresworn.webp#token)
*Medium undead, typically  Lawful Good*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|17 (+3)|12 (+1)|18 (+4)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +8, Wisdom +7
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** the languages it knew in life
- **Challenge** 6

## Traits

***Duty-Bound.*** The foresworn is bound to enacting a singular duty it pledged itself to in life. While this duty is incomplete, whenever the foresworn is destroyed, it re-forms at its previous location after `dice:1d6|noform|avg|text(3)` (`1d6`) days, with all its hit points restored.

***Incorporeal Movement.*** The foresworn can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Unusual Nature.*** The foresworn doesn't require air, food, drink, or sleep.

***Spellcasting.*** The foresworn casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 15):

**1/day**: [wall of force](2-Mechanics/CLI/spells/wall-of-force.md)

**2/day each**: [command](2-Mechanics/CLI/spells/command.md), [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md)

## Actions

***Multiattack.*** The foresworn makes three Spectral Polearm attacks.

***Spectral Polearm.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) force damage.

## Bonus Actions

***Phantasmic Battalion (Recharge 5-6).*** The foresworn summons a battalion of ghostly soldiers to its aid. The ghostly soldiers fill a 10-foot-cube centered on the foresworn, move with the foresworn when the foresworn moves, and last until the start of the foresworn's next turn. While the ghostly soldiers are present, the area they occupy is considered difficult terrain for all creatures except the foresworn, and the foresworn's reach for melee weapon attacks increases by 10 feet.
```
^statblock