---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/desert
- monster/environment/grassland
- monster/size/large
- monster/type/aberration
aliases: ["Tusked Skyfish"]
---
# Tusked Skyfish
*Source: Tome of Beasts 1 (2023 Edition) p. 372*  

*This creature looks like an enormous flying jellyfish, with long, wicked tusks curving from its gaping mouth and tentaclewhiskers trailing behind it.*

## Alchemical Flotation

These aerial jellyfish waft through the air like balloons, suspended by internal alchemical reactions. This mode of movement takes them vertically when they wish or allows them to drift with the winds. They can reach altitudes of 30,000 feet.

## Shocking Tendrils

Tusked skyfish catch slow-moving or inattentive prey in their tentacles, and they sometimes fish in shallow lakes and streams. They can suppress their natural electrical charge, allowing them to manipulate objects or interact with other creatures safely.

## Slow Mounts

When fitted with special, electricity-resistant saddles, tusked skyfish can be ridden without harming their riders, although their slow speed makes them most suitable for casual excursions or unhurried long-distance travel. Genies, their offspring, and their servitors seem to find tusked skyfish congenial beasts of burden.

## Statblock

```ad-statblock
title: Tusked Skyfish
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Tusked%20Skyfish.webp#token)
*Large aberration, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 102 (`12d10 + 36`)
- **Speed** 5 ft., fly 20 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|12 (+1)|17 (+3)| 3 (-4)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Immunities** lightning
- **Languages** —
- **Challenge** 4

## Traits

***Electrified Tendrils.*** A creature that touches the skyfish or hits it with a melee attack while within 5 feet of it takes `dice:1d6|noform|avg|text(3)` (`1d6`) lightning damage. In addition, a creature that starts its turn beneath the skyfish while the skyfish is hovering takes `dice:1d6|noform|avg|text(3)` (`1d6`) lightning damage, provided the creature is within 15 feet of the skyfish.

***Mobile Grappler.*** While grappling a creature, the tusked skyfish can move at its full speed, carrying the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) creature along with it.

## Actions

***Multiattack.*** The tusked skyfish makes one Gore attack and one Electrified Tentacles attack.

***Gore.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage.

***Electrified Tentacles.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 10 ft., one creature. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13) if it is a Medium or smaller creature. Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and takes `dice:4d6|noform|avg|text(14)` (`4d6`) lightning damage at the start of each of its turns, and the skyfish can't use its Electrified Tentacles on another target.

***Stench Spray (Recharge 5-6).*** The tusked skyfish sprays foul‑smelling liquid in a 20-foot line that is 5 feet wide. Each creature in that line must make a DC 13 Constitution saving throw. On a failure, a creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. On a success, a creature takes half the damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). If the saving throw fails by 5 or more, the creature falls [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. The [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) creature wakes up if it takes damage or if another creature takes an action to shake it awake. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

desert, grassland