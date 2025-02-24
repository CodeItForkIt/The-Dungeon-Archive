---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/16
- monster/environment/forest
- monster/environment/planar
- monster/size/medium
- monster/type/fey
aliases: ["River King"]
---
# River King
*Source: Tome of Beasts 1 (2023 Edition) p. 182*  

*This powerfully muscled elf lord wears a cloak of foam-trimmed dark blue and a vest of woven green reeds and willow branches. His crown shines like the sun on a lake, and his flowing hair curls and moves even when there is no wind. An orb of blue light that ripples like water circles his hand*.

His Rippling Majesty, Ulorian the River King, also bears the titles Defender of the Pearl Tower and Master of the Deep Forest. A lean elf noble with whipcord muscles and flowing grace, the River King rules over the Rippling Court and ultimately all the river elves of the forest. His court resides just beyond the river's reflection, in a realm of fey glamour and silty water.

## A Fickle Friend

The River King is a stern ruler with a great love for his people and a quick temper for those who threaten his domain. As much a force of nature as he is a monarch, the River King is known to sometimes forget promises that were made in sincerity, and dealing with him can be perilous at the best of times. "The river may change its course when it wills" is the usual expression among his court when His Rippling Majesty has had a sudden change of heart.

## Fey Lords and Ladies

Fey are capricious, mischievous, and often dangerous beings. However, despite their chaotic reputations, they do follow a certain set of rules. These rules—widely misunderstood by outsiders—are codified and enforced by a cadre of lofty fey nobility. Befitting any courtly structure, the fey bow to lords and ladies: eldritch creatures of immense power who rule the courts.

### Heads of State

The fey lords and ladies are beings of high station and prodigious personal power. Each rules over at least a great city if not an entire nation. No matter the scope of a fey noble's domain, in his or her eyes, a fey ruler's word is law. Outsiders might not understand the edicts and interdicts of a fey noble, but that's no protection against the harsh penalties that await any who break them, knowingly or otherwise.

### Vacant Thrones

When a lord or lady of the fey dies, the court does not remain leaderless for long. Ambitious beings among the fey always hunger for more power and covet the stations of their superiors. After a traditional month or year of mourning, vicious power struggles winnow the weak and pave the way for the most cunning or the strongest to take the court's vacant throne.

## The River King's Lair

The Court of the River King is a pair of small islands in the middle of a wide, swift river that flows from the mortal realm through a dimension of fey magic. The western keep houses servants, and the eastern is built above the Great Rippling Hall. The Great Rippling Hall is a bubble whose walls and ceiling are the river itself. A driftwood throne dominates the main hall.

## Statblock

```ad-statblock
title: River King
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/River%20King.webp#token)
*Medium fey, Chaotic Neutral*

- **Armor Class** 18 (natural armor)
- **Hit Points** 190 (`20d8 + 100`)
- **Speed** 30 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|17 (+3)|20 (+5)|14 (+2)|13 (+1)|17 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +8, Constitution +10, Wisdom +6
- **Skills** Intimidation +8, Nature +7, Perception +6, Stealth +8
- **Senses** blindsight 10 ft., darkvision 120 ft., passive Perception 16
- **Damage Resistances** bludgeoning, piercing, slashing, cold, fire, lightning, thunder from nonmagical attacks not made with cold iron weapons
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Elvish, Giant, Primordial
- **Challenge** 16

## Traits

***Amphibious.*** The River King can breathe air and water.

***Legendary Resistance (3/Day).*** If the River King fails a saving throw, he can choose to succeed instead.

***Riparian Weapons.*** The River King's weapon attacks are magical. When he hits with any weapon, the weapon deals an extra `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage (included in the attack).

***Spellcasting.*** The River King casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (save DC 16):

**At will**: [create or destroy water](2-Mechanics/CLI/spells/create-or-destroy-water.md), [water breathing](2-Mechanics/CLI/spells/water-breathing.md)

**1/day**: [control weather](2-Mechanics/CLI/spells/control-weather.md) (as an action)

**3/day each**: [freedom of movement](2-Mechanics/CLI/spells/freedom-of-movement.md), [control water](2-Mechanics/CLI/spells/control-water.md)

## Actions

***Multiattack.*** The River King makes two Longsword or Flood Blast attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) slashing damage, or `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) slashing damage if used with two hands, plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.

***Flood Blast.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 120 ft., one target. *Hit:* `dice:4d8+3|noform|avg|text(21)` (`4d8 + 3`) bludgeoning damage, and the target must succeed on a DC 18 Strength saving throw or be pushed up to 30 feet away from the River King and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Grasping Whirlpool (Recharge 5-6).*** The River King magically creates a swirling vortex of water centered on a point he can see within 60 feet. The vortex appears in the shape of a cylinder that is 15 feet tall with a 10-foot radius. Each creature in the area must make a DC 18 Strength saving throw. On a failure, a creature takes `dice:8d8|noform|avg|text(36)` (`8d8`) bludgeoning damage and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). On a success, a creature takes half the damage, isn't [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and can choose to be pushed out of the whirlpool's space. A creature that chooses not to be pushed suffers the consequences of a failed saving throw. While [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), a creature is unable to breathe unless it can breathe water, and it must succeed on a DC 18 Strength saving throw at the end of each of its turns or take `dice:4d8|noform|avg|text(18)` (`4d8`) bludgeoning damage. A creature, including the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature, can take an action to free the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature by succeeding on a DC 18 Strength check. A creature with a swimming speed has advantage on the saving throw and on the Strength check to escape.

## Reactions

***Blade Current.*** When a creature within 5 feet of the River King stands up from [prone](2-Mechanics/CLI/rules/conditions.md#Prone), he can make one Longsword attack against that creature.

## Legendary Actions

***Attack.*** The River King makes a Longsword or Flood Blast attack.

***Flow.*** The River King moves up to his walking speed, or swims up to half his swimming speed, without provoking opportunity attacks.

***Ripple (Costs 2 Actions).*** The River King magically ripples like sunlight on the surface of water. Until the start of his next turn, attack rolls against him have disadvantage.

![River King](2-Mechanics/CLI/bestiary/legendary-group/river-king-tob1-2023.md)
```
^statblock

## Environment

forest, planar