---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/planar
- monster/size/small
- monster/type/elemental
aliases: ["Firegeist"]
---
# Firegeist
*Source: Tome of Beasts 1 (2023 Edition) p. 188*  

*Wisps of black smoke and spots of bright flame coalesce into a vaguely humanoid shape.*

## Elemental Echoes

When a fire elemental meets its destruction in a particularly humiliating fashion, particularly by humanoids, while summoned away from its home plane, its remains transform into a firegeist. Malevolent and resentful, they exist for revenge.

## Indiscriminate Arsonists

Firegeists are not adept at telling one humanoid from another, and they are satisfied with burning any similar creature, providing the creature is flammable.

## Brighter Light, Darker Smoke

A firegeist can shine brightly or be primarily smoky and dark, as it wishes. It always sheds a little light.

## Statblock

```ad-statblock
title: Firegeist
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Firegeist.webp#token)
*Small elemental, Neutral Evil*

- **Armor Class** 14
- **Hit Points** 82 (`15d6 + 30`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|18 (+4)|14 (+2)| 4 (-3)|16 (+3)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +5
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Ignan
- **Challenge** 2

## Traits

***Elemental Nature.*** The firegeist doesn't require air, food, drink, or sleep.

***Hide By Firelight.*** The firegeist has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in fire or in areas lit by nonmagical fire.

***Magical Light Sensitivity.*** While in an area of light created by a spell or other magical effect, the firegeist has disadvantage on attack rolls and ability checks.

***Variable Illumination.*** The firegeist sheds dim light in a 5- to 20-foot radius. It can alter the radius as a bonus action.

***Water Susceptibility.*** For every 5 feet the firegeist moves in water, or for every gallon of water splashed on it, it takes 1 cold damage.

## Actions

***Burning Slam.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage. If the target is a flammable object, it ignites. If the target is a creature, the target must succeed on a DC 13 Dexterity saving throw or ignite. Until a creature takes an action to douse the fire, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage at the start of each of its turns.

***Burning Terror (Recharge 5-6).*** The firegeist assaults the mind of one creature it can see within 30 feet of it with the painful, humiliating memory of the firegeist's first death. The target must make a DC 13 Wisdom saving throw. On a failure, the target takes `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage and is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. On a success, the target takes half the damage and isn't [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened). While [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), the creature takes `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

planar