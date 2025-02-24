---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/7
- monster/size/medium
- monster/type/plant
aliases: ["Wolf-in-Sheep's-Clothing"]
---
# Wolf-in-Sheep's-Clothing
*Source: Quests from the Infinite Staircase p. 221*  

A wolf-in-sheep's-clothing is a predatory plant that resembles a tree stump. It hides in areas of thick vegetation and has a bark-like hide, eyestalks like vines or withered flowers, rootlike tentacles, and a fleshy growth atop its body that it uses to lure prey toward its fang-filled maw.

Wolves-in-sheep's-clothing can reshape their lures to mimic the appearance of various small, often adorable creatures to entice their prey. The Lure Forms table suggests some forms the lure might take.

`dice: [](wolf-in-sheeps-clothing-qftis.md#^lure-appearance)`

| dice: d6 | Lure Appearance |
|----------|-----------------|
| 1 | Clumsy puppy |
| 2 | Cute little bunnyoid |
| 3 | Dapper, smiling frog with a little top hat |
| 4 | Fluffy kitten |
| 5 | Fox with adorably large ears |
| 6 | Spunky, dancing crawfish |
^lure-appearance

```ad-statblock
title: Wolf-in-Sheep's-Clothing
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Wolf-in-Sheep%27s-Clothing.webp#token)
*Medium plant, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 20 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)| 9 (-1)|16 (+3)| 5 (-3)|12 (+1)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +7, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 17
- **Condition Immunities** [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 7

## Traits

***False Appearance.*** If the wolf-in-sheep's-clothing is motionless (except for its lure) at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the wolf-in-sheep's-clothing move or act (except for the lure), that creature must succeed on a DC 18 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the wolf-in-sheep's-clothing is animate.

## Actions

***Multiattack.*** The wolf-in-sheep's-clothing makes one Bite attack and two Root Tentacle attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage.

***Root Tentacle.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 20 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) bludgeoning damage, and if the target is a Medium or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 16). While [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way, the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, and at the start of each of the wolf-in-sheep's-clothing's turns, the wolf-in-sheep's-clothing can pull the target up to 10 feet toward itself (no action required). The wolf-in-sheep's-clothing has four root tentacles, each of which can grapple one target.

## Bonus Actions

***Completely Harmless Lure.*** The wolf-in-sheep's-clothing can change the color, texture, and shape of its lure to resemble a Tiny Beast or Tiny object. It can move the lure to reinforce the resemblance (no action required), but the lure must remain within 15 feet of the wolf-in-sheep's-clothing, connected by nearly [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) filament-like tendrils.
```
^statblock