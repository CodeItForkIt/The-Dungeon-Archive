---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/any
- monster/environment/planar
- monster/size/tiny
- monster/type/celestial
aliases: ["Uraeus"]
---
# Uraeus
*Source: Tome of Beasts 1 (2023 Edition) p. 373*  

*A sleek serpent wends through the air, held aloft on bronze-feathered wings. The flying cobra flares its hood and hisses, hurling a spray of orange sparks from its fanged mouth.*

Uraeuses resemble vibrantly colored cobras. The serpent's scales are the rich, gold-flecked blue of lapis lazuli and its eyes gleam white. However, its most distinguishing feature is its pair of feathery, bronze wings. It glides gracefully through the air with a deliberate vigilance that reveals its intelligence. A uraeus grows up to three feet long, and weighs around five pounds.

## Divine Protectors

Uraeuses are celestial creatures that carry a spark of divine fire within them, and they thirst for purpose when they arrive on the Material Plane. Whether the creature was deliberately summoned or found its way to the Material Plane through other means, a uraeus is created to protect. Once it finds a worthy charge, it devotes its fiery breath and searing venom to protecting that ward. A uraeus is fanatically loyal to the creature it protects. Only gross mistreatment or vicious evil can drive a uraeus to break its bond and leave.

## Statblock

```ad-statblock
title: Uraeus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Uraeus.webp#token)
*Tiny celestial, Lawful Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 40 (`9d4 + 18`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|15 (+2)|14 (+2)|10 (+0)|14 (+2)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +4, Charisma +1
- **Skills** Perception +4
- **Senses** blindsight 10 ft., passive Perception 14
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Celestial and Common but can't speak
- **Challenge** 2

## Traits

***Flyby.*** The uraeus doesn't provoke opportunity attacks when it flies out of an enemy's reach.

***Magic Resistance.*** The uraeus has advantage on saving throws against spells and other magical effects.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage, and the target must succeed on a DC 12 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage at the start of each of its turns. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Spit Fire.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 20/60 ft., one target. *Hit:* `dice:4d6+2|noform|avg|text(16)` (`4d6 + 2`) fire damage.

***Searing Breath (Recharge 5-6).*** The uraeus exhales a 15-foot cone of fire. Each creature in the area must make a DC 12 Dexterity saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) fire damage on a failed save, or half as much damage on a successful one.

## Bonus Actions

***Ward Bond.*** The uraeus forms a magical bond with a willing creature within 5 feet of it. While bonded, the uraeus and its ward know the distance and direction to each other and the general state of each other's health, even if the two are on different planes of existence. The bond lasts until the uraeus or its ward dies, until the uraeus ends it as a bonus action, or until the uraeus uses this bonus action to create a bond with another creature.

## Reactions

***Bonded Savior.*** When the uraeus's bonded ward takes damage, the uraeus prevents the ward from taking the damage and loses hp equal to that amount instead, regardless of the type of damage dealt.
```
^statblock

## Environment

any, planar