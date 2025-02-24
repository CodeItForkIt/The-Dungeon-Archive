---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/3
- monster/size/small-or-medium
- monster/type/humanoid
aliases: ["Harmonium Peacekeeper"]
---
# Harmonium Peacekeeper
*Source: Morte's Planar Parade p. 59, Sigil and the Outlands, Turn of Fortune's Wheel*  

Peacekeepers wear distinctive red plate armor and wield planar mancatchers, polearms whose metal pincers prevent criminals clamped in their grasp from teleporting away, making them excellent at catching wrongdoers in Sigil.

```ad-statblock
title: Harmonium Peacekeeper
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Harmonium%20Peacekeeper.webp#token)
*Small or Medium humanoid, Any alignment*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 45 (`7d8 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|14 (+2)|12 (+1)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4
- **Senses** passive Perception 14
- **Languages** Common plus one more language
- **Challenge** 3

## Traits

***Pack Tactics.*** The peacekeeper has advantage on an attack roll against a creature if at least one of the peacekeeper's allies is within 5 feet of the creature and the ally doesn't have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

## Actions

***Electrified Mancatcher.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) lightning damage. If the target is a Large or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 13). Until the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition ends, the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and can't teleport, the peacekeeper can't make Electrified Mancatcher attacks, and the target takes `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) lightning damage at the start of each of its turns.
```
^statblock