---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Nythalyn Henlifel"]
---
# Nythalyn Henlifel
*Source: Phandelver and Below: The Shattered Obelisk p. 114*  

```ad-statblock
title: Nythalyn Henlifel
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Nythalyn%20Henlifel.webp#token)
*Medium humanoid (elf), Neutral*

- **Armor Class** 18 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 71 (`11d8 + 22`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|18 (+4)|14 (+2)|11 (+0)|13 (+1)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Constitution +5, Wisdom +4
- **Skills** Perception +4, Stealth +10
- **Senses** darkvision 120 ft., passive Perception 14
- **Languages** Elvish, Undercommon
- **Challenge** 5

## Traits

***Fey Ancestry.*** Nythalyn has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put Nythalyn to sleep.

***Sunlight Sensitivity.*** While in sunlight, Nythalyn has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Innate Spellcasting.*** Nythalyn's spellcasting ability is Charisma (spell save DC 12). It can innately cast the following spells, requiring no material components:

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md)

**1/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [levitate](2-Mechanics/CLI/spells/levitate.md) (self only)

## Actions

***Multiattack.*** Nythalyn makes two shortsword attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.

***Hand Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 30/120 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. The target wakes up if it takes damage or if another creature takes an action to shake it awake.

## Reactions

***Parry.*** Nythalyn adds 3 to its AC against one melee attack that would hit it. To do so, Nythalyn must see the attacker and be wielding a melee weapon.
```
^statblock