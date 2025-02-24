---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/5
- monster/size/medium
- monster/type/humanoid
aliases: ["Cavalier"]
---
# Cavalier
*Source: Dungeons of Drakkenheim p. 218*  

These righteous knights take to battle upon heavily armoured steeds or winged griffons.

```ad-statblock
title: Cavalier
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Cavalier.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 19 ([splint](2-Mechanics/CLI/items/splint-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 90 (`12d8 + 36`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|16 (+3)|10 (+0)|12 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +4, Charisma +5
- **Skills** Animal Handling +4, Athletics +7, Perception +4, Persuasion +5
- **Senses** passive Perception 14
- **Languages** Any two
- **Challenge** 5

## Traits

***Bravery.*** The cavalier has advantage on saving throws against being [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened).

***Light's Fury.*** The cavalier deals an extra `dice:2d8|noform|avg|text(9)` (`2d8`) radiant damage when it hits with a weapon attack.

***Skilled Rider.*** While mounted, the cavalier may force an attack targeted at their mount to target them instead.

***Spellcasting.*** The cavalier is an 8th-level spellcaster that uses Charisma as its spellcasting ability (spell save DC 13; `dice:1d20+5|noform|text(+5)` to hit with spell attacks). They have the following paladin spells prepared:

**1st level (4 slots)**: [bless](2-Mechanics/CLI/spells/bless.md), [command](2-Mechanics/CLI/spells/command.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md)

**2nd level (3 slots)**: [branding smite](2-Mechanics/CLI/spells/branding-smite.md), [find steed](2-Mechanics/CLI/spells/find-steed.md)

## Actions

***Multiattack.*** The cavalier makes two melee attacks.

***Lance.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit (with disadvantage against a target within 5 ft.), reach 10 ft., one target. *Hit:* `dice:1d12+4|noform|avg|text(10)` (`1d12 + 4`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) radiant damage.

***Javelin.*** *Melee or Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 30/120 ft., one target *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) radiant damage.
```
^statblock