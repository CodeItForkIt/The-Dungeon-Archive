---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/14
- monster/size/large
- monster/type/fiend
aliases: ["Shator Warden"]
---
# Shator Warden
*Source: Minsc and Boo's Journal of Villainy p. 137*  

> [!quote] A quote from MINSC & BOO!  
> 
> Me and Boo like many sticky things, most especially donuts and Boo's favorite, candied pecans. But some sticky things belong on the pointy end of a sword.

> [!quote] A quote from Volo  
> 
> Demodands are difficult to study since they usually never leave their native plane of Carceri. However, the prison in Ust Natha presents a unique opportunity to view them up close. Not that I enjoyed the experience.

Demodands are primal creations of evil and implacable agents of destruction. Exiled to Carceri for their chaotic taint, they are also known as gehreleths or leths.

## Wardens of the Damned

Though they are trapped in Carceri, the demodands do not consider themselves prisoners. Instead, they are the self-appointed wardens and jailors of the Tarterian Depths. They derive pleasure from tormenting and terrorizing their fellow captives through acts of brutality, cruelly taunting them the entire time. However, they make no distinction between those actually condemned to Carceri, and planar travelers just passing through. As far as the demodand are concerned, all must be prevented from escaping at any cost.

## A Trio of the Grotesque

Demodands have three castes, each with a form so repulsive even other denizens of the Lower Planes view them with disgust. The farastu are forced to do the most menial tasks, under orders from their kelubar and shator superiors. When around weaker creatures they are vicious bullies; around more powerful beings they become whimpering cowards. The kelubars are the bureaucrats of the demodands, acting as intermediaries between the lowly farastu and their shator overlords. The kelubar decide which prisoners are rewarded, and which should be punished with extra torments. The shators make up the ruling caste, effectively serving as prison wardens to the lower-ranked guards.

## The Memory of Eons

Each shator possesses an obsidian triangle. These powerful magical artifacts grant the demodands access to the collective memory of their kind; a shared recollection stretching back to the very dawn of time. The shators primarily use the triangles to track the identity of every being that has ever escaped Carceri, concocting elaborate, generation-spanning strategies to recapture these fugitive souls.

## Statblock

```ad-statblock
title: Shator Warden
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Shator%20Warden.webp#token)
*Large fiend, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 119 (`14d10 + 42`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|11 (+0)|17 (+3)|14 (+2)|16 (+3)|20 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +12, Constitution +8, Charisma +10
- **Skills** Athletics +12, Insight +8, Persuasion +10
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 14

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the shator's darkvision.

***Keen Smell.*** The shator has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Magic Resistance.*** The shator has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The shator's weapon attacks are magical.

***Spellcasting.*** The shator casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 18):

**At will**: [clairvoyance](2-Mechanics/CLI/spells/clairvoyance.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [fear](2-Mechanics/CLI/spells/fear.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only), [spider climb](2-Mechanics/CLI/spells/spider-climb.md), [tongues](2-Mechanics/CLI/spells/tongues.md)

**2/day each**: [cloudkill](2-Mechanics/CLI/spells/cloudkill.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md), [Tasha's hideous laughter](2-Mechanics/CLI/spells/tashas-hideous-laughter.md)

## Actions

***Multiattack.*** The shator makes one Bite attack or one Poisonous Spit attack (if available) and then makes two Claws attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+7|noform|avg|text(16)` (`2d8 + 7`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+7|noform|avg|text(11)` (`1d8 + 7`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage.

***Poisonous Spit (Recharge 5-6).*** The shator exhales poisonous spit in a 20-foot line that is 5 feet wide. Each creature in that line must make a DC 18 Dexterity saving throw, taking `dice:5d8|noform|avg|text(22)` (`5d8`) acid damage on a failed save and having the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on a success.

## Bonus Actions

***Summon Demodand (1/Day).*** The shator rolls a `dice:d6|noform|avg` (`d6`). A result of 1-2 summons in two allied [farastu stalkers](2-Mechanics/CLI/bestiary/fiend/farastu-stalker-mabjov.md), a result of 3-4 summons in one allied [shator warden](2-Mechanics/CLI/bestiary/fiend/shator-warden-mabjov.md).

## Reactions

***Poisonous Slime.*** When hit with a melee attack, the shator expels a toxic slime. The attacker must succeed on a DC 18 Dexterity saving throw or have the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on a success.
```
^statblock