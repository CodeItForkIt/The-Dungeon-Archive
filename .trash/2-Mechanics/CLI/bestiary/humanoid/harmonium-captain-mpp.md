---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/8
- monster/size/small-or-medium
- monster/type/humanoid
aliases: ["Harmonium Captain"]
---
# Harmonium Captain
*Source: Morte's Planar Parade p. 58, Sigil and the Outlands, Turn of Fortune's Wheel*  

Harmonium captains lead peacekeeper patrols throughout Sigil. They bolster their subordinates in battle and bring the authority of the Harmonium crashing down on suspects with their commands.

```ad-statblock
title: Harmonium Captain
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Harmonium%20Captain.webp#token)
*Small or Medium humanoid, Any alignment*

- **Armor Class** 20 ([plate armor](2-Mechanics/CLI/items/plate-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 110 (`17d8 + 34`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|10 (+0)|14 (+2)|12 (+1)|16 (+3)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Wisdom +6
- **Skills** Perception +6
- **Senses** passive Perception 16
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common plus one more language
- **Challenge** 8

## Traits

***Aura of Command.*** Allies within 30 feet of the captain are immune to the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) conditions. This aura is suppressed while the captain has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

## Actions

***Multiattack.*** The captain makes three Harmonium Blade attacks. The captain can also use Dictate if available.

***Harmonium Blade.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) lightning damage.

***Dictate (Recharge 5-6).*** The captain verbally commands up to three creatures it can see within 60 feet of itself. This magical command must be to undertake an action or to refrain from taking actions (for example, "Throw down your weapons").

A target must succeed on a DC 14 Wisdom saving throw or have the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) condition for 1 minute, during which time it follows the captain's command. The effect ends early if the target takes damage or if it successfully completes the command. A target automatically succeeds on its saving throw if the command is directly harmful to itself, such as commanding it to walk into fire.

A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a successful save.
```
^statblock