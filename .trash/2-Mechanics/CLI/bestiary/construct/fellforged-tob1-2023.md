---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/urban
- monster/size/medium
- monster/type/construct
aliases: ["Fellforged"]
---
# Fellforged
*Source: Tome of Beasts 1 (2023 Edition) p. 170*  

*A darkly foreboding intelligence glows behind this automaton's eyes, and its joints seep hissing green vapors.*

## Spectral Constructs

Fellforged are the castoffs of gearforged and clockworks production, given foul sentience when the construct bodies attract specters yearning to feel the corporeal world. The clockwork bodies trap the specters, but it gives them physical form. The specters twist the bodies to their own use, sometimes going so far as to destroy the body to harm the living. On rare occasions, other ghostly undead choose to inhabit such constructs, using the constructs as tools to enact their will in the living world at the cost of many of their natural abilities and defenses.

## Soldiers for Vampires

Fellforged often seek out greater undead as their masters. Vampires and liches are favorite leaders, but mummies and darakhul also make suitable commanders.

## Grave Speech

The fellforged's voice is echoing and sepulchral, unnerving most living creatures.

> [!note] Fellforged in Midgard
> 
> Dwarves of Grisal canton create fellforged to fight against undead haunts and spirits and melt them down afterwards, destroying wraiths, ghosts, and other incorporeal undead. The fellforged are also sometimes created by the Emerald Order and other cults seeking to give their evil masters a body and a shape with which to rule.
^fellforged-in-midgard

## Statblock

```ad-statblock
title: Fellforged
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Fellforged.webp#token)
*Medium construct, Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 135 (`18d8 + 54`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|12 (+1)|17 (+3)|12 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +5, Wisdom +5
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** acid, cold, fire, lightning
- **Damage Immunities** necrotic, poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 5

## Traits

***Construct Nature.*** The fellforged doesn't require air, food, drink, or sleep.

***Inhabiting Spirit.*** The fellforged is inhabited and animated by a specter. If the fellforged fails a saving throw against an effect that turns undead, the specter is expelled into an unoccupied space within 5 feet of the fellforged with the hp total it had before it was expelled. The specter otherwise uses the statistics of a specter.

Without its animating specter, the fellforged becomes dormant for 1 minute then crumbles to pieces and is destroyed. The expelled specter can reinhabit the dormant fellforged as a bonus action while within 5 feet of the fellforged, making it active again and using the specter's current hp as the fellforged's hp total.

***Sunlight Sensitivity.*** While in sunlight, the fellforged has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The fellforged makes two Necrotic Slam attacks.

***Necrotic Slam.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) bludgeoning damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or its hp maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hp maximum to 0.

## Bonus Actions

***Burst Gears.*** The specter within the fellforged strains the construct's body, sending broken springs and gears flying. Each creature within 5 feet of the fellforged must make a DC 14 Dexterity saving throw, taking `dice:2d6|noform|avg|text(7)` (`2d6`) piercing damage on a failed save, or half as much damage on a successful one. Each time the fellforged uses this bonus action, its speed is reduced by 5 feet, and it can't use this bonus action if its speed is 0. Its speed returns to normal when it finishes a long rest.
```
^statblock

## Environment

urban