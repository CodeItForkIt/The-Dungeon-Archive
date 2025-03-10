---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/7
- monster/environment/arctic
- monster/environment/desert
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid
aliases: ["Warlock of the Fiend"]
---
# Warlock of the Fiend
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 255*  

Warlocks of the Fiend gain their powers through magical pacts forged with archfiends of the Lower Planes. These warlocks often keep [imps](2-Mechanics/CLI/bestiary/fiend/imp.md) or [quasits](2-Mechanics/CLI/bestiary/fiend/quasit.md) as companions, and they tend toward philosophical extremes: consorting with fiendish cults or dedicating their lives to destroying such cults.

## Warlocks

Warlocks gain arcane might through magical pacts with mysterious entities. While some use their abilities to serve the sources of their power, others use them to undermine or even destroy these entities.

## Statblock

```ad-statblock
title: Warlock of the Fiend
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Warlock%20of%20the%20Fiend.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 13 (16 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|15 (+2)|12 (+1)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +4, Charisma +7
- **Skills** Arcana +4, Deception +7, Persuasion +7, Religion +4
- **Senses** darkvision 60 ft., passive Perception 11
- **Languages** any two languages (usually Abyssal or Infernal)
- **Challenge** 7

## Traits

***Dark One's Own Luck (Recharges after a Short or Long Rest).*** When the warlock makes an ability check or saving throw, it can add a `dice:d10|noform|avg` (`d10`) to the roll. It can do this after the roll is made but before any of the roll's effects occur.

***Spellcasting.*** The warlock casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 15): 

**At will**: [alter self](2-Mechanics/CLI/spells/alter-self.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** The warlock makes three Scimitar attacks.

***Scimitar.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage.

***Hellfire.*** Green flame explodes in a 10-foot-radius sphere centered on a point within 120 feet of the warlock. Each creature in that area must make a DC 15 Dexterity saving throw, taking `dice:3d10|noform|avg|text(16)` (`3d10`) fire damage and `dice:2d10|noform|avg|text(11)` (`2d10`) necrotic damage on a failed save, or half as much damage on a successful one.

## Reactions

***Fiendish Rebuke (3/Day).*** In response to being damaged by a visible creature within 60 feet of it, the warlock forces that creature to make a DC 15 Constitution saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

arctic, desert, underdark, urban