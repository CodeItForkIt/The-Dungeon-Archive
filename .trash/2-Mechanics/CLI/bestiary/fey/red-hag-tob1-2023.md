---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/coastal
- monster/environment/forest
- monster/environment/underdark
- monster/size/medium
- monster/type/fey
aliases: ["Red Hag"]
---
# Red Hag
*Source: Tome of Beasts 1 (2023 Edition) p. 228*  

*The red-skinned woman steps forward, sunlight glinting in her raven hair as red magic swirls around her.*

An elder race—older than the elves, and as old as the dragons, they claim—red hags are the most cunning and longest-lived of the hags, with a lifespan of more than a thousand years.

## Beautiful and Strong

Unlike many of their hag kin, red hags are not horrid to look upon, and most are considered comely in their own right. Few know anything about them, and the red hags do little to enlighten scholars, preferring seclusion.

## Tied to Nature

Red hags have a deep connection with all elements of nature, and they often make their homes in deep forests, in caves, or alongside coastlines.

## Blood Magic

Because of their connection to nature, red hags often serve as druids. Within their druidic circles they practice blood sacrifices and perform ritualistic blood magic—both to slake their craving for humanoid blood, but also as a means to venerate goddesses of dark magic. The ancient hags all answer to a hierarchy with the most powerful spellcasters at the top.

> [!note] Red Hags in Midgard
> 
> Red hags are more sociable among their own kind than other hags are, and they sometimes live in small communities in remote areas. In ancient times, they settled together in larger clusters and ruled small cities of mixed populations—especially in Old Verrayne. Their current leader is Blood Mother Margase, an ancient druid.
> 
> Their greatest city, Talitheos, an island metropolis of vast wealth and magical knowledge, sunk during the cataclysm, and the hags have been seeking its ruins ever since.
^red-hags-in-midgard

## Statblock

```ad-statblock
title: Red Hag
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Red%20Hag.webp#token)
*Medium fey, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 136 (`16d8 + 64`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|16 (+3)|18 (+4)|18 (+4)|21 (+5)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Arcana +10, Deception +5, Insight +8, Perception +8
- **Senses** darkvision 60 ft., passive Perception 18
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Druidic, Giant, Sylvan
- **Challenge** 7

## Traits

***Amphibious.*** The red hag can breathe air and water.

***Blood Sense.*** The red hag can pinpoint the location of creatures that aren't Constructs or Undead within 60 feet of her and can sense the general direction of such creatures within 1 mile of her.

***Magic Resistance.*** The red hag has advantage on saving throws against spells and other magical effects.

***Speak with Beasts.*** The red hag can communicate with Beasts as if they shared a language.

***Spellcasting.*** The red hag casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 16):

**At will**: [animal friendship](2-Mechanics/CLI/spells/animal-friendship.md), [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [entangle](2-Mechanics/CLI/spells/entangle.md)

**1/day**: [control water](2-Mechanics/CLI/spells/control-water.md), [freedom of movement](2-Mechanics/CLI/spells/freedom-of-movement.md)

**3/day**: [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md)

## Actions

***Multiattack.*** The hag makes two Claw attacks or three Blood Bolt attacks. She can replace one attack with a use of Spellcasting.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage.

***Blood Bolt.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 60 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) necrotic damage. If the target is a creature with blood, it must succeed on a DC 16 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the end of its next turn.

***Siphon Blood (Recharge 5-6).*** The red hag drains blood from nearby creatures. Each creature that isn't a Construct or Undead within 20 feet of the red hag must make a DC 16 Constitution saving throw, taking `dice:10d6|noform|avg|text(35)` (`10d6`) necrotic damage on a failed save, or half as much damage on a successful one. If at least one creature fails the saving throw, the next spell the red hag casts is cast as if the spell used a spell slot two levels higher than the spell's lowest level.
```
^statblock

## Environment

coastal, forest, underdark