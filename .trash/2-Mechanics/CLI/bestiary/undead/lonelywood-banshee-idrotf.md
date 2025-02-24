---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/4
- monster/size/medium
- monster/type/undead
aliases: ["Lonelywood Banshee"]
---
# Lonelywood Banshee
*Source: Icewind Dale: Rime of the Frostmaiden p. 81*  

This banshee is the spectral remnant of a female elf warrior who was banished for a selfish, evil act. It wields a spectral longbow that shoots phantom arrows. There is only one banshee haunting the forest. If it's destroyed, it re-forms after 24 hours in a random location in the forest, damned to its eternal exile.

```ad-statblock
title: Lonelywood Banshee
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Lonelywood%20Banshee.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 12
- **Hit Points** 58 (`13d8`)
- **Speed** 0 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|14 (+2)|10 (+0)|12 (+1)|11 (+0)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +2, Charisma +5
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Elvish
- **Challenge** 4

## Traits

***Detect Life.*** The banshee can magically sense the presence of living creatures up to 5 miles away that aren't undead or constructs. She knows the general direction they're in but not their exact locations.

***Incorporeal Movement.*** The banshee can move through other creatures and objects as if they were difficult terrain. She takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if she ends her turn inside an object.

## Actions

***Spectral Longbow.*** *Ranged Spell Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 150/600 ft., one target. *Hit:* `dice:3d6+2|noform|avg|text(12)` (`3d6 + 2`) necrotic damage.

***Horrifying Visage.*** Each non-undead creature within 60 feet of the banshee that can see her must succeed on a DC 13 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) for 1 minute. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, with disadvantage if the banshee is within line of sight, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to the banshee's Horrifying Visage for the next 24 hours.

***Wail (1/Day).*** The banshee releases a mournful wail, provided that she isn't in sunlight. This wail has no effect on constructs and undead. All other creatures within 30 feet of her that can hear her must make a DC 13 Constitution saving throw. On a failure, a creature drops to 0 hit points. On a success, a creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage.
```
^statblock