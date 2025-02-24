---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/farmland
- monster/environment/forest
- monster/environment/urban
- monster/size/small
- monster/type/construct
aliases: ["Gnarljak"]
---
# Gnarljak
*Source: Tome of Beasts 1 (2023 Edition) p. 212*  

*A bear trap springs to clacking life, ready to tear flesh.*

## Hopping Motion

All steel and springs, a gnarljak is easily mistaken for a simple bear trap when lying dormant. But once it starts hopping in pursuit of a target, it reveals its animated nature and its only motivation: destruction of living things.

## Endless Snapping

Gnarljaks are mindless. They do not grow tired. They exist only to pull creatures to the ground and chew through them, then turn around and chew through them again.

## Defensive Traps

Some try to use gnarljaks to guard treasures or booby-trap approaches to important locations, but their indiscriminate biting makes them quite dangerous to their owners as well. Certain monsters, such as redcaps and shadow fey, use gnarljaks with some regularity, and gnomes are very fond of making them part of a standard tunnel defense.

## Statblock

```ad-statblock
title: Gnarljak
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Gnarljak.webp#token)
*Small construct, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 88 (`16d6 + 32`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|21 (+5)|15 (+2)| 2 (-4)|14 (+2)| 1 (-5)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +4
- **Skills** Perception +5, Stealth +8
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 15
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 6

## Traits

***Construct Nature.*** The gnarljak doesn't require air, food, drink, or sleep.

***False Appearance.*** While the gnarljak remains motionless, it is indistinguishable from a normal bear trap.

## Actions

***Multiattack.*** The gnarljak makes one Gnawing Bite attack and two Chain Tail attacks, or it makes three Chain Tail attacks.

***Gnawing Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage, and the gnarljak attaches to the target. While attached, the gnarljak can't make Gnawing Bite attacks, and at the start of each of the gnarljak's turns, the target takes `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage.

The attached gnarljak moves with the target whenever the target moves, requiring none of the gnarljak's movement. It can detach itself by spending 5 feet of its movement on its turn. A creature, including the target, can use its action to detach the gnarljak by succeeding on a DC 16 Strength check.

***Chain Tail.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) bludgeoning damage.

## Bonus Actions

***Secure Tail.*** When within 10 feet of the ground, structure, wall, or other solid surface, the gnarljak can secure its tail spike on a point in the surface within 10 feet of it. While secured, the gnarljak can't be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), it can't move more than 10 feet from that point, and its Chain Tail attack's reach is reduced to 5 feet. If the gnarljak is attached to a creature while its tail is secured, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the gnarljak is no longer attached to it.
```
^statblock

## Environment

farmland, forest, urban