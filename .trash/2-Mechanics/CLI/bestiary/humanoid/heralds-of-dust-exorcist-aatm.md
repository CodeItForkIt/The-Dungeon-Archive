---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aatm
- monster/cr/6
- monster/size/small-or-medium
- monster/type/humanoid
aliases: ["Heralds of Dust Exorcist"]
---
# Heralds of Dust Exorcist
*Source: Adventure Atlas: The Mortuary*  

Dauntless in the face of death, exorcists in the Heralds of Dust cleanse hapless creatures and resting places haunted by ghosts, specters, and other malign entities that prevent the dead from being interred or jeopardize those already in repose. Though most Duster exorcists conduct their operations in the Mortuary, many heed calls throughout Sigil and the planes beyond.

The vagaries of undeath make spirits difficult to predict. Nevertheless, exorcists are well equipped for their work. Molded by experiences with apparitions and their ilk, exorcists channel the forces of death to preserve the living, commune with the dead, and drive evil spirits back to their graves. They can also fire versatile bolts of necrotic or radiant energy from their staves to repel a host of supernatural entities.

An exorcist's senses pierce the veil of death to perceive wandering ghosts on the Ethereal Plane as well as shadow demons, wraiths, and other incorporeal entities hiding in palls of darkness. With a brief reboant chant, an exorcist can expunge a harmful entity from a possessed creature—or make that creature vulnerable to a painful spiritual inhabitation.

```ad-statblock
title: Heralds of Dust Exorcist
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AATM/Heralds%20of%20Dust%20Exorcist.webp#token)
*Small or Medium humanoid, Any alignment*

- **Armor Class** 13 (16 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|16 (+3)|16 (+3)|17 (+3)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +6, Wisdom +5, Charisma +3
- **Skills** Arcana +6, Perception +5, Religion +6
- **Senses** truesight 60 ft., passive Perception 15
- **Damage Resistances** necrotic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common plus three more languages
- **Challenge** 6

## Traits

***Incorruptible Vessel.*** The exorcist can't be possessed by Celestials, Fiends, or Undead.

***Spellcasting.*** The exorcist casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 14, `dice:1d20+6|noform|text(+6)` to hit with spell attacks):

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [mage hand](2-Mechanics/CLI/spells/mage-hand.md)

**1/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [dispel evil and good](2-Mechanics/CLI/spells/dispel-evil-and-good.md)

**2/day each**: [protection from evil and good](2-Mechanics/CLI/spells/protection-from-evil-and-good.md), [remove curse](2-Mechanics/CLI/spells/remove-curse.md), [speak with dead](2-Mechanics/CLI/spells/speak-with-dead.md)

## Actions

***Multiattack.*** The exorcist makes two Grave Burst attacks.

***Grave Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:3d10+3|noform|avg|text(19)` (`3d10 + 3`) necrotic or radiant damage (exorcist's choice).

***Admit Entity (Recharge 5-6).*** The exorcist thins the veil of death for a creature it can see within 60 feet of itself, exposing the target to malevolent entities. The target must make a DC 14 Charisma saving throw. On a failed save, the target takes `dice:8d8|noform|avg|text(36)` (`8d8`) psychic damage and has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition for 1 minute, during which time it retches and babbles incoherently in a voice that is not its own. On a successful save, the target takes half as much damage only. An [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock