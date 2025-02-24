---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
aliases: ["Dawndrinker"]
---
# Dawndrinker
*Source: Grim Hollow: Lairs of Etharis p. 49*  

> [!quote]  
> 
> Sometimes it's darkest after the dawn.

## Salvage

Dawndrinkers have a special organ that stores and processes light the way that other creatures digest food. Most of the creature's body disintegrates after it dies, but this light stomach remains. Someone who has proficiency with alchemist's supplies, cook's utensils, or an herbalism kit can prepare the stomach with other ingredients worth 25 gp. If the preparer succeeds on a DC 13 Wisdom or Intelligence check, the organ makes a tasty, sweet meal for up to four creatures. After partaking, those creatures add 60 feet to their darkvision range for 24 hours, those that lack darkvision gain it to a range of 60 feet. All partakers also gain blindsight to a range of 10 feet for the same duration.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** A dawndrinker is a cunning predator that can easily hide and move in shadow. It greatly lessens and even extinguishes light sources.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A dawndrinker can sense light, its food, at a great distance. The monster is also resistant to fire, absorbing some of its energy, and immune to radiant damage, which is a source of quick nourishment for the dawndrinker.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A dawndrinker's attacks can temporarily take away the victim's ability to perceive light.  

## Statblock

```ad-statblock
title: Dawndrinker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Dawndrinker.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 114 (`12d10 + 48`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|19 (+4)| 3 (-4)|11 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** blindsight 120 ft., darkvision 240 ft., passive Perception 10
- **Damage Resistances** fire
- **Damage Immunities** radiant
- **Languages** —
- **Challenge** 5

## Traits

***Drink Light.*** The dawndrinker can take a bonus action to drink light within 30 feet of it. If it does so, nonmagical light sources in this area go out, extinguishing any flames that are the source of the light. Provided the light comes from an effect of 3rd level or lower, or a creature of CR 7 or lower, magical bright light becomes dim light, and magical dim light goes out. If a magical effect's light is extinguished, the effect is dispelled. A creature's or object's inherent light returns to normal after 1 minute. The dawndrinker can dim or extinguish stronger effects by succeeding on a Constitution check with a DC of 10 + the effect's level or 5 + the creator's CR, whichever is lower.

***Light Sense.*** The dawndrinker can sense any light source within 120 feet of it. This sense penetrates most barriers, but it is blocked by 3 feet of wood or dirt, 1 foot of stone, or 1 inch of metal.

***Radiant Absorption.*** Whenever the dawndrinker is subjected to radiant damage, it takes no damage and instead regains hit points equal to the radiant damage dealt.

***Shadow Cunning.*** In dim light or darkness, the dawndrinker can take a bonus action to use the Disengage or Hide actions.

## Actions

***Multiattack.*** The dawndrinker makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage and `dice:2d6|noform|avg|text(7)` (`2d6`) cold damage. If the target is a creature, it must succeed on a DC 13 Constitution saving throw or be [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of the dawndrinker's next turn.
```
^statblock