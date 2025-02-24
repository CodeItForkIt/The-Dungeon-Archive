---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1-4
- monster/size/small
- monster/type/fey
aliases: ["Faevlin"]
---
# Faevlin
*Source: Grim Hollow: Lairs of Etharis p. 9*  

> [!quote]  
> 
> Never make a deal with the fey. Never make a deal with a goblin. And if you ever meet a faevlin, you'll know why.

## Salvage

Faevlins love to collect objects that increase their personal prestige and power. Every faevlin is likely to have a few personal trinkets like this, along with the occasional item of real worth.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** A faevlin can teleport away from attackers but does so in a manner even the faevlin can't predict.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Faevlins are goblins cursed by powerful fey magic  
- **DC 20 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** A faevlin can't be charmed by nonfey, but they have been known to pretend to be charmed to trick the enchanter.  

## Statblock

```ad-statblock
title: Faevlin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Faevlin.webp#token)
*Small fey, Neutral Evil*

- **Armor Class** 15 ([leather armor](2-Mechanics/CLI/items/leather-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 10 (`3d6`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|14 (+2)|10 (+0)|10 (+0)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4
- **Senses** darkvision 60 ft., passive Perception 11
- **Languages** Goblin, Sylvan
- **Challenge** 1/4

## Traits

***Fey Touched.*** Magic can't put the faevlin to sleep. Only a creature of the fey type can cause the faevlin to become [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and a faevlin always knows if a nonfey creature attempted to render it [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed).

***Sneaky.*** The faevlin can use a bonus action to take the Hide action.

## Actions

***Scimitar.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) slashing damage.

***Shortbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage.

## Reactions

***Fey Fade.*** When an attack misses a faevlin, the faevlin can teleport up to 30 feet in a random direction, arriving in a safe, unoccupied space.
```
^statblock