---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/1
- monster/size/small
- monster/type/aberration
aliases: ["Derro Apprentice"]
---
# Derro Apprentice
*Source: Quests from the Infinite Staircase p. 196*  

Derro who have just begun to discover and control their magic are called apprentices. The magic of a derro apprentice is dangerous and unpredictable.

## Derro

Derro are Underdark dwellers of dubious origin. According to the histories of some duergar, derro are descended from a community of dwarves that was left behind when the others escaped the rule of mind flayers. The mind flayers' psionic power eventually transformed these forsaken dwarves into Aberrations.

You can learn more about derro in*Mordenkainen Presents: Monsters of the Multiverse*.

## Statblock

```ad-statblock
title: Derro Apprentice
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Derro%20Apprentice.webp#token)
*Small aberration, typically  Chaotic Evil*

- **Armor Class** 13 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 22 (`5d6 + 5`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|12 (+1)|11 (+0)| 5 (-3)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4
- **Senses** darkvision 120 ft., passive Perception 7
- **Languages** Dwarvish, Undercommon
- **Challenge** 1

## Traits

***Magic Resistance.*** The derro has advantage on saving throws against spells and other magical effects.

***Sunlight Sensitivity.*** While in sunlight, the derro has disadvantage on attack rolls.

***Spellcasting.*** The derro casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 11):

**At will**: [Message](2-Mechanics/CLI/spells/message.md), [Prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day**: [Charm Person](2-Mechanics/CLI/spells/charm-person.md)

## Actions

***Chaos Blast.*** *Melee or Ranged Spell Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) damage. Roll a `dice:d4|noform|avg` (`d4`) to determine the damage type: 1, acid; 2, cold; 3, fire; 4, lightning.

***Force Burst (Recharge 4-6).*** Raw arcane magic bursts out from the derro. Each creature within 10 feet of it must make a DC 11 Strength saving throw. On a failed save, the creature takes `dice:2d6|noform|avg|text(7)` (`2d6`) force damage and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. On a successful save, the creature takes half as much damage only.
```
^statblock