---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/jttrc
- monster/cr/13
- monster/size/medium
- monster/type/celestial
aliases: ["Pari"]
---
# Pari
*Source: Journeys through the Radiant Citadel p. 167*  

A pari is an angelic harbinger gifted with foresight. A visit from a pari is often a prophetic warning or portent of an event yet to come. Pari have pastel blue skin, wear robes and armor, and have two sets of wings with vivid red feathers sprouting from their back.

```ad-statblock
title: Pari
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/JttRC/Pari.webp#token)
*Medium celestial, typically  Lawful Good*

- **Armor Class** 16 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 180 (`19d8 + 95`)
- **Speed** 30 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|20 (+5)|20 (+5)|20 (+5)|22 (+6)|22 (+6)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +10, Wisdom +11, Charisma +11
- **Skills** Insight +16, Perception +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Resistances** fire; radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all, telepathy 120 ft.
- **Challenge** 13

## Traits

***Magic Resistance.*** The pari has advantage on saving throws against spells and other magical effects.

***Unusual Nature.*** The pari doesn't require food, drink, or sleep.

***Spellcasting.*** The pari casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 19):

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md)

**1/day each**: [commune](2-Mechanics/CLI/spells/commune.md) (as an action), [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md)

**2/day each**: [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md) (as a 6th-level spell), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md)

## Actions

***Multiattack.*** The pari makes three Mace attacks.

***Mace.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) bludgeoning damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) radiant damage.

***Disorienting Futures.*** The pari attempts to flood the mind of one creature it can see within 60 feet of itself with visions of the future. The target must succeed on a DC 19 Wisdom saving throw or take `dice:5d10|noform|avg|text(27)` (`5d10`) psychic damage and have disadvantage on attack rolls until the start of the pari's next turn.
```
^statblock