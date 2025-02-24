---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Sarusanda Allester"]
---
# Sarusanda Allester
*Source: Vecna: Eve of Ruin*  

```ad-statblock
title: Sarusanda Allester
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Sarusanda%20Allester.webp#token)
*Medium humanoid (human), Lawful Neutral*

- **Armor Class** 11
- **Hit Points** 77 (`14d8 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|12 (+1)|12 (+1)|19 (+4)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +7, Wisdom +6, Charisma +5
- **Skills** Arcana +10, History +7, Nature +7, Religion +10
- **Senses** truesight 30 ft., passive Perception 13
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Celestial, Common, Draconic, Elvish, any four languages, telepathy 120 ft.
- **Challenge** 8

***Innate Spellcasting (Psionics).*** Sarusanda casts one of the following spells, requiring no components and using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [levitate](2-Mechanics/CLI/spells/levitate.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [sending](2-Mechanics/CLI/spells/sending.md), [speak with dead](2-Mechanics/CLI/spells/speak-with-dead.md)

**1/day each**: [Otiluke's resilient sphere](2-Mechanics/CLI/spells/otilukes-resilient-sphere.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

## Actions

***Multiattack.*** Sarusanda attacks twice.

***Force Bolt.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one target. *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) force damage, and if the target is a Large or smaller creature, Sarusanda can push it up to 10 feet away.

***Silver Longsword.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage, or `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) if used with two hands, plus `dice:4d8|noform|avg|text(18)` (`4d8`) force damage.

***Implode (Recharge 4-6).*** Each creature in a 20-foot-radius sphere centered on a point Sarusanda can see within 120 feet of it must succeed on a DC 15 Constitution saving throw or take `dice:6d8+4|noform|avg|text(31)` (`6d8 + 4`) force damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone) and moved to the unoccupied space closest to the sphere's center. Large and smaller objects that aren't being worn or carried in the sphere automatically take the damage and are similarly moved.

## Reactions

***Telekinetic Deflection.*** In response to being hit by an attack roll, Sarusanda increases its AC by 4 against the attack. If this causes the attack to miss, the attacker is hit by the attack instead.
```
^statblock