---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/8
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Diviner Wizard"]
---
# Diviner Wizard
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 261*  

Diviners peer into the future and know that knowledge is power. They might act aloof and mysterious, hinting at omens and secrets, or they might be know-it-alls, spilling insights to advance their own status.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

## Statblock

```ad-statblock
title: Diviner Wizard
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Diviner%20Wizard.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 90 (`20d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|11 (+0)|18 (+4)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +7, Wisdom +4
- **Skills** Arcana +7, History +7
- **Senses** passive Perception 11
- **Languages** any four languages
- **Challenge** 8

***Spellcasting.*** The diviner casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [message](2-Mechanics/CLI/spells/message.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [true seeing](2-Mechanics/CLI/spells/true-seeing.md)

**2/day each**: [arcane eye](2-Mechanics/CLI/spells/arcane-eye.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [fly](2-Mechanics/CLI/spells/fly.md), [lightning bolt](2-Mechanics/CLI/spells/lightning-bolt.md), [locate object](2-Mechanics/CLI/spells/locate-object.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [Rary's telepathic bond](2-Mechanics/CLI/spells/rarys-telepathic-bond.md)

## Actions

***Multiattack.*** The diviner makes three Arcane Burst attacks.

***Arcane Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:3d10+4|noform|avg|text(20)` (`3d10 + 4`) radiant damage.

***Overwhelming Revelation (Recharge 5-6).*** The diviner magically creates a burst of illumination in a 10-foot-radius sphere centered on a point within 120 feet of it. Each creature in that area must make a DC 15 Wisdom saving throw. On a failed save, a creature takes `dice:10d8|noform|avg|text(45)` (`10d8`) psychic damage and is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of the diviner's next turn. On a successful save, the creature takes half as much damage and isn't [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned).

## Reactions

***Portent (3/Day).*** When the diviner or a creature it can see makes an attack roll, a saving throw, or an ability check, the diviner rolls a `dice:d20|noform|avg` (`d20`) and chooses whether to use that roll in place of the `dice:d20|noform|avg` (`d20`) rolled for the attack roll, saving throw, or ability check. 
```
^statblock

## Environment

urban