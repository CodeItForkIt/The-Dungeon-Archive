---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/4
- monster/size/small
- monster/type/fey
aliases: ["Leprechaun"]
---
# Leprechaun
*Source: Quests from the Infinite Staircase p. 205*  

Leprechauns are manifestations of the Feywild rules of hospitality and reciprocity. These rules infuse leprechauns with a deep connection to fixing and making things. Industrious and proud, leprechauns channel this creative energy into their tools, using them to quickly mend damaged objects, craft new ones from raw materials, and mold ideas into vivid illusions.

A leprechaun's adherence to Feywild rules affords it tremendous luck, but this fortune comes at a cost. These same magical strictures compel leprechauns to use their powers on behalf of those who offer them gifts. Leprechauns despise greed and are spiteful toward anyone who makes demands without first offering a gift or, worse, anyone who tries to steal from them. They delight in pranking such foolish creatures or pilfering from them in return.

Leprechauns take pride in their appearances, dressing in dapper outfits that typically feature red fabrics, gleaming belts and buckles, and natural woodland accouterments. These fashions compliment their bright green skin, exuberant hair, and upbeat demeanors.

```ad-statblock
title: Leprechaun
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Leprechaun.webp#token)
*Small fey, typically  Neutral*

- **Armor Class** 13
- **Hit Points** 52 (`8d6 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|17 (+3)|16 (+3)|12 (+1)|14 (+2)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +5, Wisdom +4
- **Skills** Perception +4, Sleight of Hand +7, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Common, Sylvan
- **Challenge** 4

## Traits

***Industrious.*** The leprechaun is proficient with all artisan's tools and adds double its proficiency bonus to ability checks made with them.

***Reluctant Refusal.*** When a creature offers the leprechaun the chance to partake in merriment or revelry such as a song, a dance, or a good meal, the leprechaun must succeed on a DC 15 Wisdom saving throw or have the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition for 24 hours. While [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) in this way, the leprechaun partakes of the offering, treats the creature as a trusted friend, and seeks to defend it from harm. The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition ends if the creature or any of its allies damage the leprechaun, force the leprechaun to make a saving throw, or steal from the leprechaun.

***Spellcasting.*** The leprechaun casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):

**At will**: [Mending](2-Mechanics/CLI/spells/mending.md) (as an action), [Prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [Fabricate](2-Mechanics/CLI/spells/fabricate.md) (as an action), [Mislead](2-Mechanics/CLI/spells/mislead.md)

**2/day each**: [Invisibility](2-Mechanics/CLI/spells/invisibility.md), [Phantasmal Force](2-Mechanics/CLI/spells/phantasmal-force.md)

## Actions

***Multiattack.*** The leprechaun makes two Cobbler's Hammer attacks and can use Spellcasting.

***Cobbler's Hammer.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) bludgeoning damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) force damage. If the target is a creature, its speed is halved until the start of the leprechaun's next turn.

***Gift of Luck (1/Day).*** The leprechaun touches a creature and magically gifts the target a measure of luck. The creature gains the leprechaun's Astonishing Luck reaction. The creature can use the reaction three times, after which this gift goes away. The leprechaun can revoke this gift from a creature at any time (no action required). A creature can benefit from only one leprechaun's Gift of Luck at a time.

## Bonus Actions

***Cunning Trick.*** The leprechaun takes the Disengage or Hide action or makes a Dexterity ([Sleight of Hand](2-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)) check.

## Reactions

***Astonishing Luck.*** When the leprechaun fails an ability check, an attack roll, or a saving throw, it can roll a new `dice:d20|noform|avg` (`d20`) and choose which roll to use, potentially turning the failure into a success.
```
^statblock