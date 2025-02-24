---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/badlands
- monster/environment/grassland
- monster/size/huge
- monster/type/monstrosity
aliases: ["Caustic Charger"]
---
# Caustic Charger
*Source: Tome of Beasts 1 (2023 Edition) p. 51*  

*This massive hexapod trundles along, the dangling tentacles festooning its squat body barely clearing the ground. A bony brow ridge set over beady eyes dominates its head.*

Caustic chargers are large, squat creatures that dwell in inhospitable locations, making such lands even more dangerous.

## Unusual Feeder

A caustic charger's odd, toothless snout makes it difficult to hunt and devour prey, but the creature has adapted by secreting a paralytic acid from its tentacles. To make the best use of its stubby tentacles, it charges its prey, striking with its powerful brow ridge to knock over the victim. Then, the charger stands over and dissolves the creature with its tentacles, slurping up the liquefied remains with its snout.

## Solitary Hunters

Caustic chargers are belligerent horrors that attack anything that opposes them, including others of their own kind. Once a year, two chargers become tolerant enough of each other to produce young, resulting in a score of gray eggs with hard shells.

## Ornery Steeds

While not very smart and exceedingly violent, caustic chargers can be persuaded to partner with smaller creatures that might not provide much nourishment but can offer a bounty of prey. Dust goblins are the most common creatures that partner with caustic chargers, with varying degrees of success.

## Statblock

```ad-statblock
title: Caustic Charger
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Caustic%20Charger.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 133 (`14d12 + 42`)
- **Speed** 30 ft., burrow 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|11 (+0)|16 (+3)| 4 (-3)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** acid
- **Languages** —
- **Challenge** 7

## Traits

***Straddler.*** The caustic charger can end its move in the space of a [prone](2-Mechanics/CLI/rules/conditions.md#Prone) Large or smaller creature. A creature standing up from [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in the same space as the charger can move to a space within 5 feet of the charger as part of standing up.

***Wastes Walk.*** Difficult terrain composed of rocks or sand doesn't cost the caustic charger extra movement.

## Actions

***Multiattack.*** The caustic charger makes two Ram attacks. It can replace one Ram attack with a Tentacles attack.

***Ram.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) bludgeoning damage, and if the target is a Large or smaller creature, it must succeed on a DC 15 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the charger moved at least 10 feet straight toward the target immediately before the hit, the target has disadvantage on the saving throw.

***Tentacles.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) bludgeoning damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) acid damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If the caustic charger attacks a target that is not in the charger's space, the target takes half the acid damage and has advantage on the saving throw.

## Bonus Actions

***Slurp.*** The caustic charger feeds on a creature [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) by its Tentacles attack. The target must succeed on a DC 15 Constitution saving throw or its hp maximum is reduced by half the amount of acid damage dealt by the Tentacles attack that caused the paralysis, and the charger regains hp equal to that amount. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hp maximum to 0.
```
^statblock

## Environment

badlands, grassland