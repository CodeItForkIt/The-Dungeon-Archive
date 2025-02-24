---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ditlcot
- monster/cr/4
- monster/size/small
- monster/type/elemental
aliases: ["Pech"]
---
# Pech
*Source: Descent into the Lost Caverns of Tsojcanth p. 16*  

Pechs are slight, bipedal diggers from the Elemental Plane of Earth. They have a knack for finding weak points in buildings, objects, and raw materials, making them phenomenal excavators—and, if the occasion calls for it, sappers and saboteurs. Pechs enjoy sculpting and carving vast networks of tunnels and warrens, where they live in clans and mine precious metals and gems.

Small and lithe, pechs have long, thin limbs and broad feet. Their large, pupilless eyes are sensitive to bright light, which they avoid, and they find sunlight nauseating. Their skin displays a spectrum of color and texture as varied as that of clay, earth, and stone.

A single pech can draw on the magic of the Elemental Plane of Earth to shape stone to its will, but pechs are stronger together than alone. When in groups, pechs can combine their magic to conjure great curtains of stone and infuse creatures with the fortitude of elemental earth.

```ad-statblock
title: Pech
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DitLCoT/Pech.webp#token)
*Small elemental, typically  Neutral Good*

- **Armor Class** 17 (natural armor)
- **Hit Points** 82 (`11d6 + 44`)
- **Speed** 30 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|11 (+0)|18 (+4)|11 (+0)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +6, Wisdom +4
- **Skills** Athletics +6, Perception +4, Survival +4
- **Senses** darkvision 120 ft., tremorsense 120 ft., passive Perception 14
- **Condition Immunities** [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified)
- **Languages** Common, Terran
- **Challenge** 4

## Traits

***Magic Resistance.*** The pech has advantage on saving throws against spells and other magical effects.

***Sunlight Sensitivity.*** While in sunlight, the pech has disadvantage on attack rolls.

***Communal Spellcasting (2/Day).*** The pech works with three or more pechs to cast spells, requiring no spell components and using Wisdom as the spellcasting ability (save DC 12). If at least three other pechs are within 30 feet of it, the pech can cast [Wall of Stone](2-Mechanics/CLI/spells/wall-of-stone.md). If at least seven other pechs are within 30 feet of it, it can cast [Greater Restoration](2-Mechanics/CLI/spells/greater-restoration.md). Each other pech involved in casting the spell can't have the incapacitated condition and must have at least one use of Communal Spellcasting remaining, which it must immediately expend to participate (no action required).

**2/day**: [wall of stone](2-Mechanics/CLI/spells/wall-of-stone.md), [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md)

***Stone Shape (3/Day).*** The pech casts [Stone Shape](2-Mechanics/CLI/spells/stone-shape.md), requiring no spell components and using Wisdom as the spellcasting ability.

**3/day each**: [stone shape](2-Mechanics/CLI/spells/stone-shape.md)

## Actions

***Multiattack.*** The pech makes two Fortified Pickaxe attacks. If it hits a Large or smaller creature with both attacks, the target must succeed on a DC 14 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Fortified Pickaxe.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) force damage. If the target is a Construct or an object, the attack is automatically a critical hit.
```
^statblock