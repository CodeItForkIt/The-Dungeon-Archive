---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/5
- monster/size/medium
- monster/type/undead
aliases: ["Spirit of Hunger"]
---
# Spirit of Hunger
*Source: Quests from the Infinite Staircase*  

```ad-statblock
title: Spirit of Hunger
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Spirit%20of%20Hunger.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 67 (`9d8 + 27`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|16 (+3)|16 (+3)|12 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** the languages it knew in life
- **Challenge** 5

## Traits

***Incorporeal Movement.*** Spirit of Hunger can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Sunlight Sensitivity.*** While in sunlight, Spirit of Hunger has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:4d8+3|noform|avg|text(21)` (`4d8 + 3`) necrotic damage. The target must succeed on a DC 14 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

***Create Specter.*** Spirit of Hunger targets a humanoid within 10 feet of it that has been dead for no longer than 1 minute and died violently. The target's spirit rises as a [specter](2-Mechanics/CLI/bestiary/undead/specter.md) in the space of its corpse or in the nearest unoccupied space. The [specter](2-Mechanics/CLI/bestiary/undead/specter.md) is under Spirit of Hunger's control. Spirit of Hunger can have no more than seven specters under its control at one time.
```
^statblock