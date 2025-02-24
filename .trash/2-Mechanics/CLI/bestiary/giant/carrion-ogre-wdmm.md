---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/2
- monster/size/large
- monster/type/giant
aliases: ["Carrion Ogre"]
---
# Carrion Ogre
*Source: Waterdeep: Dungeon of the Mad Mage p. 189*  

A creature that has the body of an ogre and the head of a carrion crawler.

```ad-statblock
title: Carrion Ogre
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Carrion%20Ogre.webp#token)
*Large giant, Chaotic Evil*

- **Armor Class** 11 ([hide armor](2-Mechanics/CLI/items/hide-armor.md))
- **Hit Points** 59 (`7d10 + 21`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)| 8 (-1)|16 (+3)| 1 (-5)| 7 (-2)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 8
- **Languages** —
- **Challenge** 2

## Traits

***Tied Down.*** While lashed to the floor, the creature is [prone](2-Mechanics/CLI/rules/conditions.md#Prone) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). It also suffers from two levels of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion).

## Actions

***Multiattack.*** The creature makes two attacks: one with its tentacles and one with its bite.

***Tentacles.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one creature. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) poison damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. Until this poison ends, the target is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed). The target can repeat the saving throw at the end of each of its turns, ending the poison on itself on a success.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) piercing damage.
```
^statblock