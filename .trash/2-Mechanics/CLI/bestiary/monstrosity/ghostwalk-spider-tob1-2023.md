---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/underdark
- monster/size/large
- monster/type/monstrosity
aliases: ["Ghostwalk Spider"]
---
# Ghostwalk Spider
*Source: Tome of Beasts 1 (2023 Edition) p. 343*  

*A pasty-white spider the size of a horse slinks through the shadows. It fades from sight with a ghostly blue shimmer.*

Ghostwalk spiders are malevolent hunters that sprang from misguided experiments on phase spiders. They are spindly, emaciated things all but devoid of color. The spider is 8 feet in diameter (including legs) and weighs 500 pounds.

## Phantom Webs

Ghostwalk spiders spin ephemeral webs in secluded areas. They spend most of their time stalking prey to paralyze and drag back to their phantom web. As long as these remains lie tangled in ghostly webs, they go unnoticed by most creatures, but the spiders eventually cast old kills aside. Adventurers are wise to fear empty caves containing unexplained, desiccated remains.

## Statblock

```ad-statblock
title: Ghostwalk Spider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ghostwalk%20Spider.webp#token)
*Large monstrosity, Neutral Evil*

- **Armor Class** 15
- **Hit Points** 119 (`14d10 + 42`)
- **Speed** 50 ft., climb 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|20 (+5)|17 (+3)| 9 (-1)|14 (+2)| 8 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +9, Charisma +3
- **Skills** Perception +6, Stealth +9
- **Senses** truesight 60 ft., passive Perception 16
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Undercommon but can't speak
- **Challenge** 9

## Traits

***Ghostly Body (Ghostwalk Form Only).*** The ghostwalk spider has resistance to acid, cold, fire, lightning, and thunder damage and to bludgeoning, piercing, and slashing damage from nonmagical attacks, and it has immunity to the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions.

***Incorporeal Movement (Ghostwalk Form Only).*** The ghostwalk spider can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Spider Climb.*** The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Walker.*** The spider ignores movement restrictions caused by webbing.

## Actions

***Multiattack.*** The ghostwalk spider makes one Bite attack and one Ghostly Snare attack, or it makes two Bite attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) piercing damage. If the ghostwalk spider is in its true form, the target must make a DC 15 Constitution saving throw, taking `dice:3d8|noform|avg|text(13)` (`3d8`) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hp, the target is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hp, and is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

***Ghostly Snare (Ghostwalk Form Only, Recharge 4-6).*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 30/60 ft., one target. *Hit:* The target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) webbing. While [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) in this way, the target is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible). As an action, the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target can make a DC 15 Strength check, bursting the webbing on a success. The webbing can also be attacked and destroyed (AC 12; hp 15; immunity to bludgeoning, poison, and psychic damage).

## Bonus Actions

***Ghostwalk.*** The ghostwalk spider magically takes on a ghostly form or returns to its true, tangible form. Its statistics are the same in each form. Any equipment it is wearing or carrying becomes ghostly with it. It reverts to its true form if it dies.
```
^statblock

## Environment

underdark