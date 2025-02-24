---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/planar
- monster/size/medium
- monster/type/aberration
aliases: ["Fate Eater"]
---
# Fate Eater
*Source: Tome of Beasts 1 (2023 Edition) p. 168*  

*Violet radiance surrounds this large pale centipede. Its flesh is translucent, and its jaws are crystalline.*

## Destiny Destroyers

Fate eaters infest remote areas of the planes, where they consume the threads of Fate itself. The beings in charge of Fate view them as vermin. Sometimes those beings engage particularly canny planar travelers either to hunt fate eaters or to help repair the damage they've done. This can be a deadly job, as the fate eaters consider the destiny of a mortal to be the tastiest of delicacies, rich in savory possibilities.

## Planar Gossips

Fate eaters can and do trade information about various dooms, fates, and outcomes, but one must have something rich in destiny to trade—or at least, juicy gossip about gods and demons.

## Visionary Flesh

Eating the properly prepared flesh of a fate eater grants the eater insight into the fate of another being.

## Statblock

```ad-statblock
title: Fate Eater
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Fate%20Eater.webp#token)
*Medium aberration, Neutral*

- **Armor Class** 16 (natural armor)
- **Hit Points** 130 (`20d8 + 40`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|12 (+1)|14 (+2)|18 (+4)|16 (+3)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5
- **Skills** Arcana +7, History +7, Insight +6, Religion +7
- **Senses** truesight 60 ft., passive Perception 13
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** telepathy 100 ft. understands all but can't speak
- **Challenge** 6

## Traits

***Visionary Flesh.*** A creature that eats the flesh of a fate eater must make a DC 15 Constitution saving throw. On a failure, the creature is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. On a success, the creature gains the benefits of the divination spell.

## Actions

***Multiattack.*** The fate eater makes two Bite attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.

***Alter Fate (Recharge 5-6).*** The fate eater alters the fate of one creature it can see within 30 feet of it. The creature must make a DC 15 Charisma saving throw. On a failure, the creature takes `dice:8d8|noform|avg|text(36)` (`8d8`) psychic damage, and its fate is altered. Roll a `dice:d6|noform|avg` (`d6`) to determine which of the following alterations affects the creature. On a success, the creature takes half the damage, and its fate isn't altered. A creature with an altered fate for 1 minute or less can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Otherwise, a creature with an altered fate can repeat the saving throw at the end of each long rest, ending the effect on itself on a success.

***1 Forgotten Training.*** The creatures loses the use of one random class feature, such as Action Surge or Channel Divinity, for 1 minute.

***2 Lost Potential.*** One of the creature's ability scores, chosen at random, is reduced by 2.

***3 Seeing the Alternates.*** The creature is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) for 1 minute.

***4 Shifting Memories.*** The creature loses proficiency in one random skill and gains proficiency in another random skill.

***5 Took the Lesser Path.*** The creature's current hp total becomes its hp maximum.

***6 Untied from the Loop.*** When the creature moves, it moves in a random direction for 1 minute.
```
^statblock

## Environment

planar