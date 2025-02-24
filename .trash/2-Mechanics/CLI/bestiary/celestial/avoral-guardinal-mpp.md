---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/9
- monster/size/medium
- monster/type/celestial
aliases: ["Avoral Guardinal"]
---
# Avoral Guardinal
*Source: Morte's Planar Parade p. 32, Sigil and the Outlands*  

Avorals are eagle-like bipeds with winged arms and keen, golden eyes. Prone to wander, these avian Celestials leave Elysium more frequently than their counterparts, meandering across the Outlands to wherever the winds might take them. Solitary scouts and skirmishers, avorals are nimble aerial combatants, able to swiftly dive at foes from the heavens and tear into them with razor-sharp talons.

## Guardinals

Nomadic and peaceful, guardinals are animalistic Celestials who hail from Elysium. Guardinals resemble Humanoids with bestial traits. In their daily interactions, guardinals embody the beauty, calm, and righteousness of their home plane. Guardinals can be found throughout the Outlands, especially in Ecstasy, the gate-town to Elysium, and in Faunel, the gate-town to the Beastlands.

While guardinals are usually friendly and slow to anger, their supernatural virtue puts them at odds with the evil beings of the Lower Planes. Guardinals abhor wickedness and strike out against injustice and villainy without hesitation, determined to eradicate forces that threaten beauty and peace.

## Statblock

```ad-statblock
title: Avoral Guardinal
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Avoral%20Guardinal.webp#token)
*Medium celestial, typically  Neutral Good*

- **Armor Class** 16 (natural armor)
- **Hit Points** 172 (`23d8 + 69`)
- **Speed** 30 ft., fly 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|19 (+4)|17 (+3)|16 (+3)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Charisma +8
- **Skills** Perception +11, Religion +7
- **Senses** darkvision 120 ft., passive Perception 21
- **Damage Resistances** radiant
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Celestial, Common
- **Challenge** 9

## Traits

***Dive Attack.*** If the avoral is flying, dives at least 30 feet in a straight line toward a Medium or smaller creature, and ends within 5 feet of it, that creature must succeed on a DC 15 Strength saving throw or take `dice:4d6|noform|avg|text(14)` (`4d6`) piercing damage and have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Flyby.*** The avoral doesn't provoke an opportunity attack when it flies out of an enemy's reach.

***Spellcasting.*** The avoral casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**1/day each**: [command](2-Mechanics/CLI/spells/command.md), [hold person](2-Mechanics/CLI/spells/hold-person.md)

## Actions

***Multiattack.*** The avoral makes two Talon attacks. It can replace one attack with a use of Spellcasting.

***Talon.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage plus `dice:2d12|noform|avg|text(13)` (`2d12`) radiant damage.
```
^statblock