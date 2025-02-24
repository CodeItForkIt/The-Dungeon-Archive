---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/forest
- monster/environment/planar
- monster/size/large
- monster/type/monstrosity
aliases: ["Hound of the Night"]
---
# Hound of the Night
*Source: Tome of Beasts 1 (2023 Edition) p. 235*  

*This enormous black hound pants in the moonlight, wisps of steam rising from its muzzle, as it follows its elvish master.*

## Fey Bloodhounds

Hounds of the night are bred by the shadow fey for use as hunting companions and guardians, and they excel at both tasks. Far more intelligent than other hounds, they are difficult to evade once they are on a quarry's trail, because they can think their way past problems that would throw their lesser kin off the trail. Their shadow fey masters claim that hounds of the night can smell a shadow on running water and can sniff out a ghost passing through a wall.

## Cousins to Winter

Somewhere in their early existence as a breed, some enterprising hunter interbred them with winter wolves. Every trace of their white fur is long gone, but the cold breath of those dread canines remains.

## Dimensional Stepping

Hounds of night excel at distracting prey while some of their pack teleport away to achieve some larger goal, such as dragging off a treasure or overwhelming a spellcaster in the back ranks.

## Statblock

```ad-statblock
title: Hound of the Night
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Hound%20of%20the%20Night.webp#token)
*Large monstrosity, Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 112 (`15d10 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|16 (+3)|14 (+2)| 7 (-2)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Constitution +5, Wisdom +5
- **Skills** Intimidation +3, Perception +5, Stealth +6
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Vulnerabilities** fire
- **Damage Immunities** cold
- **Languages** understands Elvish and Umbral but can't speak
- **Challenge** 5

## Traits

***Fey Scent.*** The hound of the night has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell. If it is tracking a Fey, Giant, or Humanoid whose scent it knows, the hound can continue tracking that creature if the creature moves into the Border Ethereal or teleports, provided the creature isn't in the Border Ethereal for more than 1 minute or that the creature doesn't teleport more than 100 feet at a time.

## Actions

***Multiattack.*** The hound of the night makes two Bite attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) cold damage, and the target must succeed on a DC 14 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Frost Breath (Recharge 5-6).*** The hound exhales frost in a 15-foot cone. Each creature in the area must make a DC 14 Dexterity saving throw, taking `dice:6d8|noform|avg|text(27)` (`6d8`) cold damage on a failed save, or half as much damage on a successful one.

***Teleport (Recharge 4-6).*** The hound magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see. Before or after teleporting, the hound can make one Bite attack.
```
^statblock

## Environment

forest, planar