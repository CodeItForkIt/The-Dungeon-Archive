---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Tomb Dwarf"]
---
# Tomb Dwarf
*Source: Tomb of Annihilation p. 135*  

Acererak abducted dwarf miners and transformed them into wights to exploit their expertise at underground construction.

```ad-statblock
title: Tomb Dwarf
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Tomb%20Dwarf.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 14 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
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

## Traits

***Sunlight Sensitivity.*** While in sunlight, the tomb dwarf has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

## Actions

***Multiattack.*** The tomb dwarf makes two longsword attacks or two crossbow attacks. It can use its Life Drain in place of one longsword attack.

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.A humanoid slain by this attack rises 24 hours later as a zombie under the tomb dwarf's control, unless the humanoid is restored to life or its body is destroyed. The tomb dwarf can have no more than twelve zombies under its control at one time.

***Battleaxe.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) slashing damage, or `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) slashing damage if used with two hands.

***Light Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.
```
^statblock