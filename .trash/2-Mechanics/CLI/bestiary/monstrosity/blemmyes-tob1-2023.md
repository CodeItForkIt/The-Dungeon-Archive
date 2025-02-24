---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/8
- monster/environment/farmland
- monster/environment/forest
- monster/environment/hill
- monster/size/large
- monster/type/monstrosity
aliases: ["Blemmyes"]
---
# Blemmyes
*Source: Tome of Beasts 1 (2023 Edition) p. 37*  

*This headless giant has a large mouth in its chest with eyes bulging out on either side of it.*

## Always Hungry

Blemmyes are brutes that savor humanoid flesh, and they see all humanoids as potential meals. Some even have the patience to tend groups of humans, goblins, or halflings like unruly herds, farming them for food and fattening them up for maximum succulence.

## Cannibals

So great is their hideous hunger that blemmyes are not above eating their own kind; they cull and consume the weakest specimens of their people when other food is scarce. The most terrible habit of these monsters is that they seldom wait for their food to die, or even for a battle to conclude, before launching into a grisly feast.

## Statblock

```ad-statblock
title: Blemmyes
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Blemmyes.webp#token)
*Large monstrosity, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 168 (`16d10 + 80`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|13 (+1)|20 (+5)| 7 (-2)|12 (+1)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Intimidation +3
- **Senses** darkvision 60 ft., passive Perception 11
- **Languages** Giant
- **Challenge** 8

## Traits

***Carnivorous Compulsion.*** At the start of each of its turns, if the blemmyes can see an [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) creature, the blemmyes must succeed on a DC 11 Wisdom saving throw or spend its next turn moving toward and attacking that creature.

## Actions

***Multiattack.*** The blemmyes makes one Bite attack and two Slam attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+5|noform|avg|text(19)` (`4d6 + 5`) piercing damage. If the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and a Medium or smaller creature, the target is swallowed. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the blemmyes, and it takes `dice:4d6|noform|avg|text(14)` (`4d6`) acid damage at the start of each of the blemmyes' turns. The blemmyes can have only one target swallowed at a time.

If the blemmyes takes 20 damage or more on a single turn from the swallowed creature, the blemmyes must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 5 feet of the blemmyes. If the blemmyes dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Slam.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage. If the target is a creature, it must succeed on a DC 16 Wisdom saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.

***Rock.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 30/120 ft., one target. *Hit:* `dice:4d10+5|noform|avg|text(27)` (`4d10 + 5`) bludgeoning damage. If the target is a creature, it must succeed on a DC 16 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of its next turn.
```
^statblock

## Environment

farmland, forest, hill