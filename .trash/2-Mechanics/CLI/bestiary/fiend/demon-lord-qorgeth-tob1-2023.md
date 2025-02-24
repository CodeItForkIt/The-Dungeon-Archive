---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/23
- monster/environment/planar
- monster/size/gargantuan
- monster/type/fiend/demon
aliases: ["Demon Lord Qorgeth"]
---
# Demon Lord Qorgeth
*Source: Tome of Beasts 1 (2023 Edition) p. 80*  

*This massive undulating worm-like creature crushes trees and cracks stone.*

Qorgeth, the Writhing Prince, Pale Maw, the Devourer, is the lord of worms and decay. Its presence seeps into the world of mortals via the trails of worms and maggots through rotting flesh. The demon lord views all things that live, or once lived, as its property in the making. Everything becomes its food eventually.

## Fiendish Worm

An impossibly massive, pale-fleshed worm, Qorgeth's segmented body is road-mapped with pale veins of pink and blue. When it opens its massive maw, it reveals a writhing mass of smaller worms, many of which are adorned with wailing or enraged humanoid heads.

## Qorgeth's Lair

Qorgeth's lair is a tangled labyrinth of tunnels in the heart of its dark realm. The tunnels seem to twist and burrow through space itself rather than just the rock and soil surrounding them.

## Statblock

```ad-statblock
title: Demon Lord Qorgeth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Demon%20Lord%20Qorgeth.webp#token)
*Gargantuan fiend (demon), Chaotic Evil*

- **Armor Class** 21 (natural armor)
- **Hit Points** 370 (`20d20 + 160`)
- **Speed** 50 ft., burrow 50 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|29 (+9)| 6 (-2)|26 (+8)| 9 (-1)|22 (+6)|18 (+4)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +5, Constitution +15, Wisdom +13, Charisma +11
- **Skills** Perception +13
- **Senses** blindsight 120 ft., tremorsense 120 ft., passive Perception 23
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 23

## Traits

***Legendary Resistance (3/Day).*** If Qorgeth fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** Qorgeth has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** Qorgeth's weapon attacks are magical.

***Tunneler.*** Qorgeth can burrow through solid rock and leaves a 15-foot-diameter tunnel in its wake.

***Spellcasting.*** Qorgeth casts one of the following spells, requiring no material or somatic components and using Charisma as the spellcasting ability (spell save DC 19):

**At will**: [Evard's black tentacles](2-Mechanics/CLI/spells/evards-black-tentacles.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md)

**1/day each**: [earthquake](2-Mechanics/CLI/spells/earthquake.md), [teleport](2-Mechanics/CLI/spells/teleport.md) (self only)

**3/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [insect plague](2-Mechanics/CLI/spells/insect-plague.md) (biting worms)

## Actions

***Multiattack.*** Qorgeth makes one Bite attack, two Crush attacks, and one Stinger attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 10 ft., one target. *Hit:* `dice:2d12+9|noform|avg|text(22)` (`2d12 + 9`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 21 Dexterity saving throw or be swallowed by Qorgeth. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the worm, and it takes `dice:3d10|noform|avg|text(16)` (`3d10`) necrotic damage at the start of each of Qorgeth's turns.

If Qorgeth takes 50 damage or more in a single turn from a creature inside it, Qorgeth must succeed on a DC 25 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of Qorgeth. If Qorgeth dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape the corpse by spending 30 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Crush.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+9|noform|avg|text(20)` (`2d10 + 9`) bludgeoning damage, and if the target is a Large or smaller creature, it is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until Qorgeth moves. A creature, including the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature, can use an action to free the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature by succeeding on a DC 21 Strength check.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 15 ft., one target. *Hit:* `dice:4d6+9|noform|avg|text(23)` (`4d6 + 9`) piercing damage, and the target must make a DC 21 Constitution saving throw. On a failure, the target takes `dice:6d10|noform|avg|text(33)` (`6d10`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. On a success, the target takes half the damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). A creature that fails the saving throw by 10 or more is also [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

## Legendary Actions

***Shriek.*** Each creature within 60 feet of Qorgeth and that can hear the demon must succeed on a DC 21 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Death Roll (Costs 2 Actions).*** Qorgeth moves up to half its speed straight toward a creature and makes one Crush attack against the creature. Each object and structure between Qorgeth and the target takes `dice:6d10|noform|avg|text(33)` (`6d10`) bludgeoning damage.

***Devour (Costs 3 Actions).*** Qorgeth makes one Bite attack.

![Demon Lord Qorgeth](2-Mechanics/CLI/bestiary/legendary-group/demon-lord-qorgeth-tob1-2023.md)
```
^statblock

## Environment

planar