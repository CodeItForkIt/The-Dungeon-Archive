---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/4
- monster/size/large
- monster/type/plant
aliases: ["Horrid Plant Dew Drinker"]
---
# Horrid Plant Dew Drinker
*Source: Quests from the Infinite Staircase p. 204*  

```ad-statblock
title: Horrid Plant Dew Drinker
*Large plant, Unaligned*

- **Armor Class** 6
- **Hit Points** 42 (`5d10 + 15`)
- **Speed** 5 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 3 (-4)|17 (+3)| 1 (-5)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (can't see beyond this radius), passive Perception 10
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened)
- **Languages** —
- **Challenge** 4

## Traits

***False Appearance.*** If the horrid plant is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the horrid plant move or act, that creature must succeed on a DC 18 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)) check to discern that the horrid plant isn't an ordinary plant.

## Actions

***Multiattack.*** The horrid plant makes two Tendril attacks.

***Tendril.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 30 ft., one target. *Hit:* `dice:2d6|noform|avg|text(7)` (`2d6`) bludgeoning damage. If the target is a Huge or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14), and the horrid plant can pull the target up to 25 feet closer to itself. Until the grapple ends, the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, and the horrid plant can't use the same tendril on another target. The horrid plant has two tendrils.

## Bonus Actions

***Vampiric Tendril.*** One creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the horrid plant must make a DC 13 Constitution saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage on a failed save or half as much damage on a successful one. The target's hit point maximum is reduced by an amount equal to the damage taken, and the horrid plant regains hit points equal to that amount. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.
```
^statblock