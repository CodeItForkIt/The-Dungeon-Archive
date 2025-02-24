---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Oozing Vulture"]
---
# Oozing Vulture
*Source: Grim Hollow: Lairs of Etharis p. 38*  

> [!quote]  
> 
> The squawking and flapping of wings didn't cause me to flee. The blood-dripping feathers and gnarled beak? A whole different story.

## Salvage

An oozing vulture's feathers are prized by tailors and arcanists alike. A character can collect `dice:2d10|noform|avg` (`2d10`) feathers with a successful DC 10 Dexterity ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)) check. Each feather is worth 3 gp.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Oozing vultures have a vicious bite that can knock their victims prone.  
- **DC 15 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Oozing vultures can track the smell of blood over great distances.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** An oozing vulture is enraged by the smell of blood and gains advantage on attacks against wounded prey.  

## Statblock

```ad-statblock
title: Oozing Vulture
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Oozing%20Vulture.webp#token)
*Medium monstrosity, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 65 (`10d8 + 10`)
- **Speed** 20 ft., fly 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|13 (+1)|12 (+1)| 5 (-3)|14 (+2)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +3
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** —
- **Challenge** 2

## Traits

***Blood Frenzy.*** The oozing vulture has advantage on melee attack rolls against any creature that doesn't have all its hit points.

***Keen Sight and Smell.*** The oozing vulture has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight or smell.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock