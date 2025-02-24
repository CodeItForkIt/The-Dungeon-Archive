---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/planar
- monster/size/large
- monster/type/aberration
aliases: ["Voidling"]
---
# Voidling
*Source: Tome of Beasts 1 (2023 Edition) p. 390*  

*Writhing black tendrils stretch from this indistinct orb of pure shadow. The faintest flicker of something green, like an eye, appears for a moment in the center of the globe and then fades to black again.*

## Called from Darkness

Voidlings are creatures of the darkest part of the Void, the cold space between the stars. They are drawn to mortal realms by practitioners of foul, corrupting magic known to break the minds of those who wield it. They frequently are summoned servants to Void dragons, and they have been seen as wardens of the temples on the Plateau of Leng.

## Sustained by Darkness

Voidlings are said to devour life and knowledge, and they subsist on darkness. The places they inhabit are known for their dank chill and obscurity. Voidlings are summoned by those hungry for power at any cost, and—despite their dark reputation—they serve well for years or even decades, until one day they turn on their summoners. If they slay their summoner, they grow in strength and return to the Void. Exactly what voidlings seek when they have not been summoned—and what triggers their betrayals—is a mystery.

## Cold Tendrils

Creatures of utter darkness, they can barely be said to have a shape. They consist largely of lashing tendrils of solid shadow. The tendrils meet at a central point and form a rough sphere in which something like an eye appears intermittently. Though their tentacles stretch ten feet long, the core of a voiding is no more than four feet across, and it weighs nothing, darting through either air or Void with impressive speed.

## Statblock

```ad-statblock
title: Voidling
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Voidling.webp#token)
*Large aberration, Chaotic Evil*

- **Armor Class** 15
- **Hit Points** 180 (`24d10 + 48`)
- **Speed** 0 ft., fly 50 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|21 (+5)|15 (+2)|14 (+2)|16 (+3)|10 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +6, Intelligence +6, Wisdom +7, Charisma +4
- **Skills** Stealth +9
- **Senses** truesight 60 ft., passive Perception 13
- **Damage Vulnerabilities** radiant
- **Damage Immunities** necrotic
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** telepathy 60 ft., Void Speech
- **Challenge** 11

## Traits

***Darkness Regeneration.*** While in an area of dim light or darkness, the voidling regains 5 hp at the start of its turn if it has at least 1 hp.

***Magic Resistance.*** The voidling has advantage on saving throws against spells and other magical effects.

***Void Traveler.*** The voidling doesn't require air, food, drink, sleep, or ambient pressure.

## Actions

***Multiattack.*** The voidling makes four Shadow Tendril or Necrotic Bolt attacks. If two Necrotic Bolt attacks hit one creature, the target must succeed on a DC 17 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of its next turn.

***Shadow Tendril.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.

***Necrotic Bolt.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one target. *Hit:* `dice:4d6+3|noform|avg|text(17)` (`4d6 + 3`) necrotic damage.

***Shadow's Grasp (Recharge 5-6).*** The voidling releases a wave of small, grasping tendrils of shadow. Each creature within 20 feet of it must make a DC 17 Dexterity saving throw. On a failure, a creature takes `dice:14d6|noform|avg|text(49)` (`14d6`) necrotic damage and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by tendrils of shadow for 1 minute. On a success, a creature takes half the damage and isn't [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

planar