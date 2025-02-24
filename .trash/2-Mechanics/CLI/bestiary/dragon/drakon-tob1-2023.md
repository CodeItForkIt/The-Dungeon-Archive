---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/coastal
- monster/size/large
- monster/type/dragon
aliases: ["Drakon"]
---
# Drakon
*Source: Tome of Beasts 1 (2023 Edition) p. 147*  

*These winged snakes are coastal beasts and sometimes confused with true dragons or wyverns. They are neither, but quite deadly in their own right.*

## Searing Acid and Dissolving Gaze

The gaze of these winged snakes can paralyze and dissolve their victims. Drakon fangs do not deliver venom; volatile acid constantly burbles up from a drakon's stomach and enhances its attacks. A caustic drool clings to creatures they bite, and drakons can also belch clouds of searing vapor. Their lairs reek with acidic vapors and droplets of searing liquid.

## Coastal Beasts

Drakons lair along warm, largely uninhabited coasts, where they explore the shores and the coastal shelf, spending as much time above the waves as under them. Fortunately, they rarely travel far inland.

## Statblock

```ad-statblock
title: Drakon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Drakon.webp#token)
*Large dragon, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 105 (`14d10 + 28`)
- **Speed** 30 ft., fly 60 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|19 (+4)|15 (+2)| 2 (-4)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** acid
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** —
- **Challenge** 5

## Traits

***Amphibious.*** The drakon can breathe air and water.

***Dissolving Gaze.*** When a creature that can see the drakon's eyes starts its turn within 30 feet of the drakon, the drakon can force it to make a DC 13 Constitution saving throw if the drakon isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and can see the creature. On a failed save, the creature takes `dice:1d6|noform|avg|text(3)` (`1d6`) acid damage, its hp maximum is reduced by an amount equal to the acid damage it takes, and it is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the start of its next turn. This reduction lasts until the creature finishes a long rest. The creature dies if this effect reduces its hp maximum to 0.

Unless surprised, a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see the drakon until the start of its next turn, when it can avert its eyes again. If the creature looks at the drakon in the meantime, it must immediately make the save.

## Actions

***Multiattack.*** The drakon makes one Bite attack and one Tail attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage plus `dice:4d4|noform|avg|text(10)` (`4d4`) acid damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage.

***Acid Breath (Recharge 5-6).*** The drakon exhales acidic vapors in a 15-foot cone. Each creature in that area must make a DC 13 Constitution saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) acid damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

coastal