---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/14
- monster/environment/underdark
- monster/size/medium
- monster/type/humanoid/cleric
- monster/type/humanoid/elf
aliases: ["Drow Inquisitor"]
---
# Drow Inquisitor
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 102, Mordenkainen's Tome of Foes p. 184*  

Lolth's worshipers expect treachery—the Spider Queen encourages it, after all. A certain amount of backstabbing and double-crossing can be managed, but too much can undermine an entire community. To keep some semblance of order and to root out traitors, priestesses of Lolth employ inquisitors. Inquisitors are chosen from the ranks of the priesthood, and their authority is equaled only by that of the [drow matron mothers](2-Mechanics/CLI/bestiary/humanoid/drow-matron-mother-mpmm.md) (also in this book) of the noble houses. Anyone they decide is at odds with the hierarchy faces painful interrogation and usually an excruciating death.

```ad-statblock
title: Drow Inquisitor
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Drow%20Inquisitor.webp#token)
*Medium humanoid (cleric, elf), Typically  Neutral Evil*

- **Armor Class** 16 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 149 (`23d8 + 46`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|15 (+2)|14 (+2)|16 (+3)|21 (+5)|20 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +7, Wisdom +10, Charisma +10
- **Skills** Insight +10, Perception +10, Religion +8, Stealth +7
- **Senses** darkvision 120 ft., passive Perception 20
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Elvish, Undercommon
- **Challenge** 14

## Traits

***Discern Lie.*** The drow discerns when a creature in earshot speaks a lie in a language the drow knows.

***Fey Ancestry.*** The drow has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put the drow to sleep.

***Sunlight Sensitivity.*** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Spellcasting.*** The drow's casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 18):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [message](2-Mechanics/CLI/spells/message.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [clairvoyance](2-Mechanics/CLI/spells/clairvoyance.md), [darkness](2-Mechanics/CLI/spells/darkness.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [levitate](2-Mechanics/CLI/spells/levitate.md) (self only), [silence](2-Mechanics/CLI/spells/silence.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md), [true seeing](2-Mechanics/CLI/spells/true-seeing.md)

## Actions

***Multiattack.*** The drow makes three Death Lance attacks.

***Death Lance.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) piercing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

## Bonus Actions

***Spectral Dagger (Recharges after a Short or Long Rest).*** The drow conjures a floating, spectral dagger within 60 feet of itself. The drow can make a melee spell attack (`dice:1d20+10|noform|text(+10)` to hit) against one creature within 5 feet of the dagger. On a hit, the target takes `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) force damage.

The dagger lasts for 1 minute. As a bonus action on later turns, the drow can move the dagger up to 20 feet and repeat the attack against one creature within 5 feet of the dagger.
```
^statblock

## Environment

underdark