---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/rot
- monster/cr/11
- monster/size/medium
- monster/type/undead
aliases: ["Naergoth Bladelord"]
---
# Naergoth Bladelord
*Source: The Rise of Tiamat p. 90, Tyranny of Dragons p. 186*  

```ad-statblock
title: Naergoth Bladelord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/RoT/Naergoth%20Bladelord.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 135 (`18d8 + 54`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|16 (+3)|12 (+1)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +5, Wisdom +6
- **Skills** Perception +6, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 16
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 11

## Traits

***Sunlight Sensitivity.*** While in sunlight, Naergoth has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** Naergoth makes three attacks, either with his longsword or longbow. He can use Life Drain in place of one longsword attack.

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:5d6+3|noform|avg|text(20)` (`5d6 + 3`) necrotic damage. The target must succeed on a DC 15 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) slashing damage, or `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) if used with two hands, plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+1|noform|avg|text(5)` (`1d8 + 1`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.
```
^statblock