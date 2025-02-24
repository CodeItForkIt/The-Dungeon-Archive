---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/5
- monster/size/huge
- monster/type/beast
aliases: ["Ammit"]
---
# Ammit
*Source: Plane Shift: Amonkhet p. 30*  

## Demons

Deep in the desert, far from the protection of the Hekma and the safety of Naktamun, lies a place called Ifnir, the Demons' Nest. The people of Amonkhet believe that the God-Pharaoh banished all the demons of this plane to the desolation of Ifnir as punishment when they rose up in rebellion against him. Some say that the angels carry the worst dissenters into the heart of Ifnir, which is a fate far worse than merely being abandoned amid the scouring sands.

The demons of Ifnir bear some resemblance to Bolas, with long limbs and tails, huge wings, and gaunt bodies adorned with horns and blades. Other demonic creatures have more bestial features, including [ammits](2-Mechanics/CLI/bestiary/beast/ammit-psa.md)—crocodilian demons sometimes used as challenges within the trials of the five gods—and the scorpion demons called [soulstingers](2-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md), whose venom causes excruciating pain in its victims.

Use the statistics of a [nalfeshnee](2-Mechanics/CLI/bestiary/fiend/nalfeshnee.md) for a demon such as an [Archfiend of Ifnir](2-Mechanics/CLI/bestiary/fiend/archfiend-of-ifnir-psa.md). The statistics of a [giant crocodile](2-Mechanics/CLI/bestiary/beast/giant-crocodile.md) can model an [ammit](2-Mechanics/CLI/bestiary/beast/ammit-psa.md), and those of a [bone devil](2-Mechanics/CLI/bestiary/fiend/bone-devil.md) work well for a [soulstinger demon](2-Mechanics/CLI/bestiary/fiend/soulstinger-demon-psa.md).

```ad-statblock
title: Ammit
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Ammit.webp#token)
*Huge beast, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 85 (`9d12 + 27`)
- **Speed** 30 ft., swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)| 9 (-1)|17 (+3)| 2 (-4)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** passive Perception 10
- **Languages** —
- **Challenge** 5

## Traits

***Hold Breath.*** The ammit can hold its breath for 30 minutes.

## Actions

***Multiattack.*** The ammit makes two attacks: one with its bite and one with its tail.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the ammit can't bite another target.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target not [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the ammit. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage. If the target is a creature, it must succeed on a DC 16 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock