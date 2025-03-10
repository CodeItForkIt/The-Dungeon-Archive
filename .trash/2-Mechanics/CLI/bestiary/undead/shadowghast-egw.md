---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/5
- monster/size/medium
- monster/type/undead
aliases: ["Shadowghast"]
---
# Shadowghast
*Source: Explorer's Guide to Wildemount p. 299*  

A shadowghast is an undead assassin. Leaping out from the shadows and trailing tendrils of darkness, it closes in on its prey with nary a sound, then tears into a victim with its paralyzing claws and furious bite.

```ad-statblock
title: Shadowghast
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Shadowghast.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 15
- **Hit Points** 49 (`9d8 + 9`)
- **Speed** 35 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|20 (+5)|12 (+1)|12 (+1)|11 (+0)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +8
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 5

## Traits

***Stench.*** Any creature that starts its turn within 5 feet of the shadowghast must succeed on a DC 12 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the start of its next turn. On a successful saving throw, the creature is immune to this Stench for 24 hours.

***Shadow Stealth.*** While in dim light or darkness, the shadowghast can take the Hide action as a bonus action.

## Actions

***Multiattack.*** The shadowghast makes two attacks: one with its bite and one with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d8+2|noform|avg|text(11)` (`2d8 + 2`) slashing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) necrotic damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage. If the target is a creature other than an undead, it must succeed on a DC 12 Constitution saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock