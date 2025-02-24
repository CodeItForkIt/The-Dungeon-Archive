---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/desert
- monster/size/gargantuan
- monster/type/plant
aliases: ["Vesiculosa"]
---
# Vesiculosa
*Source: Tome of Beasts 1 (2023 Edition) p. 385*  

*A glittering pool stands among lush and verdant fruiting plants.*

## Underground Oasis

A vesiculosa is a huge, burrowing pitcher plant that dwells in deserts and oases, spurring nearby growth and luring in prey with soporific scents and tainted water. A vesiculosa's body is buried in the ground, with only its roots in the open in ropy tangles. It leaves the mouth of its water-filled central pitcher open on the surface of the ground, looking like a small oasis. When creatures fall to its sleep-inducing water, the vesiculosa uses its roots to pull them into the soil, waiting for them to die before feasting on the nutrients left by the decaying flesh.

## Rich Sapphire Heartvine

A vesiculosa's heartvine resembles a lump of sapphire and is highly prized by alchemists. It can be reached with an hour or two of hard digging once the plant has been killed.

## Statblock

```ad-statblock
title: Vesiculosa
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Vesiculosa.webp#token)
*Gargantuan plant, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 232 (`16d20 + 64`)
- **Speed** 0 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|15 (+2)|19 (+4)| 2 (-4)|14 (+2)| 2 (-4)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +6
- **Senses** tremorsense 60 ft., passive Perception 16
- **Damage Resistances** bludgeoning, fire, piercing
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 11

## Traits

***Oasis Appearance.*** While the vesiculosa remains motionless and partially submerged on the surface of sand or soil, it is indistinguishable from a small oasis or pond. The vesiculosa's pitcher produces enough water for plants to grow around it, provided the vesiculosa remains in the area for an extended period of time. A creature that eats a fruit from a plant growing in the vesiculosa's water is affected by the Sweet Water trait as if it drank the water.

***Sweet Fragrance.*** When a creature that can smell the vesiculosa's sweet fragrance starts its turn within 30 feet of the vesiculosa, the creature must succeed on a DC 16 Wisdom saving throw or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) for 1 minute. While [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), the creature must move on its turn toward the vesiculosa by the safest available route to get within 5 feet of the plant and drink its water. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the vesiculosa's Sweet Fragrance for the next 24 hours.

***Sweet Water.*** A creature that drinks water from the vesiculosa's pitcher regains 5 `dice:2d4|noform|avg` (`2d4`) hp, reduces its [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) level by 1, and must succeed on a DC 16 Constitution saving throw or fall [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for 10 minutes. An [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) creature wakes up if it takes damage or if another creature takes an action to shake it awake. Drinking the water provides a creature enough nourishment to sustain it for one day.

## Actions

***Multiattack.*** The vesiculosa makes four Root or Spit Sweet Water attacks.

***Root.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one creature. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until the grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The vesiculosa has four roots, each of which can grapple only one target.

***Spit Sweet Water.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 20/60 ft., one creature. *Hit:* `dice:3d10+2|noform|avg|text(18)` (`3d10 + 2`) bludgeoning damage, and the target must succeed on a DC 16 Constitution saving throw or fall [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) for 1 minute. The target wakes up if it takes damage or if another creature takes an action to shake it awake.

## Bonus Actions

***Bury.*** One creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the vesiculosa is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), dragged into the ground, and buried just below the surface, ending the grapple. The buried creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and unable to breathe or stand up. A creature, including the buried creature, can take its action to free the buried creature by succeeding on a DC 16 Strength check. This bonus action doesn't wake a creature that is [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) from the vesiculosa's Sweet Water trait or Spit Sweet Water action.
```
^statblock

## Environment

desert