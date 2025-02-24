---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/5
- monster/size/large
- monster/type/elemental
aliases: ["Animated Delerium Sludge"]
---
# Animated Delerium Sludge
*Source: Dungeons of Drakkenheim p. 203*  

Contaminated Elementals can be found all over Drakkenheim, often in areas where the eldritch magics are especially concentrated. Many who have encountered these elementals have spoken of the city itself coming to life to attack them. Reports of ruins reaching out and crushing adventurers, burning flames moving and hunting with minds of their own, or contaminated pools lurching to engulf passersby have been heard. Even the blowing air itself has mustered parts of the Haze into shifting clouds that stalk adventurers through the streets. These magical creatures are a constant reminder that nothing in the city can be trusted, and that nowhere is truly safe.

```ad-statblock
title: Animated Delerium Sludge
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Animated%20Delerium%20Sludge.webp#token)
*Large elemental, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 114 (`12d10 + 48`)
- **Speed** 30 ft., swim 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|18 (+4)| 5 (-3)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** acid; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Deep Speech
- **Challenge** 5

## Traits

***Sludge Form.*** The animated sludge can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.

## Actions

***Contaminated Touch.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. In addition, a target hit by this attack must succeed on a DC 15 Constitution saving throw or gain one level of contamination.

***Engulf.*** Each creature in the animated sludge's space must succeed on a DC 15 Strength saving throw. On a failed save, a creature becomes [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the sludge if it is Large or smaller (escape DC 14). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). If the saving throw is successful, the target is pushed out of the sludge's space.

The sludge can grapple one Large creature or up to two Medium or smaller creatures at one time. At the start of each of the sludge's turns, each target [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it takes `dice:8d6|noform|avg|text(28)` (`8d6`) necrotic damage and must succeed on a DC 15 Constitution saving throw or gain one level of contamination.

A creature within 5 feet of the sludge can attempt to pull a creature or object out of it. This takes an action and requires a successful DC 14 Strength check.
```
^statblock