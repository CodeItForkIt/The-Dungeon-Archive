---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Master Sage"]
---
# Master Sage
*Source: Candlekeep Mysteries p. 9*  

Candlekeep's resident lore experts are master sages and sages who dedicate themselves to scholarship above all.

```ad-statblock
title: Master Sage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Master%20Sage.webp#token)
*Medium humanoid (any race), Unaligned*

- **Armor Class** 10
- **Hit Points** 54 (`12d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|10 (+0)|10 (+0)|20 (+5)|18 (+4)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Arcana +11, History +11, Insight +7, Investigation +11, Medicine +10, Nature +11, Religion +11
- **Senses** passive Perception 14
- **Languages** Common plus any five languages
- **Challenge** 5

***Spellcasting.*** The sage casts one of the following spells, using Intelligence as the spellcasting ability (save DC 14, `dice:1d20+6|noform|text(+6)` to hit with spell attacks):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [mending](2-Mechanics/CLI/spells/mending.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md), 

**1/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [contact other plane](2-Mechanics/CLI/spells/contact-other-plane.md), [Drawmij's instant summons](2-Mechanics/CLI/spells/drawmijs-instant-summons.md), [legend lore](2-Mechanics/CLI/spells/legend-lore.md), [locate creature](2-Mechanics/CLI/spells/locate-creature.md), [planar binding](2-Mechanics/CLI/spells/planar-binding.md), [polymorph](2-Mechanics/CLI/spells/polymorph.md), [protection from evil and good](2-Mechanics/CLI/spells/protection-from-evil-and-good.md), [scrying](2-Mechanics/CLI/spells/scrying.md), [sending](2-Mechanics/CLI/spells/sending.md), [true seeing](2-Mechanics/CLI/spells/true-seeing.md)

**3/day each**: [comprehend languages](2-Mechanics/CLI/spells/comprehend-languages.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), , [identify](2-Mechanics/CLI/spells/identify.md), [levitate](2-Mechanics/CLI/spells/levitate.md), [locate object](2-Mechanics/CLI/spells/locate-object.md), , [Tenser's Floating Disk](2-Mechanics/CLI/spells/tensers-floating-disk.md), [unseen servant](2-Mechanics/CLI/spells/unseen-servant.md)

## Actions

***Shocking Grasp (Cantrip).*** *Melee Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit (with advantage if the target is wearing armor made of metal), reach 5 ft., one creature. *Hit:* `dice:3d8|noform|avg|text(13)` (`3d8`) lightning damage, and the target can't take reactions until the start of its next turn.

***Fireball (3rd-Level Spell; 3/Day).*** The sage creates a fiery explosion centered on a point it can see within 150 feet of it. Each creature in a 20-foot-radius sphere centered on that point must make a DC 14 Dexterity saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) fire damage on a failed save, or half as much damage on a successful one. The fire spreads around corners and ignites flammable objects in the area that aren't being worn or carried.

## Reactions

***Shield (1st-Level Spell; 3/Day).*** When the sage is hit by an attack or targeted by a [magic missile](2-Mechanics/CLI/spells/magic-missile.md) spell, it calls forth an [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) barrier of magical force that protects it. Until the start of its next turn, the sage has a +5 bonus to AC, including against the triggering attack, and it takes no damage from magic missile.
```
^statblock