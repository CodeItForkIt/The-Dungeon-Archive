---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/23
- monster/size/gargantuan
- monster/type/aberration
aliases: ["Amalgamation"]
---
# Amalgamation
*Source: Dungeons of Drakkenheim p. 206*  

> [!quote] A quote from Eldrick Runeweaver  
> 
> Formed only in places where dimensional rifts are torn open, this blasphemous abomination is a conduit by which beings from realms of chaos untold can enter our world. It is an interdimensional cancer which infects our earth.


```ad-statblock
title: Amalgamation
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Amalgamation.webp#token)
*Gargantuan aberration, Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 525 (`30d20 + 210`)
- **Speed** 5 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|11 (+0)|27 (+8)|22 (+6)|18 (+4)|20 (+5)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +17, Dexterity +7, Constitution +15, Intelligence +13, Wisdom +11
- **Skills** Arcana +13, Deception +12, Insight +11, Perception +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Immunities** bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** all, telepathy 1 mile
- **Challenge** 23

## Traits

***Legendary Resistance (3/Day).*** If the amalgamation fails a saving throw, it can choose to succeed instead.

***Malignancy.*** The amalgamation can't be teleported or travel to another plane against its will.

***Immutable Form.*** The amalgamation is immune to any spell or effect that would alter its form.

***Magic Weapons.*** The amalgamation's weapon attacks are magical.

***Innate Spellcasting.*** The amalgamation's innate spellcasting ability is Charisma (spell save DC 20). It can innately cast the following spells, requiring no components:

**At will**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md)

## Actions

***Multiattack.*** The amalgamation uses its Contaminating Presence. It then makes three tentacle attacks, each of which it can replace with one use of Fling.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+10|noform|avg|text(23)` (`3d8 + 10`) piercing damage. If the target is a Large or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the amalgamation, that creature is swallowed, and the grapple ends.

While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the amalgamation, and it takes `dice:12d6|noform|avg|text(42)` (`12d6`) acid damage and gains one level of contamination at the start of each of the amalgamation's turns.

If the amalgamation takes 50 damage or more on a single turn from a creature inside it, the amalgamation must succeed on a DC 25 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the amalgamation. If the amalgamation dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 50 ft., one target. *Hit:* `dice:3d6+10|noform|avg|text(20)` (`3d6 + 10`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 18). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The amalgamation has twelve tentacles, each of which can grapple one target.

***Fling.*** One Large or smaller object held or creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the amalgamation is thrown up to 60 feet in a direction of the amalgamation's choice and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If a thrown target strikes a solid surface, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 18 Dexterity saving throw or take the same damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Mind-breaking Whispers.*** The amalgamation utters a terrible truth within the mind of one creature within 120 feet of it. That creature must succeed on a DC 20 Intelligence saving throw. On a failure, it takes `dice:10d6|noform|avg|text(35)` (`10d6`) psychic damage and becomes insane until it finishes a long rest. While insane, it can't take actions, can't understand what other creatures say, can't read, and can speak only in gibberish. A [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell cast on the creature ends this effect.

***Contaminating Presence.*** Humanoid creatures within 120 feet of the amalgamation must succeed on a DC 20 Constitution saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage and gain one level of contamination.

## Legendary Actions

***Tentacle Attack or Fling.*** The amalgamation makes one tentacle attack or uses its Fling.

***Mind-breaking Whispers (Costs 2 Actions).*** The amalgamation uses Mind-breaking Whispers.

***Piper at the Gate (Costs 3 Actions).*** Up to five gibbering mouthers appear in unoccupied spaces within 30 feet of the amalgamation and remain until destroyed. These creatures act after the amalgamation on the same initiative count and are under its control. The amalgamation can have up to ten gibbering mouthers summoned by this ability at a time.
```
^statblock