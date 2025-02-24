---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/3
- monster/size/small
- monster/type/plant
aliases: ["Barkburr"]
---
# Barkburr
*Source: Quests from the Infinite Staircase p. 195*  

Barkburrs are animate, poisonous Plants that spontaneously grow from trees when a spark of nature's magic takes root in the wood. They appear as limpet-like knots of bark and wood indistinguishable from ordinary tree burls. Barkburrs often act in defense of a grove or forest.

Some barkburrs cling to the trees from which they sprouted, while others slowly wander until they encounter creatures that threaten the forest's natural order. When a barkburr identifies such a creature, the barkburr leaps at the invader and injects it with a poisonous sap that quickly and painfully transforms the creature into a tree.

```ad-statblock
title: Barkburr
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Barkburr.webp#token)
*Small plant, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 52 (`8d6 + 24`)
- **Speed** 10 ft., climb 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 6 (-2)|16 (+3)| 1 (-5)|15 (+2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Athletics +5
- **Senses** blindsight 60 ft. (can't see beyond this radius), passive Perception 12
- **Damage Immunities** psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** —
- **Challenge** 3

## Traits

***False Appearance.*** If the barkburr is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the barkburr move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the barkburr is animate.

***Springing Leap.*** With or without a running start, the barkburr's high jump is up to 15 feet, and its long jump is up to 30 feet. The barkburr's jumps can exceed its speed if its speed isn't 0.

## Actions

***Multiattack.*** The barkburr makes two Poison Barb attacks and uses Lignify if able.

***Poison Barb.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and the barkburr attaches to the target. While the barkburr is attached, it can't make Poison Barb attacks, and the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition as its body begins to transform into wood.

An attached barkburr can detach itself by spending 5 feet of its movement on its turn. A creature that can reach the barkburr, including the target, can use its action to detach the barkburr by making a successful DC 13 Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) check.

***Lignify.*** The barkburr targets the creature it is attached to, and the target must make a DC 13 Constitution saving throw. On a failed save, the target has the [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) condition until freed by the [Greater Restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or another effect, except it turns into a tree instead of stone. Any equipment the target is wearing or carrying is absorbed into the tree's bark.
```
^statblock