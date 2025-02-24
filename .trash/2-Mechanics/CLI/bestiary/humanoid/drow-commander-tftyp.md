---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Drow Commander"]
---
# Drow Commander
*Source: Tales from the Yawning Portal p. 209*  

```ad-statblock
title: Drow Commander
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Drow%20Commander.webp#token)
*Medium humanoid (elf), Neutral Evil*

- **Armor Class** 18 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 110 (`11d8 + 22`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|18 (+4)|14 (+2)|11 (+0)|13 (+1)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Constitution +5, Wisdom +4
- **Skills** Perception +4, Stealth +10
- **Senses** darkvision 120 ft., passive Perception 14
- **Languages** Elvish, Undercommon
- **Challenge** 5

## Traits

***Special Equipment.*** The drow carries three magical bolts, as follows:

- A *bolt of holding*, which casts [hold person](2-Mechanics/CLI/spells/hold-person.md) on a target hit with the bolt, as well as up to two other targets within 30 feet of that target  
- A *bolt of blinding*, which casts [blindness/deafness](2-Mechanics/CLI/spells/blindness-deafness.md) to blind on a target hit with the bolt, as well as up to two other targets within 30 feet of that target  
- A *bolt of vapors*, which casts [stinking cloud](2-Mechanics/CLI/spells/stinking-cloud.md) centered on the point it hits  

Each of these effects has a spell save DC of 15 and a duration of 1 minute.

***Fey Ancestry.*** The drow has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put the drow to sleep.

***Sunlight Sensitivity.*** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Innate Spellcasting.*** The drow's spellcasting ability is Charisma (spell save DC 12). It can innately cast the following spells, requiring no material components:

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md)

**1/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [levitate](2-Mechanics/CLI/spells/levitate.md) (self only)

## Actions

***Multiattack.*** The drow makes two shortsword attacks.

***Shortsword +2.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+6|noform|avg|text(9)` (`1d6 + 6`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.

***Hand Crossbow +1.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 30/120 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. The target wakes up if it takes damage or if another creature takes an action to shake it awake.

## Reactions

***Parry.*** The drow adds 3 to its AC against one melee attack that would hit it. To do so, the drow must see the attacker and be wielding a melee weapon.
```
^statblock