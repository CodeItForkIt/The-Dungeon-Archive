---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/17
- monster/environment/underdark
- monster/size/huge
- monster/type/aberration
aliases: ["Urochar"]
---
# Urochar
*Source: Tome of Beasts 1 (2023 Edition) p. 374*  

*This gigantic crimson leech slithers upright on four muscular tentacles. At the top of its writhing trunk, a great lidless eye glows with baleful orange light, surrounded by quivering, feathered antennae.*

## Underworld Wanderers

Sometimes fearfully called "strangling watchers," the urochar are among the most dreaded monsters of the underworld. They have long plagued the drow, grimlocks, and other humanoids of the deep paths. They seek out death and the dying all the way to the banks of the River Styx.

## Devour the Dying

Urochars feast on the final moments of those caught in their crushing tentacles. Though powerful, urochars are quite passive. They watch the life and death struggles of other creatures and take action only to drink in a dying being's final moments from a nearby crevice or overhang.

## Immortal

Strangling watchers are effectively immortal. Gargantuan specimens in the deepest reaches of the underworld are several millennia old.

## Statblock

```ad-statblock
title: Urochar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Urochar.webp#token)
*Huge aberration, Chaotic Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 256 (`19d12 + 133`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|15 (+2)|24 (+7)|14 (+2)|14 (+2)|20 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +8, Constitution +13, Wisdom +8, Charisma +11
- **Skills** Perception +8, Stealth +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Resistances** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** thunder
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** understands Darakhul and Void Speech but can't speak
- **Challenge** 17

## Traits

***Mind-Rending Death.*** When the urochar dies, it releases all the fear it consumed in its lifetime in a single, mind-rending wave. Each creature within 30 feet of it must succeed on a DC 19 Charisma saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature takes `dice:4d6|noform|avg|text(14)` (`4d6`) psychic damage at the start of each of its turns. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Rubbery Body.*** The urochar's body is rubbery with few bones, allowing it to easily move through any opening large enough for a Medium creature. It can squeeze through any opening large enough for a Small creature. The urochar's destination must still have suitable room to accommodate its volume.

***Spider Climb.*** The urochar can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The urochar can use its Paralyzing Gaze. It then makes four Tentacle attacks.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 20 ft., one target. *Hit:* `dice:4d8+7|noform|avg|text(25)` (`4d8 + 7`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 19) if it is a Large or smaller creature. Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The urochar has four tentacles, each can grapple only one target.

***Paralyzing Gaze.*** The urochar turns its eerie gaze upon one creature it can see within 60 feet of it. The target must succeed on a DC 19 Wisdom saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to the urochar's Paralyzing Gaze for the next 24 hours.

***Strangling Grasp.*** Each creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the urochar must make a DC 19 Strength saving throw. On a failure, a creature takes `dice:8d8|noform|avg|text(36)` (`8d8`) bludgeoning damage and can't breathe until the grapple ends. On a success, a creature takes half the damage and can still breathe.

## Reactions

***Hidden Step.*** The urochar magically teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see and takes the Hide action. Grappled creatures are no longer [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) and don't teleport with it.
```
^statblock

## Environment

underdark