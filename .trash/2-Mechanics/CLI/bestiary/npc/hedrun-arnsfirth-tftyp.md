---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Hedrun Arnsfirth"]
---
# Hedrun Arnsfirth
*Source: Tales from the Yawning Portal p. 160*  

```ad-statblock
title: Hedrun Arnsfirth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Hedrun%20Arnsfirth.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 37 (`5d8 + 15`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|14 (+2)|16 (+3)|12 (+1)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +4
- **Skills** Arcana +3, Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 3

## Traits

***Sunlight Sensitivity.*** While in sunlight, Hedrun has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Innate Spellcasting.*** Hedrun's innate spellcasting ability is Charisma (spell save DC 13). It can innately cast the following spells, requiring no verbal or material components:

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md)

**1/day each**: [fear](2-Mechanics/CLI/spells/fear.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [misty step](2-Mechanics/CLI/spells/misty-step.md)

## Actions

***Multiattack.*** Hedrun attacks twice with Grave Bolt.

***Grave Bolt.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 120 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) necrotic damage.

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.

A humanoid slain by this attack rises 24 hours later as a [zombie](2-Mechanics/CLI/bestiary/undead/zombie.md) under Hedrun's control, unless the humanoid is restored to life or its body is destroyed. Hedrun can have no more than twelve [zombies](2-Mechanics/CLI/bestiary/undead/zombie.md) under its control at one time.
```
^statblock