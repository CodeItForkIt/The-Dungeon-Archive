---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1-4
- monster/environment/underdark
- monster/environment/urban
- monster/size/tiny
- monster/type/monstrosity/shapechanger
aliases: ["Map Mimic"]
---
# Map Mimic
*Source: Tome of Beasts 1 (2023 Edition) p. 269*  

*A treasure map flaps as if caught in a strong wind. It suddenly splits open, revealing a fanged mouth and face.*

## Mimic Spawn

Mimic adhesive is not just a powerful means of trapping prey, it also contains millions of microscopic larvae that feed on flesh. Most of the larvae are consumed by the mimic when it eats. Mimics are either unaware of this, or they're indifferent to the fact that they routinely cannibalize their own offspring. A few larvae survive by adhering to the clothing or equipment of someone who escaped from a full-grown mimic's attack. These larvae hitch a ride, their host taking them far from the dungeon, cavern, or ruin of their birth. There, they drop off and grow into wormlike mimic young called map mimics. In time, map mimics grow into typical mimics.

## Smaller than a Dinner Plate

Map mimics are too small to mimic the types of objects their parent does, but they still deceive prey by altering their forms. They can assume the shape, texture, and coloration of anything up to the size of a dinner plate.

## Paper Scrolls

Their preferred form is parchment paper. They can display the path they've followed on their hide, complete with important landmarks. In this form, they curl up and wait inside bottles, or in the clutches of a corpse in plain view, until an unsuspecting adventurer discovers them. If the mimic is hungry, it attacks and attaches to the finder's face. Otherwise, it continues its charade as a map, eventually leading the reader back to the parent mimic.

## Statblock

```ad-statblock
title: Map Mimic
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Map%20Mimic.webp#token)
*Tiny monstrosity (shapechanger), Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 22 (`5d4 + 10`)
- **Speed** 30 ft., fly 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|15 (+2)|14 (+2)| 5 (-3)|13 (+1)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Immunities** acid
- **Condition Immunities** [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 1/4

## Traits

***False Appearance (Object Form Only).*** While the mimic remains motionless, it is indistinguishable from an ordinary object.

***Life Path.*** Regardless of the form it takes, the map mimic can make a map on its surface (no action required) that shows the route it has traveled since it left its parent mimic. The map shows terrain features and landmarks of where it has been, but doesn't show the names of those places.

## Actions

***Pseudopod.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage, and it attaches to the target. While attached, the mimic can't attack, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), and at the start of each of the mimic's turns, the target takes `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage.

The attached mimic moves with the target whenever the target moves, requiring none of the mimic's movement. It can detach itself by spending 5 feet of its movement on its turn. A creature, including the target, can use its action to detach the mimic by succeeding on a DC 8 Strength check.

## Bonus Actions

***Change Shape.*** The mimic transforms into a Tiny object or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
```
^statblock

## Environment

underdark, urban