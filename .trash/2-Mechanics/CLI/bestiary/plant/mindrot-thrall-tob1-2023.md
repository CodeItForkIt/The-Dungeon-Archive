---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/badlands
- monster/environment/underdark
- monster/size/medium
- monster/type/plant
aliases: ["Mindrot Thrall"]
---
# Mindrot Thrall
*Source: Tome of Beasts 1 (2023 Edition) p. 270*  

*A heavily cloaked figure reeks of decay, spreading a floating cloud of spores with every step.*

## Fungal Rot

Mindrot fungus is an intelligent hive-mind parasite that consumes creatures from the inside out. When inhaled, mindrot spores enter the brain through the bloodstream. As the fungus grows, it dissolves the host's body and slowly replaces the creature's flesh with its own. The fungus's first target is the motor function of the brain. It takes control of the creature's movement while the victim is still alive and conscious, leaving the victim trapped within its own body. Indeed, sensory awareness may be the last function that the fungus attacks. Eventually, even the victim's skin and muscle are replaced with fungal fibers. At that point, the affected creature no longer looks like its former self. Such a newly born mindrot thrall conceals its alarming appearance under heavy robes or cloaks so it can travel without causing alarm.

## Spore Blisters

A thrall's skin is taut and waxy. Blisters form just beneath the surface, and when they grow as large as a child's fist they burst, releasing a spray of spores. It seeks to infect as many new victims as possible during the few weeks that it survives in humanoid form. At the end of that time, the thrall shrivels to a dried, vaguely humanoid husk. Even a dead mindrot thrall remains dangerous. Its half-formed spore blisters can remain infectious for months.

## Dimensional Horrors

Wizards hypothesize the fungus was brought to the mortal world's wastelands by a shambling horror crossing through a dimensional portal. The remoteness of the wasteland is likely why the mindrot fungus hasn't destroyed whole cities, though someday it might find a more fertile breeding ground.

## Statblock

```ad-statblock
title: Mindrot Thrall
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Mindrot%20Thrall.webp#token)
*Medium plant, Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|17 (+3)|11 (+0)|14 (+2)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +5
- **Skills** ⏤
- **Senses** tremorsense 30 ft., passive Perception 12
- **Damage Immunities** acid, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common but can't speak
- **Challenge** 3

## Traits

***Fungal Aura.*** A creature that starts its turn within 5 feet of a mindrot thrall must succeed on a DC 13 Constitution saving throw or become infected with the mindrot disease.

***Mindrot.*** A creature infected with this disease manifests symptoms in `dice:1d4|noform|avg` (`1d4`) days after infection, which include migraines and muscle weakness. Until the disease is cured, at the end of each long rest, the infected creature must succeed on a DC 13 Constitution saving throw or take `dice:2d8|noform|avg|text(9)` (`2d8`) acid damage, and its hp maximum is reduced by that amount. This reduction lasts until the creature finishes a long rest after the disease is cured. The creature dies if the disease reduces its hp maximum to 0. One day after the creature dies, it rises as a mindrot thrall. A creature that succeeds on two saving throws recovers from the disease.

## Actions

***Multiattack.*** The mindrot thrall makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) slashing damage.

***Spore Breath (Recharge 4-6).*** The thrall exhales a blast of acidic spores from its rotten lungs in a 15-foot cone. Each creature in the area must make a DC 13 Dexterity saving throw. On a failure, a creature takes `dice:4d8|noform|avg|text(18)` (`4d8`) acid damage and is infected with the mindrot disease (see the Mindrot trait). On a success, a creature takes half the damage and isn't infected.
```
^statblock

## Environment

badlands, underdark