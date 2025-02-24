---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/sahuagin
aliases: ["Sahuagin Warlock of Uk'otoa (Rod of Retribution)"]
---
# Sahuagin Warlock of Uk'otoa (Rod of Retribution)
*Source: Explorer's Guide to Wildemount p. 297*  

```ad-statblock
title: Sahuagin Warlock of Uk'otoa (Rod of Retribution)
*Medium humanoid (sahuagin), Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 22 (`5d8`)
- **Speed** 30 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|10 (+0)|11 (+0)| 8 (-1)| 8 (-1)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Arcana +1, Persuasion +5
- **Senses** darkvision 120 ft., passive Perception 9
- **Languages** Common, Sahuagin
- **Challenge** 3

## Traits

***Blood Frenzy.*** The warlock has advantage on melee attack rolls against any creature that doesn't have all its hit points.

***Limited Amphibiousness.*** The warlock can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.

***Shark Telepathy.*** The warlock can magically command any shark within 120 feet of it, using a limited telepathy.

***Special Equipment.*** The warlock carries a [rod of retribution](2-Mechanics/CLI/items/rod-of-retribution-egw.md).

***Innate Spellcasting.*** The warlock's innate spellcasting ability is Charisma (spell save DC 13, `dice:1d20+5|noform|text(+5)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will**: [eldritch blast](2-Mechanics/CLI/spells/eldritch-blast.md) (see "Actions" below), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day each**: [armor of Agathys](2-Mechanics/CLI/spells/armor-of-agathys.md), [arms of Hadar](2-Mechanics/CLI/spells/arms-of-hadar.md), [counterspell](2-Mechanics/CLI/spells/counterspell.md), [crown of madness](2-Mechanics/CLI/spells/crown-of-madness.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [hunger of Hadar](2-Mechanics/CLI/spells/hunger-of-hadar.md)

## Actions

***Multiattack.*** The warlock makes two attacks: one with its bite and one with its Sword of Fathoms.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage.

***Sword of Fathoms.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) slashing damage, and if the target is a creature, it must succeed on a DC 13 Constitution saving throw or begin choking. The choking creature is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) until the end of its next turn, when the effect ends on it.

***Eldritch Blast (Cantrip).*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 120 ft., one creature. *Hit:* `dice:1d10|noform|avg|text(5)` (`1d10`) force damage.

## Reactions

***Retribution (3/Day).*** When a creature the warlock can see within 60 feet of it damages the warlock, the creature must make a DC 13 Dexterity saving throw, taking `dice:2d10|noform|avg|text(11)` (`2d10`) lightning damage on a failed save, or half as much damage on a successful one.
```
^statblock