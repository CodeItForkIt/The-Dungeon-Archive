---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ttp
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Giant Slug"]
---
# Giant Slug
*Source: The Tortle Package p. 18*  

```ad-statblock
title: Giant Slug
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TTP/Giant%20Slug.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 66 (`6d10 + 18`)
- **Speed** 10 ft., climb 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|13 (+1)|16 (+3)| 1 (-5)|12 (+1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Languages** Abyssal, Aquan, Common
- **Challenge** 3

## Traits

***Keen Smell.*** The slug has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Spider Climb.*** The slug can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Innate Spellcasting.*** The slug's innate spellcasting ability is Wisdom (spell save DC 11, `dice:1d20+3|noform|text(+3)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**1/day each**: [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [sanctuary](2-Mechanics/CLI/spells/sanctuary.md), [spiritual weapon](2-Mechanics/CLI/spells/spiritual-weapon.md)

## Actions

***Multiattack.*** The slug makes two attacks: one with its tentacles and one with its bite.

***Tentacles.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one creature. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) poison damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. Until this poison ends, the target is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed). The target can repeat the saving throw at the end of each of its turns, ending the poison on itself on a success.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) piercing damage.

## Reactions

***Animate Tentacle.*** When the slug takes damage in this cave (Shrine of Umberlee), it can use its reaction to animate one of the tentacles of the kraken statue and cause it to   make a melee weapon attack (`dice:1d20+3|noform|text(+3)` to hit) against one creature within 20 feet of the statue that the slug can see. The tentacle deals `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage on a hit.
```
^statblock