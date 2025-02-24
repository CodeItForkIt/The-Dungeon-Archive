---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/druid
- monster/type/humanoid/gith
aliases: ["Githyanki Xenomancer"]
---
# Githyanki Xenomancer
*Source: Boo's Astral Menagerie p. 27, Light of Xaryxis*  

A githyanki xenomancer travels to the farthest reaches of Wildspace and the Astral Sea, even visiting worlds of the Material Plane from time to time, to study and catalog creatures it has never encountered before. Friendly contact with sapient creatures can bring the xenomancer's diplomatic skills to the forefront, while hostile contact becomes a test of the xenomancer's survival skills.

Sometimes a xenomancer's research requires that a specimen be captured and imprisoned (to study its behavior) or killed and dissected (to study or harvest its insides). Many xenomancers prefer to do this work in their laboratories on the Astral Plane.

```ad-statblock
title: Githyanki Xenomancer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Githyanki%20Xenomancer.webp#token)
*Medium humanoid (druid, gith), Any alignment*

- **Armor Class** 14
- **Hit Points** 157 (`21d8 + 63`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|18 (+4)|17 (+3)|15 (+2)|18 (+4)|13 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +8, Constitution +7, Wisdom +8
- **Skills** Animal Handling +8, Nature +6, Perception +8, Survival +8
- **Senses** passive Perception 18
- **Languages** Gith plus any four languages
- **Challenge** 9

***Spellcasting (Psionics).*** The githyanki casts one of the following spells, requiring no spell components and using Wisdom as the spellcasting ability (spell save DC 16):

**At will**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md), [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)

**1/day each**: [dominate monster](2-Mechanics/CLI/spells/dominate-monster.md), [forcecage](2-Mechanics/CLI/spells/forcecage.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

**2/day each**: [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md) (self only)

## Actions

***Multiattack.*** The githyanki makes three Staff attacks, three Telekinetic Bolt attacks, or a combination thereof.

***Staff.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage, or `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage when used with two hands, plus `dice:4d6|noform|avg|text(14)` (`4d6`) psychic damage.

***Telekinetic Bolt.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 60 ft., one target. *Hit:* `dice:3d10+4|noform|avg|text(20)` (`3d10 + 4`) force damage.

## Bonus Actions

***Astral Step (Recharge 4-6).*** The githyanki teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.
```
^statblock