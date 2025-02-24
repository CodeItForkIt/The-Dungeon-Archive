---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/9
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Abjurer Wizard"]
---
# Abjurer Wizard
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 260*  

Abjurers specialize in creating protective magical wards. Monarchs, nobles, and other wealthy individuals commonly hire abjurers to provide protection.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

## Statblock

```ad-statblock
title: Abjurer Wizard
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Abjurer%20Wizard.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 104 (`16d8 + 32`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|14 (+2)|18 (+4)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +8, Wisdom +5
- **Skills** Arcana +8, History +8
- **Senses** passive Perception 11
- **Languages** any four languages
- **Challenge** 9

***Spellcasting.*** The abjurer casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 16):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [message](2-Mechanics/CLI/spells/message.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [arcane lock](2-Mechanics/CLI/spells/arcane-lock.md), [banishment](2-Mechanics/CLI/spells/banishment.md), [globe of invulnerability](2-Mechanics/CLI/spells/globe-of-invulnerability.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [wall of force](2-Mechanics/CLI/spells/wall-of-force.md)

**2/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [lightning bolt](2-Mechanics/CLI/spells/lightning-bolt.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md)

## Actions

***Multiattack.*** The abjurer makes three Arcane Burst attacks.

***Arcane Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:3d10+4|noform|avg|text(20)` (`3d10 + 4`) force damage.

***Force Blast.*** Each creature in a 20-foot cube originating from the abjurer must make a DC 16 Constitution saving throw. On a failed save, a creature takes `dice:8d8|noform|avg|text(36)` (`8d8`) force damage and is pushed up to 10 feet away from the abjurer. On a successful save, a creature takes half as much damage and isn't pushed.

## Reactions

***Arcane Ward (Recharge 4-6).*** When the abjurer or a creature it can see within 30 feet of it takes damage, the abjurer magically creates a protective barrier around itself or the other creature. The barrier reduces the damage to the protected creature by `dice:4d10+4|noform|avg|text(26)` (`4d10 + 4`), to a minimum of 0, and then vanishes.
```
^statblock

## Environment

urban