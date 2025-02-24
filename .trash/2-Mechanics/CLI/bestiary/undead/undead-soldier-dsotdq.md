---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Undead Soldier"]
---
# Undead Soldier
*Source: Dragonlance: Shadow of the Dragon Queen p. 96*  

```ad-statblock
title: Undead Soldier
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Undead%20Soldier.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 18 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)|10 (+0)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 3

## Actions

***Multiattack.*** The soldier makes two longsword attacks or two longbow attacks. It can use its Life Drain in place of one longsword attack.

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

A humanoid slain by this attack rises 24 hours later as a [zombie](2-Mechanics/CLI/bestiary/undead/zombie.md) under the soldier's control, unless the humanoid is restored to life or its body is destroyed. The soldier can have no more than twelve zombies under its control at one time.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) slashing damage, or `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) slashing damage if used with two hands.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.
```
^statblock