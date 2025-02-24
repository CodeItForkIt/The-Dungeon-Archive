---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/cleric
- monster/type/humanoid/human
aliases: ["Mercion"]
---
# Mercion
*Source: The Wild Beyond the Witchlight p. 224*  

Mercion strikes the balance of a natural leader and a protective caregiver. She has a direct manner that reassures and inspires those around her.

Mercion does not worship a deity, but rather an ideal: that truth gives life to artistry and beauty, and that those who embrace deceit should be censured and punished. Light is her domain.

```ad-statblock
title: Mercion
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Mercion.webp#token)
*Medium humanoid (cleric, human), Lawful Good*

- **Armor Class** 19 ([plate armor](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 31 (`9d8 - 9`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|10 (+0)| 9 (-1)|12 (+1)|17 (+3)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +5, Charisma +5
- **Skills** Insight +5, Medicine +5
- **Senses** passive Perception 13
- **Languages** Common, Dwarvish
- **Challenge** 3

## Traits

***Special Equipment.*** Mercion wields a +1 quarterstaff.

***Spellcasting.*** Mercion casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 13):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [spare the dying](2-Mechanics/CLI/spells/spare-the-dying.md)

**1/day**: [death ward](2-Mechanics/CLI/spells/death-ward.md)

**2/day each**: [command](2-Mechanics/CLI/spells/command.md), [create food and water](2-Mechanics/CLI/spells/create-food-and-water.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [revivify](2-Mechanics/CLI/spells/revivify.md)

## Actions

***Multiattack.*** Mercion makes one Divine Radiance attack and one +1 Quarterstaff attack. She can replace one of these attacks with a use of Spellcasting.

***Divine Radiance.*** *Melee or Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:3d8|noform|avg|text(13)` (`3d8`) radiant damage.

***+1 Quarterstaff.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) bludgeoning damage, or `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) bludgeoning damage when used with two hands.

***Radiant Fire (Recharge 5-6).*** Mercion creates a magical explosion of fiery radiance centered on a point she can see within 120 feet of her. Each creature in a 20-foot-radius sphere centered on that point must make a DC 13 Dexterity saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) radiant damage on a failed save, or half as much damage on a successful one.
```
^statblock