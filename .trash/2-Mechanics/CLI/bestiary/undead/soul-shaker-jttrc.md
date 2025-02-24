---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/jttrc
- monster/cr/4
- monster/size/large
- monster/type/undead
aliases: ["Soul Shaker"]
---
# Soul Shaker
*Source: Journeys through the Radiant Citadel p. 47*  

A grasping mass of Humanoid limbs, a soul shaker is an obsessive claimer of corpses and collector of body parts. These nightmarish creatures arise from ghoulish collections of severed limbs exposed to necromantic energies or when numerous crawling claws form a cooperative relationship.

Most of a soul shaker's victims have their vitality drained and their flesh pulverized by its many arms. However, should a soul shaker encounter someone with an impressionable mind, the creature attempts to charm the individual, using them as a lure to tempt others into its hunting grounds.

If defeated, a soul shaker disperses into several skittering, animate limbs. The terror can only truly be vanquished by destroying these disembodied appendages. If more than one of these pieces escape, the soul shaker reforms over the course of days and begins hunting once more.

```ad-statblock
title: Soul Shaker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/JttRC/Soul%20Shaker.webp#token)
*Large undead, typically  Chaotic Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 76 (`8d10 + 32`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)| 8 (-1)|18 (+4)| 8 (-1)|11 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 10
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** telepathy 60 ft.
- **Challenge** 4

## Traits

***Enthralled Lure (1/Day).*** The soul shaker can cast the [geas](2-Mechanics/CLI/spells/geas.md) spell, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 12).

***Reconstruction.*** When the soul shaker is reduced to 0 hit points, it explodes into `dice:1d4+5|noform|avg|text(7)` (`1d4 + 5`) crawling claws. After `dice:1d12|noform|avg|text(6)` (`1d12`) days, if at least two of those crawling claws are alive, they teleport to the location of the soul shaker's death and merge together, whereupon the soul shaker reforms and regains all its hit points.

***Unusual Nature.*** The soul shaker doesn't require air, food, drink, or sleep.

## Actions

***Crushing Grasp.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage. If the target is a Medium or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). The soul shaker can have only one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way at a time.

## Bonus Actions

***Consume Vitality.*** The soul shaker targets a creature it is grappling. If the target is not a Construct or an Undead, the target must succeed on a DC 14 Constitution saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the soul shaker regains hit points equal to that amount. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.
```
^statblock