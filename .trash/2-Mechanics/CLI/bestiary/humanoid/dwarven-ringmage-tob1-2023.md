---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/arctic
- monster/environment/urban
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Dwarven Ringmage"]
---
# Dwarven Ringmage
*Source: Tome of Beasts 1 (2023 Edition) p. 409*  

Curves are seldom seen in the stacked blocks and precise geometric forms of dwarven architecture. Devoid of angles and planes with no beginning and no end, circles are a mystery and hold power. Dwarven ringmages are those dwarves who have mastered the art of tapping into that power, imbuing it into metal rings and their spellcasting. Rings and circles are sacred to them, and they read omens in the cycle of seasons, the shape of flowers, and in a storm's first rain drops.

```ad-statblock
title: Dwarven Ringmage
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dwarven%20Ringmage.webp#token)
*Medium humanoid (dwarf), Any alignment*

- **Armor Class** 16 ([breastplate](2-Mechanics/CLI/items/breastplate.md))
- **Hit Points** 136 (`21d8 + 42`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|15 (+2)|18 (+4)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5, Intelligence +7, Wisdom +4
- **Skills** Arcana +7, History +7
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** poison
- **Languages** Common, Dwarvish
- **Challenge** 7

## Traits

***Dwarven Resilience.*** The dwarven ringmage has advantage on saving throws against poison.

***Spellcasting.*** The dwarven ringmage casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: [color spray](2-Mechanics/CLI/spells/color-spray.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [true strike](2-Mechanics/CLI/spells/true-strike.md)

**1/day each**: [greater invisibility](2-Mechanics/CLI/spells/greater-invisibility.md), [wall of stone](2-Mechanics/CLI/spells/wall-of-stone.md)

**3/day each**: [expeditious retreat](2-Mechanics/CLI/spells/expeditious-retreat.md), [fly](2-Mechanics/CLI/spells/fly.md), [haste](2-Mechanics/CLI/spells/haste.md)

## Actions

***Multiattack.*** The dwarven ringmage can use its Ring Magic. It then makes three Ring Staff attacks. It can replace one attack with a use of Spellcasting.

***Ring Staff.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) acid, cold, fire, lightning, or thunder damage (the ringmage's choice).

***Ring Magic.*** The dwarven ringmage draws circles of magic in the air and sends them toward one creature it can see within 30 feet of it, causing one of the following effects:

- **Rings of Binding.** The target must succeed on a DC 15 Strength saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by magical rings until the end of its next turn.  
- **Rings of Bravery.** The target can't be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) and has advantage on melee weapon attack rolls until the end of its next turn.  
- **Rings of Protection.** The target has a +2 bonus to its Armor Class until the end of its next turn.  
- **Rings of Retribution.** When any creature hits the target before the start of the ringmage's next turn, the creature takes `dice:1d8|noform|avg|text(4)` (`1d8`) acid, cold, fire, lightning, or thunder damage (the ringmage's choice).  
```
^statblock

## Environment

arctic, urban