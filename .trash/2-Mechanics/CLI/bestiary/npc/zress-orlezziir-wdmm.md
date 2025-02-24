---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Zress Orlezziir"]
---
# Zress Orlezziir
*Source: Waterdeep: Dungeon of the Mad Mage p. 136*  

```ad-statblock
title: Zress Orlezziir
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Zress%20Orlezziir.webp#token)
*Medium humanoid (elf), Neutral Evil*

- **Armor Class** 16 ([chain mail](2-Mechanics/CLI/items/chain-mail.md))
- **Hit Points** 162 (`25d8 + 50`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|19 (+4)|15 (+2)|12 (+1)|14 (+2)|13 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Constitution +6, Wisdom +6
- **Skills** Perception +6, Stealth +8
- **Senses** darkvision 120 ft., passive Perception 16
- **Languages** Elvish, Undercommon
- **Challenge** 9

## Traits

***Battle Command.*** As a bonus action, Zress targets one ally he can see within 30 feet of him. If the target can see or hear Zress, the target can use its reaction to make one melee attack or to take the Dodge or Hide action.

***Fey Ancestry.*** Zress has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put Zress to sleep.

***Sunlight Sensitivity.*** While in sunlight, Zress has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Innate Spellcasting.*** Zress's innate spellcasting ability is Charisma (spell save DC 13). He can innately cast the following spells, requiring no material components:

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md)

**1/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [levitate](2-Mechanics/CLI/spells/levitate.md) (self only)

## Actions

***Multiattack.*** Zress makes three attacks: two with his scimitar and one with his whip or his hand crossbow.

***Scimitar.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) slashing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage.

***Whip.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d4+4|noform|avg|text(6)` (`1d4 + 4`) slashing damage. If the target is an ally, it has advantage on attack rolls until the end of its next turn.

***Hand Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 30/120 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. The target regains consciousness if it takes damage or if another creature takes an action to shake it.

## Reactions

***Parry.*** Zress adds 3 to his AC against one melee attack that would hit him. To do so, Zress must see the attacker and be wielding a melee weapon.
```
^statblock