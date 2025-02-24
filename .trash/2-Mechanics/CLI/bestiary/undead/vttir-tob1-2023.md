---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/any
- monster/size/medium
- monster/type/undead
aliases: ["Vættir"]
---
# Vættir
*Source: Tome of Beasts 1 (2023 Edition) p. 378*  

*The creature's blue-black skin is stretched taut over its bones, and its lips are drawn back in a cruel grimace. It holds a bronze axe high over its head, and its eyes glow an icy blue.*

## Servants of the Land

Servants of the land, vættir haunt those who disrespect the wild or ancient laws and traditions. Regardless of where they're found, vættir always wear ancient mail and carry bronze axes.

## Jealous and Wrathful

A wrathful vættir rises from its burial mound when its grave goods are stolen or when it is disrespected. Vættir jealously guard both honor and treasures, and they may be relentless enemies over matters as small as an accidental word or a single coin.

## Dangerous Helpers

Vættirs will answer a summons for aid by descendants or nearby villages. Summoned vættir wander into longhouses or taverns and sit down beside those who call them, ready to serve. However, there's always a price, and a vættir's help is often more than bargained for.

## Statblock

```ad-statblock
title: Vættir
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Vaettir.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 15 ([chain shirt](2-Mechanics/CLI/items/chain-shirt.md))
- **Hit Points** 97 (`13d8 + 39`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|16 (+3)|10 (+0)|12 (+1)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +4, Wisdom +3
- **Skills** ⏤
- **Senses** darkvision 60 ft., truesight 30 ft., passive Perception 11
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 4

## Traits

***Grave Goods Sense.*** The vættir can pinpoint the location of creatures wearing or carrying one of the vættir's personal items or grave goods within 60 feet of it, and the vættir can sense the general direction of its personal items and grave goods within 1 mile of it.

***Rejuvenation.*** A destroyed vættir gains a new body in 24 hours, regaining all its hp and becoming active again. The new body forms in a random unoccupied space within 100 feet of where it fell. This trait doesn't function if the vættir is put to rest (typically by returning its remains to its burial mound).

***Sunlight Sensitivity.*** While in sunlight, the vættir has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Undead Nature.*** The vættir doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The vættir can use its Disorienting Gaze. It then makes two Vættir's Greataxe or Necrotic Bolt attacks.

***Vættir's Greataxe.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d12+5|noform|avg|text(11)` (`1d12 + 5`) slashing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) necrotic damage.

***Necrotic Bolt.*** *Ranged Spell Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 120 ft., one target. *Hit:* `dice:3d8+2|noform|avg|text(15)` (`3d8 + 2`) necrotic damage.

***Disorienting Gaze.*** The vættir locks eyes with one creature it can see within 30 feet of it. The target must succeed on a DC 15 Charisma saving throw or be [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) for 1 minute. While [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), the creature moves in a random direction when it moves. An [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the vættir's Disorienting Gaze for the next 24 hours.

***Corpse Breath (Recharge 5-6).*** The vættir spews forth a 15‑foot cone of putrid gas. Each creature in the area must make a DC 15 Constitution saving throw. On a failure, a creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. On a success, a creature takes half the damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

any