---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/wizard
aliases: ["Ringlerun"]
---
# Ringlerun
*Source: The Wild Beyond the Witchlight p. 227*  

Ringlerun became an adventurer to better satisfy his craving for arcane knowledge. One of his adventures took him into an underwater tomb, where he tricked a marid into surrendering a staff of power. This staff greatly increased Ringlerun's capabilities and made him the envy of many rival spellcasters.

Ringlerun has a good heart, but he's easily distracted by intellectual pursuits. He would rather spend time in quiet contemplation or reading than in frivolous conversation.

```ad-statblock
title: Ringlerun
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Ringlerun.webp#token)
*Medium humanoid (human, wizard), Lawful Good*

- **Armor Class** 12 ([staff of power](2-Mechanics/CLI/items/staff-of-power.md))
- **Hit Points** 42 (`12d8 - 12`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|10 (+0)| 9 (-1)|17 (+3)|13 (+1)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +2, Dexterity +3, Constitution +2, Intelligence +6, Wisdom +4, Charisma +3
- **Skills** Arcana +6, History +6
- **Senses** passive Perception 11
- **Languages** Common, Draconic, Dwarvish, Elvish
- **Challenge** 5

## Traits

***Special Equipment.*** Ringlerun wields a [staff of power](2-Mechanics/CLI/items/staff-of-power.md). It has 20 charges when fully charged and regains `dice:2d8+4|noform|avg` (`2d8 + 4`) expended charges daily at dawn. If its last charge is expended, roll a `dice:d20|noform|avg` (`d20`). On a 1, the staff retains its +2 bonus to attack and damage rolls but loses its other properties; on a 20, it regains `dice:1d8+2|noform|avg` (`1d8 + 2`) charges.

***Spellcasting.*** Ringlerun casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [fly](2-Mechanics/CLI/spells/fly.md), [knock](2-Mechanics/CLI/spells/knock.md)

**3/day each**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [sleep](2-Mechanics/CLI/spells/sleep.md)

## Actions

***Multiattack.*** Ringlerun makes three [staff of power](2-Mechanics/CLI/items/staff-of-power.md) or Freezing Ray attacks. He can replace one of those attacks with a use of Spellcasting.

***Staff of Power.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+1|noform|avg|text(4)` (`1d6 + 1`) bludgeoning damage, or `dice:1d8+1|noform|avg|text(5)` (`1d8 + 1`) bludgeoning damage when used with two hands, and Ringlerun can expend 1 of the staff's charges to deal an extra `dice:1d6|noform|avg|text(3)` (`1d6`) force damage.

***Freezing Ray.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 120 ft., one creature. *Hit:* `dice:6d8|noform|avg|text(27)` (`6d8`) cold damage.

***Staff Spell.*** While holding his [staff of power](2-Mechanics/CLI/items/staff-of-power.md), Ringlerun can expend 1 or more of its charges to cast one of the following spells from it (spell save DC 14, `dice:1d20+8|noform|text(+8)` to hit with spell attacks): cone of cold (`dice:8d8|noform|avg` (`8d8`) cold damage; 5 charges), fireball (`dice:10d6|noform|avg` (`10d6`) fire damage; 5 charges), globe of invulnerability (6 charges), hold monster (5 charges), levitate (2 charges), lightning bolt (`dice:10d6|noform|avg` (`10d6`) lightning damage; 5 charges), magic missile (1 charge), ray of enfeeblement (1 charge), or wall of force (5 charges).
```
^statblock