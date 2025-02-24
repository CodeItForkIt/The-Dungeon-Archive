---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/5
- monster/size/medium
- monster/type/construct
aliases: ["Android"]
---
# Android
*Source: Quests from the Infinite Staircase p. 194*  

Androids are synthetic humanoids built to assist their creators with highly specialized tasks. They are designed to be compliant and typically have friendly demeanors.

Every android has one or more upgrades to help it excel at its intended functions, but all androids are capable of defending themselves with concentrated bolts of force up close or from a distance.

Despite an android's sophisticated construction, electrical surges can temporarily disrupt its finely tuned components. Similarly, damage to its core processing functions or long stretches of isolation can wear down an android's critical faculties, causing it to behave erratically.

```ad-statblock
title: Android
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Android.webp#token)
*Medium construct, typically  Lawful Neutral*

- **Armor Class** 15 (natural armor)
- **Hit Points** 91 (`14d8 + 28`)
- **Speed** 30 ft., fly 30 ft. (hover; aerialist only), swim 30 ft. (diver only)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|15 (+2)|12 (+1)|13 (+1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5, Wisdom +4
- **Skills** History +4, Perception +7
- **Senses** blindsight 60 ft. (sentry only), darkvision 60 ft., passive Perception 17
- **Damage Resistances** acid, fire
- **Damage Immunities** cold, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common plus the languages spoken by its creator
- **Challenge** 5

## Traits

***Design Specialization.*** When the android is created, it gains one of six possible designs suited for its role (choose or roll a `dice:d6|noform|avg` (`d6`)): 1, aerialist; 2, diplomat; 3, diver; 4, duelist; 5, medic; 6, sentry. This design determines certain traits in this stat block.

***Lightning Overload.*** When the android takes lightning damage, it must succeed on a DC 10 Constitution saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of its next turn.

***Spellcasting (Diplomat and Medic Only).*** The android casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability:

**2/day each**: [Cure Wounds](2-Mechanics/CLI/spells/cure-wounds.md) (as a 3rd-level spell; medic only), [Identify](2-Mechanics/CLI/spells/identify.md), [Tongues](2-Mechanics/CLI/spells/tongues.md) (diplomat only)

## Actions

***Multiattack.*** The android makes two Force Strike attacks.

***Force Strike.*** *Melee or Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 40/120 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) force damage. If the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

## Reactions

***Parry (Duelist Only).*** The android adds 3 to its AC against one melee attack roll that would hit it. To do so, the android must see the attacker.
```
^statblock