---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/large
- monster/type/elemental
aliases: ["Water Totem Elemental"]
---
# Water Totem Elemental
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](2-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](2-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](2-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](2-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](2-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](2-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](2-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](2-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```ad-statblock
title: Water Totem Elemental
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Water%20Totem%20Elemental.webp#token)
*Large elemental, Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 114 (`12d10 + 48`)
- **Speed** 30 ft., swim 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|18 (+4)| 5 (-3)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** acid; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Aquan
- **Challenge** 5

## Traits

***Water Form.*** The totem elemental can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.

***Freeze.*** If the totem elemental takes cold damage, it partially freezes; its speed is reduced by 20 feet until the end of its next turn.

## Actions

***Multiattack.*** The totem elemental makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage.

***Whelm (Recharge 4-6).*** Each creature in the totem elemental's space must make a DC 15 Strength saving throw. On a failure, a target takes `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage. If it is Large or smaller, it is also [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and unable to breathe unless it can breathe water. If the saving throw is successful, the target is pushed out of the totem elemental's space.

The totem elemental can grapple one Large creature or up to two Medium or smaller creatures at one time. At the start of each of the totem elemental's turns, each target [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it takes `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage. A creature within 5 feet of the totem elemental can pull a creature or object out of it by taking an action to make a DC 14 Strength check and succeeding.
```
^statblock