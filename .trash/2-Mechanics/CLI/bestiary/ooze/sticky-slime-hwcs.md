---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/1-8
- monster/size/medium
- monster/type/ooze
aliases: ["Sticky Slime"]
---
# Sticky Slime
*Source: Humblewood Campaign Setting p. 188*  

Deep in the murky marshes of the Mokk Fields, where water lays stagnant and the stench of decay permeates all, the worlds of life and death intertwine. Within this ominous mire lurk some of the most unusual natural predators in Humblewood. Collectively known as "slimes", these oozes move slowly through the muck, well-camouflaged by the dark and pungent waters, waiting to devour any hapless being that wanders within reach.

Slimes are easily provoked, and while it isn't difficult to outrun one, some who have strayed into a slime's territory only find out too late that they have been detected. Fortunately for many swampland travelers, slimes have a slow metabolism, and can go without feeding for long periods.

In addition to being an important part of the ecosystem, many slimes are either naturally magical, or yield organic materials which are in high demand among mages, scholars, and researchers. While slime hunting is a dangerous undertaking, the perch of Winnowing Reach was built on the labor of so-called "slime-wranglers", whose skill collecting valuable residue from live slimes is directly responsible for transforming the once minor outpost into a thriving site for scholarly innovation.

Three main types of slimes have been classified, but as magical creatures with strange properties, it's speculated that more elusive slime species might exist somewhere in the remote swamps. The three documented types are: [caustic slimes](2-Mechanics/CLI/bestiary/ooze/caustic-slime-hwcs.md), [shifting slimes](2-Mechanics/CLI/bestiary/ooze/shifting-slime-hwcs.md), and [sticky slimes](2-Mechanics/CLI/bestiary/ooze/sticky-slime-hwcs.md).

## Sticky Slime

A semi-solid type of ooze, sticky slimes are far more robust than their cousins. Experienced slime wranglers know never to attack them directly with weapons. The rubbery bodies of sticky slimes can suck a blade out of a wielder's hands, leaving the attacker unarmed.

### True to Form

Sticky slimes are wholly described by their name. They leave a trail of extremely thick adhesive residue in their wake. While the residue itself is harmless, it can trap adventurers where they stand, and sticky slimes tend to live in proximity of far more threatening monsters.

## Statblock

```ad-statblock
title: Sticky Slime
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Sticky%20Slime.webp#token)
*Medium ooze, Unaligned*

- **Armor Class** 6
- **Hit Points** 13 (`2d8 + 4`)
- **Speed** 15 ft., climb 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)| 3 (-4)|14 (+2)| 1 (-5)| 6 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Damage Resistances** bludgeoning, piercing, slashing
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 1/8

## Traits

***Amorphous.*** The Caustic Slime can move through a space as narrow as 1 inch wide without squeezing.

***Slime Trail.*** The slime leaves a trail of ooze behind it that remains tacky for up to 15 minutes. A creature that steps in the ooze must succeed a DC 12 Strength saving throw or become [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). A creature may attempt the saving throw again at the end of each of its turns, ending the effect on a success.

***Mucus.*** When the slime is hit by a melee attack, the attacker must succeed on a DC 12 Strength saving throw or their weapon becomes stuck in the slime. The weapon can be wrenched out by using an action to make a Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check against the same DC, freeing the weapon on a success. All weapons stuck in the slime can be retrieved once the slime is slain.

## Actions

***Psuedopod.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) bludgeoning damage.
```
^statblock