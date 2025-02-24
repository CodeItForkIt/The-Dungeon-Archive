---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/5
- monster/size/large
- monster/type/elemental
aliases: ["Fire Guardian"]
---
# Fire Guardian
*Source: Plane Shift: Ixalan p. 38*  

Elementals are an even more primal embodiment of natural forces. They are living beings of raw natural energy, but magic can shape and bind them into physical forms composed of wind, water, fire, or the verdant growth of the forest. The River Heralds construct jade totems that hold elementals in stasis until activated by trespassers. When a totem opens, the elemental's physical form comes together, and the intruders are quickly dispatched.

River Heralds also make use of elementals formed of air, water, or vegetation. In ancient times when folk of the River Heralds and the Sun Empire worked together, they harnessed fire elementals into guardians that still keep watch over certain forgotten ruins.

Any of the various elemental and plant creatures in the "Monster Manual" can represent the elementals of Ixalan. The River Heralds' totem elementals are similar to the basic [air](2-Mechanics/CLI/bestiary/elemental/air-elemental.md), [earth](2-Mechanics/CLI/bestiary/elemental/earth-elemental.md), and [water elementals](2-Mechanics/CLI/bestiary/elemental/water-elemental.md), or to [treants](2-Mechanics/CLI/bestiary/plant/treant.md), blights, [shambling mounds](2-Mechanics/CLI/bestiary/plant/shambling-mound.md), or [awakened trees](2-Mechanics/CLI/bestiary/plant/awakened-tree.md) and [awakened shrubs](2-Mechanics/CLI/bestiary/plant/awakened-shrub.md). Fire guardians are similar to [fire elementals](2-Mechanics/CLI/bestiary/elemental/fire-elemental.md).

```ad-statblock
title: Fire Guardian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Fire%20Guardian.webp#token)
*Large elemental, Neutral*

- **Armor Class** 13
- **Hit Points** 102 (`12d10 + 36`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|17 (+3)|16 (+3)| 6 (-2)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Ignan
- **Challenge** 5

## Traits

***Fire Form.*** The fire guardian can move through a space as narrow as 1 inch wide without squeezing. A creature that touches the fire guardian or hits it with a melee attack while within 5 feet of it takes `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage. In addition, the fire guardian can enter a hostile creature's space and stop there. The first time it enters a creature's space on a turn, that creature takes `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage and catches fire; until someone takes an action to douse the fire, the creature takes `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage at the start of each of its turns.

***Illumination.*** The fire guardian sheds bright light in a 30-foot radius and dim light in an additional 30 feet.

***Water Susceptibility.*** For every 5 feet the fire guardian moves in water, or for every gallon of water splashed on it, it takes 1 cold damage.

## Actions

***Multiattack.*** The fire guardian makes two touch attacks.

***Touch.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) fire damage. If the target is a creature or a flammable object, it ignites. Until a creature takes an action to douse the fire, the target takes `dice:1d10|noform|avg|text(5)` (`1d10`) fire damage at the start of each of its turns.
```
^statblock