---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdh
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/elf
aliases: ["Drow Gunslinger"]
---
# Drow Gunslinger
*Source: Waterdeep: Dragon Heist p. 201*  

Firearms aren't widely available in the North, but some members of Bregan D'aerthe are equipped with Lantanese pistols, bullets, and packets of smokepowder. These drow gunslingers are expert pistoleers, as skilled with their guns as the best archers are with their bows.

```ad-statblock
title: Drow Gunslinger
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDH/Drow%20Gunslinger.webp#token)
*Medium humanoid (elf), Any alignment*

- **Armor Class** 18 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 84 (`13d8 + 26`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|18 (+4)|14 (+2)|11 (+0)|13 (+1)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +6, Constitution +4, Wisdom +3
- **Skills** Perception +3, Stealth +8
- **Senses** darkvision 120 ft., passive Perception 13
- **Languages** Elvish, Undercommon
- **Challenge** 4

## Traits

***Fey Ancestry.*** The drow has advantage on saving throws against being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), and magic can't put the drow to sleep.

***Gunslinger.*** Being within 5 feet of a hostile creature or attacking at long range doesn't impose disadvantage on the drow's ranged attack rolls with a pistol. In addition, the drow ignores half cover and three-quarters cover when making ranged attacks with a pistol.

***Sunlight Sensitivity.*** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Innate Spellcasting.*** The drow's spellcasting ability is Charisma (spell save DC 12) It can innately cast the following spells, requiring no material components:

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md)

**1/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [levitate](2-Mechanics/CLI/spells/levitate.md) (self only)

## Actions

***Multiattack.*** The drow makes two shortsword attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage.

***Poisonous Pistol.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 30/90 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) poison damage.
```
^statblock