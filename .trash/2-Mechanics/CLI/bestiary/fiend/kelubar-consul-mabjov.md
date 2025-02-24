---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/11
- monster/size/medium
- monster/type/fiend
aliases: ["Kelubar Consul"]
---
# Kelubar Consul
*Source: Minsc and Boo's Journal of Villainy p. 136*  

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
title: Kelubar Consul
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Kelubar%20Consul.webp#token)
*Medium fiend, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 97 (`13d8 + 39`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|13 (+1)|17 (+3)|14 (+2)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +9, Constitution +7, Charisma +8
- **Skills** Athletics +9, Insight +6, Persuasion +8
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Resistances** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 11

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the kelubar's darkvision.

***Freedom of Movement.*** The kelubar is unaffected by difficult terrain, and spells and other magical affects don't reduce its speed or cause it to be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). If the kelubar spends 5 feet of movement is automatically escapes from nonmagical restraints or a creature that has it [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled). It is also able to move underwater with no movement or attack penalties.

***Keen Smell.*** The kelubar has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Magic Resistance.*** The kelubar has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The kelubar's weapon attacks are magical.

***Reckless.*** At the start of its turn, the kelubar can gain advantage on all melee weapon attack rolls it makes during that turn, but attack rolls against it have advantage until the start of its next turn.

***Sneak Attack (1/Turn).*** The kelubar deals an extra `dice:4d6|noform|avg|text(14)` (`4d6`) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 ft. of an ally of the kelubar that isn't incapacitated and the kelubar doesn't have disadvantage on the attack roll.

***Stench.*** Any creature that is not a demodand and starts its turn within 30 feet of the kelubar must succeed on a DC 16 Constitution saving throw or or have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 minute. On a successful saving throw, the creature is immune to the stench of this kelubar for 1 hour.

***Spellcasting.*** The kelubar casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [clairvoyance](2-Mechanics/CLI/spells/clairvoyance.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [fear](2-Mechanics/CLI/spells/fear.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only), [spider climb](2-Mechanics/CLI/spells/spider-climb.md), [tongues](2-Mechanics/CLI/spells/tongues.md)

**2/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md)

## Actions

***Multiattack.*** The kelubar makes one Bite attack and three Claws attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage.

## Bonus Actions

***Summon Demodand (1/Day).*** The kelubar rolls a `dice:d6|noform|avg` (`d6`). A result of 1-2 summons in two allied [farastu stalkers](2-Mechanics/CLI/bestiary/fiend/farastu-stalker-mabjov.md), a result of 3-4 summons in one allied [kelubar consul](2-Mechanics/CLI/bestiary/fiend/kelubar-consul-mabjov.md).

## Reactions

***Impossible Dodge.*** When an attacker that the kelubar can see hits it with an attack, the kelubar can use its reaction to halve the attack's damage.
```
^statblock