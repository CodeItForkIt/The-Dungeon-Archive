---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgg
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/cleric
aliases: ["Firbolg Wanderer"]
---
# Firbolg Wanderer
*Source: Bigby Presents: Glory of the Giants p. 137, Giants of the Star Forge*  

Firbolgs inspired by the saga of Diancastra embark on adventures to create their own legends. These wanderers use their magic for trickery and disguise to emulate Diancastra.

## Firbolgs

Distant cousins of giants, the first firbolgs wandered the primeval forests of the multiverse, and the magic of those forests entwined itself with the firbolgs' souls. Ages later, that magic still thrums inside firbolgs.

Firbolgs are often drawn to the service or emulation of the gods Diancastra and Hiatea. Firbolgs' innate magic of obscurement and trickery resonates with Diancastra's wily resourcefulness. A traditional emphasis on community and harmony leads many firbolgs to pledge themselves to Hiatea's service.

## Statblock

```ad-statblock
title: Firbolg Wanderer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGG/Firbolg%20Wanderer.webp#token)
*Medium humanoid (cleric), Any alignment*

- **Armor Class** 16 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 90 (`12d8 + 36`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|16 (+3)|14 (+2)|17 (+3)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Charisma +6
- **Skills** Perception +6, Persuasion +6, Stealth +5
- **Senses** passive Perception 16
- **Languages** Common, Giant
- **Challenge** 5

***Spellcasting.*** The firbolg casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 14):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [Tasha's hideous laughter](2-Mechanics/CLI/spells/tashas-hideous-laughter.md)

**1/day each**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [polymorph](2-Mechanics/CLI/spells/polymorph.md)

## Actions

***Multiattack.*** The firbolg makes two attacks using Longsword, Bewitching Bolt, or a combination of them.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) slashing damage, or `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) slashing damage if used with two hands, plus `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage.

***Bewitching Bolt.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 60 ft., one creature. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) psychic damage, and the target must succeed on a DC 14 Charisma saving throw or have the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition until the start of the target's next turn.

## Bonus Actions

***Duplicitous Movement (1/Day).*** The firbolg projects an illusory duplicate of itself in an unoccupied space it can see within 30 feet of itself. The firbolg can then swap places with the illusion. The illusion vanishes after 1 minute, if the firbolg is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), or if the illusion is more than 120 feet from the firbolg.

As a bonus action on later turns, the firbolg can move the illusion up to 30 feet and can then swap places with it.
```
^statblock