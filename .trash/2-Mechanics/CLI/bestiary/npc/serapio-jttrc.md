---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/jttrc
- monster/cr/5
- monster/size/medium
- monster/type/fiend/demon
aliases: ["Serapio"]
---
# Serapio
*Source: Journeys through the Radiant Citadel p. 61*  

```ad-statblock
title: Serapio
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/JttRC/Serapio.webp#token)
*Medium fiend (demon), typically  Neutral Evil*

- **Armor Class** 13
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|17 (+3)|14 (+2)|10 (+0)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Constitution +5
- **Skills** Perception +5, Stealth +6
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Resistances** cold, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 5

## Traits

***Magic Resistance.*** Serapio has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** Serapio makes two Talon attacks.

***Talon.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(8)` (`1d8 + 3`) piercing damage plus `dice:3d8|noform|avg|text(14)` (`3d8`) poison damage.

***Change Shape.*** Serapio magically transforms into a Medium owl, while retaining its game statistics (other than its size). This transformation ends if Serapio is reduced to 0 hit points or if it uses its action to end it.

***Plague Winds (Fiend Form Only; Recharge 5-6).*** Serapio emits a chilling, disease-ridden wind in a 60-foot line that is 10 feet wide. Each creature in that area must succeed on a DC 13 Constitution saving throw or take `dice:4d12|noform|avg|text(26)` (`4d12`) cold damage and become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned).

While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, the creature can't regain hit points. At the end of every hour, the creature must succeed on a DC 13 Constitution saving throw or gain 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). If the creature is in direct sunlight when it makes this saving throw, it automatically succeeds on the save.

If the creature is targeted by magic that ends a poison or disease, such as lesser restoration, while the creature isn't in direct sunlight, the effect does not end.
```
^statblock