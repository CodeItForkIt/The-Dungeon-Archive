---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/any
- monster/size/medium
- monster/type/aberration
aliases: ["Ostinato"]
---
# Ostinato
*Source: Tome of Beasts 1 (2023 Edition) p. 292*  

*A bit of catchy, repetitive music emanates from nowhere, drifting and moving as if dancing in the empty air.*

## Born from Drama

Incredibly moving arias, passionate performances, and ditties that drive a person mad are often the product of ostinatos. These creatures of living music are born from overwrought emotions, and they feed off the vitality and personality of mortals.

## Song Searchers

Ostinatos wander the mortal world as repetitive snippets of song, searching for hosts and rich feeding grounds. They enter hosts secretly, remaining undetected to prolong their voracious feasting.

## Statblock

```ad-statblock
title: Ostinato
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ostinato.webp#token)
*Medium aberration, Chaotic Neutral*

- **Armor Class** 15
- **Hit Points** 39 (`6d8 + 12`)
- **Speed** 0 ft., fly 50 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|20 (+5)|15 (+2)| 5 (-3)|12 (+1)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Vulnerabilities** thunder
- **Damage Resistances** acid; cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** telepathy 120 ft. understands Common but can't speak
- **Challenge** 4

## Traits

***Incorporeal Movement.*** The ostinato can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Invisibility.*** The ostinato is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible).

***Magic Resistance.*** The ostinato has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The ostinato makes two Cacophony Burst attacks.

***Cacophony Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 60 ft., one target. *Hit:* `dice:3d8+3|noform|avg|text(16)` (`3d8 + 3`) thunder damage.

***Aural Symbiosis (Recharge 6).*** One Humanoid that the ostinato can see within 5 feet of it must succeed on a DC 13 Charisma saving throw or the ostinato merges with the target, becoming an enjoyable, repetitive tune in its host's mind. The ostinato can't be targeted by any attack, spell, or other effect, and it can't attack. The host retains control of its body and is aware of the ostinato's presence only as a melody, not as a living entity. The host no longer needs to eat or drink, gains the ostinato's Magic Resistance trait, and has advantage on Charisma checks. In addition, the host has disadvantage on Wisdom saving throws, and it can't maintain [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) on spells or other effects. At the end of each long rest, the host can make a DC 13 Wisdom ([Insight](2-Mechanics/CLI/rules/skills.md#Insight)) check, realizing that the music it hears comes from an external entity on a success.

The Aural Symbiosis lasts until the host drops to 0 hp, the ostinato ends it as a bonus action, or the ostinato is forced out by an effect like the [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md) spell. When the Aural Symbiosis ends, the ostinato bursts out from the host's mind in a thunderous explosion of sound, reappearing in an unoccupied space within 5 feet of the host. Each creature within 15 feet of the ostinato when it exits, including the host, must make a DC 13 Constitution saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) thunder damage on a failed save, or half as much damage on a successful one. The host is immune to this ostinato's Aural Symbiosis for 24 hours after succeeding on the saving throw or after the Aural Symbiosis ends.

***Contagious Tune (1/Day).*** While merged with a Humanoid host, the ostinato fills the minds of nearby creatures with the same catchy tune playing in its host's mind. Each creature within 30 feet of the ostinato's host must make a DC 13 Charisma saving throw, taking `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage on a failed save, or half as much damage on a successful one. The ostinato then gains temporary hp equal to the single highest amount of psychic damage dealt. A [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened) creature is immune to Contagious Tune.
```
^statblock

## Environment

any