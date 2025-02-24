---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/19
- monster/environment/badlands
- monster/environment/planar
- monster/size/huge
- monster/type/aberration
aliases: ["Shoggoth"]
---
# Shoggoth
*Source: Tome of Beasts 1 (2023 Edition) p. 326*  

*The giant, gelatinous blob of flesh releases whistles, trills, and chirps as it rolls forward, forming and reabsorbing mouths, eyes, and ears across its body.*

A shoggoth is an intelligent, gelatinous blob capable of manipulating and reshaping its body. Created by an elder race as servants, the shoggoths rebelled long ago and slew their masters without pity. Since that time, they've lived in isolated or desolate regions, devouring whatever they encounter and absorbing its flesh into their own amorphous, shifting forms.

## Constant Growth

Shoggoths continue growing throughout their lives, though the eldest among them grow very slowly indeed. Some shoggoths may shrink from starvation if they deplete a territory of resources.

## Mutable Form

A shoggoth can form any number of eyes, mouths, tentacles, or other appendages as needed, though it lacks the control to take and maintain the shape of another creature.

## Statblock

```ad-statblock
title: Shoggoth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Shoggoth.webp#token)
*Huge aberration, Chaotic Neutral*

- **Armor Class** 18 (natural armor)
- **Hit Points** 325 (`21d12 + 189`)
- **Speed** 50 ft., climb 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|14 (+2)|28 (+9)|12 (+1)|20 (+5)|13 (+1)|

- **Proficiency Bonus** +6
- **Saving Throws** ⏤
- **Skills** Perception +11
- **Senses** darkvision 120 ft., tremorsense 60 ft., passive Perception 21
- **Damage Resistances** bludgeoning, fire, piercing
- **Damage Immunities** cold, slashing, thunder
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Void Speech
- **Challenge** 19

## Traits

***Anaerobic Nature.*** The shoggoth doesn't require air.

***Absorb Flesh.*** When the shoggoth kills a creature while within 15 feet of it, the creature's body is absorbed into the shoggoth's. The creature can be restored to life only by means of a true resurrection or a [wish](2-Mechanics/CLI/spells/wish.md) spell.

***Amorphous.*** The shoggoth can move through a space as narrow as 1 foot wide without squeezing.

***Hideous Cacophony.*** The shoggoth's many mouths constantly emit whistles, fluting, and other high-pitched noises. It has disadvantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to be unheard. Each creature that starts its turn within 60 feet of the shoggoth and that can hear it must make a DC 19 Wisdom saving throw or be disoriented until the start of its next turn. A disoriented creature is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), and when it moves, it moves in a random direction.

Unless surprised, a creature can cover its ears to avoid the saving throw at the start of its turn. If the creature does so, it can't hear until the start of its next turn, when it can cover its ears again. If the creature uncovers its ears in the meantime while within 60 feet of the shoggoth, it must immediately make the save. A creature that is covering its ears and that has access to cloth, wax, or similar material can stuff its ears with the material as a bonus action to free up its hands, deafening itself while the material remains stuffed in its ears.

***Keen Hearing and Smell.*** The shoggoth has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or smell.

***Limited Mutability.*** Any spell or effect that would alter the shoggoth's form alters it for only 1 round. Afterward, the shoggoth returns to its amorphous blob form.

## Actions

***Multiattack.*** The shoggoth makes four Slam attacks. It can replace two Slam attacks with a use of Crush.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 15 ft., one target. *Hit:* `dice:4d10+8|noform|avg|text(30)` (`4d10 + 8`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 18) if it is a Large or smaller creature.

***Crush.*** The shoggoth crushes up to two creatures it is grappling by rolling them beneath its bulk. Each target must succeed on a DC 19 Strength saving throw or take `dice:4d10+8|noform|avg|text(30)` (`4d10 + 8`) bludgeoning damage, be unable to breathe, and be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the grapple ends. If the shoggoth moves, a creature beneath it is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and is able to breathe, but it remains [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).
```
^statblock

## Environment

badlands, planar