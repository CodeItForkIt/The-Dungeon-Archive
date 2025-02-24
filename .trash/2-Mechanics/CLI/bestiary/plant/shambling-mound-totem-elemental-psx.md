---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/large
- monster/type/plant
aliases: ["Shambling Mound Totem Elemental"]
---
# Shambling Mound Totem Elemental
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](2-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](2-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](2-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](2-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](2-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](2-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](2-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](2-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```ad-statblock
title: Shambling Mound Totem Elemental
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Shambling%20Mound%20Totem%20Elemental.webp#token)
*Large plant, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 20 ft., swim 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 8 (-1)|16 (+3)| 5 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Stealth +2
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 10
- **Damage Resistances** cold, fire
- **Damage Immunities** lightning
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion)
- **Languages** —
- **Challenge** 5

## Traits

***Lightning Absorption.*** Whenever the shambling mound totem is subjected to lightning damage, it takes no damage and regains a number of hit points equal to the lightning damage dealt.

## Actions

***Multiattack.*** The shambling mound totem makes two slam attacks. If both attacks hit a Medium or smaller target, the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14), and the shambling mound totem uses its Engulf on it.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage.

***Engulf.*** The shambling mound totem engulfs a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The engulfed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and unable to breathe, and it must succeed on a DC 14 Constitution saving throw at the start of each of the mound's turns or take `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage. If the mound moves, the engulfed target moves with it. The mound can have only one creature engulfed at a time.
```
^statblock