---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/underdark
- monster/environment/urban
- monster/size/small
- monster/type/humanoid/kobold
aliases: ["Kobold Trapsmith"]
---
# Kobold Trapsmith
*Source: Tome of Beasts 1 (2023 Edition) p. 246*  

*This kobold is bedecked in satchels, pouches, sacks, and bandoliers. All of these are bursting with tools, bits of scrap, wire, cogs, and twine. Impossibly large eyes blink through the lenses of its goggles*.

Some kobolds hatch a bit cleverer than their counterparts. These sharp-witted creatures feel driven to fiddle with the world, and those that don't meet an early demise through accident or violence often take up tinkering. Trapsmiths make a kobold lair into a deadly gauntlet of hidden pain.

## Improvisers

Trapsmiths are adept at improvising on-the-fly. They can use whatever spare parts are at hand to create simple thieves' tools or construct makeshift traps to fling at foes.

## Shifting Peril

Trapsmiths aren't warriors and avoid direct confrontation with enemies that aren't mired in traps or engaged with other foes. If the trapsmith senses that invaders in its lair are likely to get past its traps, it tries to hide or escape. A trapsmith delights in laying traps and snares behind invaders, along tunnels and paths they've already cleared and believe to be safe, then luring them back through its handiwork.

## Statblock

```ad-statblock
title: Kobold Trapsmith
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Kobold%20Trapsmith.webp#token)
*Small humanoid (kobold), Lawful Neutral*

- **Armor Class** 14 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 54 (`12d6 + 12`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|16 (+3)|12 (+1)|16 (+3)|13 (+1)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** darkvision 60 ft., passive Perception 11
- **Languages** Common, Draconic
- **Challenge** 2

## Traits

***Improvised Tools.*** The kobold trapsmith can use any Tiny objects at hand to pick locks and disarm traps, as if any such object was part of a set of thieves' tools. It is proficient in using Tiny objects in this way. In addition, the trapsmith has advantage on ability checks to pick locks and disarm traps.

***Pack Tactics.*** The kobold trapsmith has advantage on attack rolls against a creature if at least one of the trapsmith's allies is within 5 feet of the creature and the ally isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

***Sunlight Sensitivity.*** While in sunlight, the kobold trapsmith has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The trapsmith uses Makeshift Trap then makes one Dagger or Spare Part attack.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage.

***Spare Part.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 20/60 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) bludgeoning damage or slashing damage (the trapsmith's choice).

***Makeshift Trap.*** The kobold trapsmith cobbles together a quick trap with materials at hand and throws it at a point on the ground it can see within 30 feet of it. The trapsmith chooses one of the following traps. Each creature in the trap's area must succeed on a DC 13 Dexterity saving throw or suffer the trap's effects.

- **Bursting Much-Heavy Net.** Each creature that fails the saving throw within 10 feet of where the trap lands takes `dice:3d6|noform|avg|text(10)` (`3d6`) bludgeoning damage and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) for 1 minute. A creature can take an action to free the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) creature by succeeding on a DC 13 Strength check.  
- **Spikes-on-Spikes.** Each creature within 10 feet of where the trap lands takes `dice:4d4|noform|avg|text(10)` (`4d4`) piercing damage and the area within 10 feet of the point is difficult terrain for 1 minute.  
- **Spring-Loaded Whirly Blades.** Each creature that fails the saving throw within 10 feet of where the trap lands takes `dice:4d6|noform|avg|text(14)` (`4d6`) slashing damage and its speed is reduced by 10 feet until the end of its next turn.  
- **Static-Generating Thingamabob.** Each creature that fails the saving throw within 5 feet of where the trap lands takes `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage and is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.  
```
^statblock

## Environment

underdark, urban