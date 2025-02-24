---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/any
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Shadow Fey Duelist"]
---
# Shadow Fey Duelist
*Source: Tome of Beasts 1 (2023 Edition) p. 159*  

*The pale-skinned elf wears a gleaming breastplate and tight-fitting clothing. He moves like the wind, evading blows with effortless skill. When he stops and smiles, his blade is slick with crimson*.

Shadow fey duelists are elite warriors, often of noble lineage. Swift and sure beyond compare, duelists are often taller and more wiry than others of their kind. Their armor, clothing, and weapons are of exquisite make, fashioned from only the finest materials, as befits their station.

## Deadly Nobles

A nobleman or woman of the shadow fey is not to be taken lightly—many courtiers or politicians are deadly with their slim blades, and they are known to distill virulent poisons. Often a skilled duelist serves as a champion for her liege, standing in the noble's stead in challenges or serving as an elite bodyguard.

## Statblock

```ad-statblock
title: Shadow Fey Duelist
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Shadow%20Fey%20Duelist.webp#token)
*Medium humanoid (elf), Lawful Evil*

- **Armor Class** 17 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 117 (`18d8 + 36`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|20 (+5)|14 (+2)|13 (+1)|12 (+1)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +8, Constitution +5, Charisma +6
- **Skills** Acrobatics +8, Deception +6, Perception +4, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Common, Elvish, Umbral
- **Challenge** 6

## Traits

***Duelist's Mobility.*** Opportunity attacks made against the duelist have disadvantage. If the duelist is [prone](2-Mechanics/CLI/rules/conditions.md#Prone) at the start of its turn, it can immediately stand without costing movement.

***Fey Ancestry.*** The shadow fey has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put it to sleep.

***Sunlight Sensitivity.*** While in sunlight, the shadow fey has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The shadow fey duelist makes two Rapier attacks and one Dagger attack.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+5|noform|avg|text(7)` (`1d4 + 5`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage, and if the target is a creature, it must succeed on a DC 14 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Rapier.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) piercing damage.

## Bonus Actions

***Shadow Traveler (3/Day).*** While in shadows, dim light, or darkness, the shadow fey disappears into the darkness and reappears in an unoccupied space it can see within 30 feet. A tendril of inky smoke appears at the origin and destination when it uses this bonus action.

## Reactions

***Parry.*** The shadow fey duelist adds 3 to its AC against one melee attack that would hit it. To do so, the duelist must see the attacker and be wielding a melee weapon.
```
^statblock

## Environment

any, urban