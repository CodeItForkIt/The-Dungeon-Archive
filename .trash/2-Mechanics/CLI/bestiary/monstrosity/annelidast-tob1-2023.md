---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/12
- monster/environment/desert
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/environment/underdark
- monster/environment/urban
- monster/size/huge
- monster/type/monstrosity
aliases: ["Annelidast"]
---
# Annelidast
*Source: Tome of Beasts 1 (2023 Edition) p. 21*  

*The massive worm erupted from the earth, crushing all near it and scooping up the remains.*

An annelidast is a gigantic worm that slumbers for decades at a time in the bowels of the earth, where the rock itself radiates primordial magic. Over millennia, they have grown lead-plated carapaces to shield themselves from the magic.

## Unique Predation

Each century, an annelidast wakes and travels to the surface to feed. The worm eats through baleen-like teeth that help it filter feed through the earth as it travels underground, but this method of eating requires it to pulverize larger surface prey before consumption.

## Sleeping Plague

The annelidast's exterior is saturated with the primordial magic of its deep-earth home. When an annelidast nears waking, it burrows toward the surface in a dreamlike state, following vibrations in the earth made by living creatures. As it lies just beneath the surface rousing from its slumber, the primordial magic infusing it radiates outward and sickens creatures living there, making them easier prey when it fully wakes.

## Statblock

```ad-statblock
title: Annelidast
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Annelidast.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 184 (`16d12 + 80`)
- **Speed** 40 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|10 (+0)|20 (+5)| 1 (-5)|10 (+0)| 4 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +9, Wisdom +4
- **Skills** ⏤
- **Senses** tremorsense 120 ft., passive Perception 10
- **Damage Resistances** lightning
- **Damage Immunities** bludgeoning, poison from nonmagical attacks
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 12

## Traits

***Deep Earth Dweller.*** The annelidast doesn't require air.

***Primordial Aura.*** A creature that starts its turn within 30 feet of the annelidast must succeed on a DC 17 Constitution saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage. A creature that finishes a long rest within 1,000 feet of the annelidast must succeed on a DC 17 Constitution saving throw or develop tumors across its body and become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the tumors are removed by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or similar magic.

***Tunneler.*** The annelidast can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.

## Actions

***Multiattack.*** The annelidast makes three Slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:2d12+8|noform|avg|text(21)` (`2d12 + 8`) bludgeoning damage, and if the target is a creature, it must succeed on a DC 17 Strength saving throw or be pushed up to 15 feet away from the annelidast. A creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the annelidast automatically succeeds on this saving throw.

***Crush (Recharge 5-6).*** The annelidast launches most of its massive bulk into the air and crashes down on the ground in a 20-foot line that is 10 feet wide. It then retracts itself into a space along that line and can occupy the space of one or more Large or smaller creatures. Each creature in the line must make a DC 17 Dexterity saving throw. On a failure, a creature takes `dice:7d12|noform|avg|text(45)` (`7d12`) bludgeoning damage, is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) while it shares a space with the annelidast, as it is pinned beneath the annelidast's body. On a success, a creature takes half the damage, isn't knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), and is pushed out of the annelidast's space into an unoccupied space of the creature's choice within 5 feet of the annelidast. A creature, including the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature, can take its action to free the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature by succeeding on a DC 17 Strength check. If the annelidast burrows along the surface of the earth at least 20 feet before using this action, creatures in the line have disadvantage on the saving throw.

## Reactions

***Defensive Recoil.*** When the annelidast takes damage, it can make one Slam attack against a creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it.
```
^statblock

## Environment

desert, forest, grassland, hill, mountain, underdark, urban