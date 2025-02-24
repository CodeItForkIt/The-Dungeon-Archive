---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dip
- monster/cr/1-4
- monster/size/small
- monster/type/humanoid/gnome
aliases: ["Rock Gnome Recluse"]
---
# Rock Gnome Recluse
*Source: Dragon of Icespire Peak p. 62*  

Rock gnome recluses are skilled in the arcane arts. They use their magical talents to create all kinds of wondrous inventions, very few of which work as intended.

```ad-statblock
title: Rock Gnome Recluse
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DIP/Rock%20Gnome%20Recluse.webp#token)
*Small humanoid (gnome), Chaotic Neutral*

- **Armor Class** 10 (13 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 7 (`2d6`)
- **Speed** 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|11 (+0)|10 (+0)|15 (+2)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Arcana +4, History +4
- **Senses** darkvision 60 ft., passive Perception 10
- **Languages** Common, Gnomish
- **Challenge** 1/4

## Traits

***Gnome Cunning.*** The gnome has advantage on Intelligence, Wisdom, and Charisma saving throws against magic.

***Spellcasting.*** The gnome is a 2nd-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 12, `dice:1d20+4|noform|text(+4)` to hit with spell attacks). It has the following wizard spells prepared:

**Cantrips (at will)**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](2-Mechanics/CLI/spells/ray-of-frost.md) (see "Actions" below)

**1st level (3 slots)**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [magic missile](2-Mechanics/CLI/spells/magic-missile.md) (see "Actions" below), [shield](2-Mechanics/CLI/spells/shield.md)

## Actions

***Magic Missile (Expends a 1st-Level Spell Slot).*** The gnome creates three magical darts. Each dart hits a creature the gnome chooses within 120 feet of it and deals `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) force damage.

***Ray of Frost.*** *Ranged Spell Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 60 ft., one creature. *Hit:* `dice:1d8|noform|avg|text(4)` (`1d8`) cold damage, and the target's speed is reduced by 10 feet until the start of the gnome's next turn.
```
^statblock