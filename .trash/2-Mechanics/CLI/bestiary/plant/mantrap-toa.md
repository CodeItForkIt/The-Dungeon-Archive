---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/1
- monster/size/large
- monster/type/plant
aliases: ["Mantrap"]
---
# Mantrap
*Source: Tomb of Annihilation p. 227*  

A mantrap is a giant carnivorous plant that resembles an oversized flytrap. To attract prey, the mantrap releases a pollen that magically draws creatures to it. Though it will snap its leafy jaws shut around any warm-blooded creature that strays within its reach, it prefers humanoid prey.

```ad-statblock
title: Mantrap
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Mantrap.webp#token)
*Large plant, Unaligned*

- **Armor Class** 12
- **Hit Points** 45 (`7d10 + 7`)
- **Speed** 5 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|12 (+1)| 1 (-5)|10 (+0)| 2 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** tremorsense 30 ft., passive Perception 10
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 1

## Traits

***Attractive Pollen (1/Day).*** When the mantrap detects any creatures nearby, it can use its reaction to release pollen out to a radius of 30 feet. Any beast or humanoid within the area must succeed on a DC 11 Wisdom saving throw or be forced to use all its movement on its turns to get as close to the the mantrap as possible. An affected target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***False Appearance.*** While the mantrap remains motionless, it is indistinguishable from an ordinary tropical plant.

## Actions

***Engulf.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one Medium or smaller creature. *Hit:* The target is trapped inside the mantrap's leafy jaws. While trapped in this way, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), has total cover from an attacks and other effects outside the mantrap, and takes `dice:4d6|noform|avg|text(14)` (`4d6`) acid damage at the start of each of the target's turns. If the mantrap dies, the creature inside it is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it. A mantrap can engulf only one creature at a time.
```
^statblock