---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/12
- monster/environment/planar
- monster/environment/underdark
- monster/size/huge
- monster/type/giant
aliases: ["Gug"]
---
# Gug
*Source: Tome of Beasts 1 (2023 Edition) p. 225*  

*The giant, four-armed, two-legged creature steps forward, long claws extended. A large toothy mouth splits its torso from shoulders to navel.*

## Underworld Godlings

Gugs are giants of the underworld that enjoy smashing and devouring lesser creatures. Their burbling and grunting speech displays a surprising and malign intelligence to those who can understand it. Gugs are occasionally worshipped by tribes of derro, and their strange underworld cities are filled with esoteric monoliths and constructs.

## Nocturnal Raiders

While gugs were banished into the underworld by forgotten gods long ago, they regularly flout this prohibition by raiding the surface by night. They also spend much time in the Ethereal Plane, and some gug spellcasters travel the planes with entourages of fext or noctiny.

## Prey on Ghouls

Gugs devour ghouls and darakhul as their preferred food. When these are not available, they seem to prefer carrion and particular varieties of psychotropic mushrooms, as well as something that is best described as candied bats.

## Statblock

```ad-statblock
title: Gug
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Gug.webp#token)
*Huge giant, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 230 (`20d12 + 100`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|10 (+0)|21 (+5)|10 (+0)| 8 (-1)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +11, Dexterity +4, Constitution +9, Charisma +6
- **Skills** Athletics +11, Perception +3, Stealth +4
- **Senses** darkvision 240 ft., passive Perception 13
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Deep Speech, Giant, Undercommon
- **Challenge** 12

## Traits

***Towering Strength.*** The gug is considered to be a Gargantuan giant for the purpose of determining its carrying capacity.

## Actions

***Multiattack.*** The gug makes two four Grasping Claw attacks, or it makes two Grasping Claw attacks and two Stomp attacks. It can replace one Grasping Claw attack with a use of Fling or Swallow.

***Grasping Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+7|noform|avg|text(18)` (`2d10 + 7`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17) if it is a Large or smaller creature. The gug has four Grasping Claws, each of which can grapple only one target.

***Stomp.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft. *Hit:* `dice:2d12+7|noform|avg|text(20)` (`2d12 + 7`) bludgeoning damage, and the target must succeed on a DC 17 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Fling.*** One Large or smaller object held or creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the gug is thrown up to 60 feet in a random direction and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If a thrown target strikes a solid surface, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 17 Dexterity saving throw or take the same damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Swallow.*** The gug makes one Grasping Claw attack against a Large or smaller creature it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the gug, and it takes `dice:4d6|noform|avg|text(14)` (`4d6`) acid damage at the start of each of the gug's turns. A gug can have only one creature swallowed at a time.

If the gug takes 30 damage or more on a single turn from the swallowed creature, the gug must succeed on a DC 19 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the gug. If the gug dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

planar, underdark