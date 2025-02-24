---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/10
- monster/environment/planar
- monster/size/medium
- monster/type/celestial
aliases: ["Planewatcher"]
---
# Planewatcher
*Source: Tome of Beasts 1 (2023 Edition) p. 293*  

*The brilliant lasso tightened around the eldritch monster as the faceless winged creature dragged it across a hellish landscape.*

A planewatcher is sworn to protect the order of the boundaries between worlds. These angelic creatures fearlessly track down people and monsters who cross the boundaries of the planes and drag them back to where they came from, willingly or otherwise. Each planewatcher is bound to a single plane of existence.

## Friend or Foe

Planewatchers are dedicated to their purpose, regardless of morality. Heroes may find themselves beseeching a planewatcher for help to battle an interplanar foe, or find themselves fighting one while on a planar mission. Planewatchers track down trespassers based on the perceived threat to the multiverse.

## Unlikely Allies

Star drakes protect the Material Plane in much the same way planewatchers protect their respective planes. Because of this, the Material Plane has fewer planewatchers than other planes, and the two beings can work in concert to maintain the natural order of the multiverse.

## Statblock

```ad-statblock
title: Planewatcher
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Planewatcher.webp#token)
*Medium celestial, Lawful Neutral*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 136 (`16d8 + 64`)
- **Speed** 30 ft., climb 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|17 (+3)|18 (+4)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +8, Charisma +9
- **Skills** Athletics +8, Insight +8, Perception +8, Survival +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 10

## Traits

***Magic Resistance.*** The planewatcher has advantage on saving throws against spells and other magical effects.

***Planar Sense.*** The planewatcher can pinpoint the location of creatures not native to the plane the planewatcher currently occupies and planar portals within 60 feet of it, and the planewatcher can sense the general direction of such creatures and portals within 1 mile of it.

***Plane Bound.*** The planewatcher is immune to any spell or effect that would force it to leave its current plane, unless it wants to leave.

***Word-Bound.*** The planewatcher always knows the direction and distance to any creature that dispels, breaks, or otherwise avoids the geas of the promise it made via Planar Ultimatum, provided the planewatcher and the creature are on the same plane of existence. While grappling such a creature, it can cast the [banishment](2-Mechanics/CLI/spells/banishment.md) spell as a bonus action (spell save DC 17) on that creature.

## Actions

***Multiattack.*** The planewatcher makes one Radiant Lasso attack and two Enervating Blast attacks, or it makes three Enervating Blast attacks. It can replace two attacks with a use of Planar Ultimatum.

***Radiant Lasso.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 30 ft., one target. *Hit:* `dice:4d6+4|noform|avg|text(22)` (`4d6 + 4`) radiant damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16) if the planewatcher isn't already grappling a creature. Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), can't tell a lie, and can't teleport or be transported to another plane of existence unless the planewatcher wills it.

***Enervating Blast.*** *Melee or Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 60 ft., one target. *Hit:* `dice:4d8+5|noform|avg|text(23)` (`4d8 + 5`) force damage, and the target has disadvantage on Strength and Dexterity checks until the end of its next turn.

***Planar Ultimatum.*** The planewatcher demands one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it to return to the creature's home plane within 24 hours. If the creature doesn't swear to do so, it must make a DC 17 Constitution saving throw, taking `dice:10d8|noform|avg|text(45)` (`10d8`) radiant damage on a failed save, or half as much damage on a successful one If the creature swears to return, it becomes affected by the [geas](2-Mechanics/CLI/spells/geas.md) spell for 30 days, which compels the creature to return to its home plane as soon as possible.

## Bonus Actions

***Reel.*** The planewatcher pulls a creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it up to 25 feet straight toward it.
```
^statblock

## Environment

planar