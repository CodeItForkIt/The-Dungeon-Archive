---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/12
- monster/size/large
- monster/type/monstrosity
aliases: ["Blazebear"]
---
# Blazebear
*Source: Vecna: Eve of Ruin p. 210*  

> [!quote] A quote from Clank, Warforged Merchant from Sharn  
> 
> Even the animals in the Mournland are warped by magic. You should see the bears—terrifying!

On the world of Eberron, many strange, magic-warped monsters have emerged from the depths of the war-wracked Mournland. The blazebear is one such monster, so named for its hulking, ursine figure and the glow of its eyes. This glow is magical energy that saturates the blazebear's entire body. Swipes from a blazebear's claws dole out painful wounds and can end spells, and its gaze can stun prey.

```ad-statblock
title: Blazebear
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Blazebear.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 189 (`18d10 + 90`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|17 (+3)|21 (+5)| 3 (-4)|13 (+1)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +11, Charisma +7
- **Skills** Perception +5
- **Senses** darkvision 120 ft., passive Perception 15
- **Languages** —
- **Challenge** 12

## Traits

***Magic Resistance.*** The blazebear has advantage on saving throws against spells and other magical effects.

***Mist Sight.*** The blazebear can see normally through heavily obscured areas created by mist or fog, including areas created by spells such as Fog Cloud.

## Actions

***Multiattack.*** The blazebear makes two Bite attacks. It can replace one attack with Stunning Gaze if available.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+7|noform|avg|text(20)` (`2d12 + 7`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) force damage.

***Stunning Gaze (Recharge 5-6).*** The blazebear targets two creatures it can see within 120 feet of itself. Each target must succeed on a DC 15 Wisdom saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of the blazebear's next turn.

## Reactions

***Antimagic Swipe.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one creature casting a spell of 3rd level or lower. *Hit:* `dice:4d10|noform|avg|text(22)` (`4d10`) force damage, and the target must succeed on a DC 15 Intelligence saving throw or the spell fails and has no effect.
```
^statblock