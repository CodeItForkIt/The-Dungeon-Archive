---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/8
- monster/environment/desert
- monster/size/huge
- monster/type/monstrosity/shapechanger
aliases: ["Dune Mimic"]
---
# Dune Mimic
*Source: Tome of Beasts 1 (2023 Edition) p. 268*  

*The sand surges and shifts, a sinkhole opens, and sandy tendrils reach out.*

## Enormous Forms

Though most commonly seen as dunes, a dune mimic can take the form of a date palm grove, a riverbank, an enormous boulder, or other large shapes in the landscape.

## A King's Guardians

Dune mimics were created by a forgotten king as guardians for his desert tomb. Somewhere, dozens of them guard vast wealth.

## Spread by Spores

Although not intended to reproduce, they began producing spores spontaneously and replicating themselves. Now they are spread across the deserts. Luckily for the other inhabitants, dune mimics reproduce just once per century

## Statblock

```ad-statblock
title: Dune Mimic
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dune%20Mimic.webp#token)
*Huge monstrosity (shapechanger), Neutral*

- **Armor Class** 13 (natural armor)
- **Hit Points** 168 (`16d12 + 64`)
- **Speed** 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)| 8 (-1)|18 (+4)| 9 (-1)|13 (+1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4
- **Senses** darkvision 60 ft., tremorsense 30 ft., passive Perception 14
- **Damage Immunities** acid, fire
- **Condition Immunities** [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 8

## Traits

***Adhesive (Object or Terrain Form Only).*** The dune mimic adheres to anything that touches it. A creature adhered to the dune mimic is also [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it (escape DC 15). Ability checks made to escape this grapple have disadvantage. The dune mimic can harden its outer surface, so only the creatures it chooses are affected by this trait.

***False Appearance (Object or Terrain Form Only).*** While the dune mimic remains motionless, it is indistinguishable from an ordinary sandy object or terrain feature.

***Grappler.*** The dune mimic has advantage on attack rolls against any creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it.

## Actions

***Multiattack.*** The dune mimic makes three Pseudopod attacks. It can replace one attack with a use of Engulf.

***Pseudopod.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 15 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) bludgeoning damage. If the dune mimic is in object or terrain form, the target is subjected to the mimic's Adhesive trait.

***Engulf.*** The dune mimic engulfs a Large or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The engulfed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and unable to breathe, and it must succeed on a DC 15 Constitution saving throw at the start of each of the mimic's turns or take `dice:3d6|noform|avg|text(10)` (`3d6`) slashing damage, as the creature is lacerated by the mimic's sand-coated form. If the mimic moves, any engulfed creatures move with it. The mimic can have no more than two creatures engulfed at a time.

## Bonus Actions

***Change Shape.*** The dune mimic transforms into a Huge sand- or gravel-covered object, shapes itself into a sandy or rocky terrain feature no larger than a 20-foot cube or transforms back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
```
^statblock

## Environment

desert