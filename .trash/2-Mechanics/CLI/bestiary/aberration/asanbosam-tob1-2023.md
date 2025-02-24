---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/forest
- monster/environment/hill
- monster/size/large
- monster/type/aberration
aliases: ["Asanbosam"]
---
# Asanbosam
*Source: Tome of Beasts 1 (2023 Edition) p. 27*  

*A hirsute hulk with bulging, bloodshot eyes perches high in a tree, ready to seize unwary passersby with its rusty, hook-like talons.*

## Iron Hooks and Fangs

Asanbosam resemble hairy ogres from the waist up, but with muscular, flexible legs much longer than those of an ogre. These odd appendages end in feet with hook-like talons, and both the creature's hooks and its fangs are composed of iron rather than bone or other organic material. These iron fangs and claws mark an asanbosam's age, not just by their size but also by their color. The youngest specimens have shiny gray hooks and fangs, while those of the older asanbosams are discolored and rusty.

## Iron Eaters

The asanbosam diet includes iron in red meat, poultry, fish, and leaf vegetables, and—in times of desperation—grinding iron filings off their own hooks to slake their cravings. The asanbosams' taste for fresh blood and humanoid flesh led to the folklore that they are vampiric (not true).

## Tree Lairs

Asanbosams spend most of their lives in trees, where they build nestlike houses or platforms of rope and rough planks. They don't fear magic; most tribes count at least one spellcaster among its members.

## Statblock

```ad-statblock
title: Asanbosam
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Asanbosam.webp#token)
*Large aberration, Chaotic Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 102 (`12d10 + 36`)
- **Speed** 40 ft., climb 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|13 (+1)|17 (+3)|11 (+0)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Acrobatics +4, Perception +3, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Languages** Giant
- **Challenge** 5

## Traits

***Spider Climb.*** The asanbosam can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The asanbosam makes one Bite attack and one Claws attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) piercing damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) poison damage and contract a disease. Until the disease ends, the creature is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). Every 24 hours that elapse, the infected creature must repeat the saving throw. On a success, the disease ends. On a failure, the creature's hp maximum is reduced by `dice:1d10|noform|avg|text(5)` (`1d10`). This reduction lasts until the disease ends. The target dies if its hp maximum is reduced to 0.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+4|noform|avg|text(20)` (`3d10 + 4`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the asanbosam can't use its Claws on another target. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or contract the disease described in the Bite attack.

## Bonus Actions

***Arboreal Escape.*** While in a tree, the asanbosam takes the Disengage or Hide action.
```
^statblock

## Environment

forest, hill