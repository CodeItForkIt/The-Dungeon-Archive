---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/9
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Evoker Wizard"]
---
# Evoker Wizard
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 262*  

Evokers harness arcane energy to destroy. Many armies employ evokers to rain destruction down on enemy forces.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

## Statblock

```ad-statblock
title: Evoker Wizard
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Evoker%20Wizard.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 121 (`22d8 + 22`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|12 (+1)|17 (+3)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +7, Wisdom +5
- **Skills** Arcana +7, History +7
- **Senses** passive Perception 11
- **Languages** any four languages
- **Challenge** 9

***Spellcasting.*** The evoker casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [message](2-Mechanics/CLI/spells/message.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [wall of ice](2-Mechanics/CLI/spells/wall-of-ice.md)

**2/day each**: [ice storm](2-Mechanics/CLI/spells/ice-storm.md), [lightning bolt](2-Mechanics/CLI/spells/lightning-bolt.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md)

## Actions

***Multiattack.*** The evoker makes three Arcane Burst attacks.

***Arcane Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:4d10+3|noform|avg|text(25)` (`4d10 + 3`) force damage.

***Sculpted Explosion (Recharge 4-6).*** The evoker unleashes a magical explosion of a particular damage type: cold, fire, lightning, or thunder. The magic erupts in a 20-foot-radius sphere centered on a point within 150 feet of the evoker. Each creature in that area must make a DC 15 Dexterity saving throw. The evoker can select up to three creatures it can see in the area to ignore the spell, as the evoker sculpts the spell's energy around them. On a failed save, a creature takes `dice:9d8|noform|avg|text(40)` (`9d8`) damage of the chosen type and is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). On a successful save, a creature takes half as much damage and isn't knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

urban