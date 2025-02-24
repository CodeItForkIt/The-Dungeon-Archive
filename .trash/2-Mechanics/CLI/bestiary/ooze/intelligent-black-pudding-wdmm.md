---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/4
- monster/size/large
- monster/type/ooze
aliases: ["Intelligent Black Pudding"]
---
# Intelligent Black Pudding
*Source: Waterdeep: Dungeon of the Mad Mage p. 244*  

```ad-statblock
title: Intelligent Black Pudding
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Intelligent%20Black%20Pudding.webp#token)
*Large ooze, Unaligned*

- **Armor Class** 7
- **Hit Points** 85 (`10d10 + 30`)
- **Speed** 20 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 5 (-3)|16 (+3)|14 (+2)| 6 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Damage Immunities** acid, cold, lightning, slashing
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Elvish and Undercommon but can't speak
- **Challenge** 4

## Traits

***Amorphous.*** The pudding can move through a space as narrow as 1 inch wide without squeezing.

***Corrosive Form.*** A creature that touches the pudding or hits it with a melee attack while within 5 feet of it takes `dice:1d8|noform|avg|text(4)` (`1d8`) acid damage. Any nonmagical weapon made of metal or wood that hits the pudding corrodes. After dealing damage, the weapon takes a permanent and cumulative −1 penalty to damage rolls. If its penalty drops to −5, the weapon is destroyed. Nonmagical ammunition made of metal or wood that hits the pudding is destroyed after dealing damage. The pudding can eat through 2-inch-thick, nonmagical wood or metal in 1 round.

***Spider Climb.*** The pudding can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Innate Spellcasting.*** The pudding's spellcasting ability is Intelligence (spell save DC 12, `dice:1d20+4|noform|text(+4)` to hit with spell attacks). It can cast the following spells, requiring no components:

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md)

**1/day**: [Melf's acid arrow](2-Mechanics/CLI/spells/melfs-acid-arrow.md)

**3/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [shield](2-Mechanics/CLI/spells/shield.md)

## Actions

***Pseudopod.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) bludgeoning damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) acid damage. In addition, nonmagical armor worn by the target is partly dissolved and takes a permanent and cumulative −1 penalty to the AC it offers. The armor is destroyed if the penalty reduces its AC to 10.

## Reactions

***Split.*** When a pudding that is Medium or larger is subjected to lightning or slashing damage, it splits into two new puddings if it has at least 10 hit points. Each new pudding has hit points equal to half the original pudding's, rounded down. New puddings are one size smaller than the original pudding.
```
^statblock