---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/7
- monster/size/large
- monster/type/construct
aliases: ["Construct (Shield Guardian)"]
---
# Construct (Shield Guardian)
*Source: Plane Shift: Kaladesh p. 32*  

The term "construct" encompasses a tremendous variety of artifact creatures. Some are automatons designed for battle—most often to fight each other in arenas, but also in real combat. Many of these battle constructs specialize in defense, sometimes carrying shields to protect their creators, or simply escorting their charges like a watchdog.

Many constructs are intended for use in foundries and workshops, assisting inventors or performing repetitive tasks. Such a construct might find and deliver a specific tool its inventor requests, or perform routine maintenance in parts of a foundry that are difficult or dangerous to reach.

Other constructs have been designed to carry messages or packages, to load and unload goods from barges and airships, to trawl the sewers for salvageable materials, and even—during the height of the Aether Revolt—to scan crowds of people for known renegades and fugitives, recognizing their facial features.

Almost any creature in the "Monster Manual" with the construct type could be used as a construct on Kaladesh, including [animated armor](2-Mechanics/CLI/bestiary/construct/animated-armor.md), [helmed horrors](2-Mechanics/CLI/bestiary/construct/helmed-horror.md), [shield guardians](2-Mechanics/CLI/bestiary/construct/shield-guardian.md), and [modrons](2-Mechanics/CLI/bestiary/construct/monodrone.md).

## Artifact Creatures

Many of the products of Kaladesh's most inventive minds are tools meant to be wielded, piloted, or otherwise employed by other people. But the crowning achievement of the artificer's art is the imitation of life itself, crafting artificial creatures with the capability to move, act, and even make decisions independently, according to a comprehensive set of instructions.

Ghirapur is full of such artifact creatures—courier devices dashing through the streets of Bomat, thopters flitting from aerie to aerie, and assembly workers crafting more artifacts in busy foundries. These creatures are as diverse in their forms and appearance as they are in their purposes, but they can be broadly grouped into four categories: constructs, servos, thopters, and lifecraft creatures.

## Statblock

```ad-statblock
title: Construct (Shield Guardian)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Construct%20%28Shield%20Guardian%29.webp#token)
*Large construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 142 (`15d10 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 8 (-1)|18 (+4)| 7 (-2)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands commands given in any language but can't speak
- **Challenge** 7

## Traits

***Bound.*** The construct is magically bound to an amulet. As long as the construct and its amulet are on the same plane of existence, the amulet's wearer can telepathically call the construct to travel to it, and the construct knows the distance and direction to the amulet. If the construct is within 60 feet of the amulet's wearer, half of any damage the wearer takes (rounded up) is transferred to the construct.

***Regeneration.*** The construct regains 10 hit points at the start of its turn if it has at least 1 hit point.

***Spell Storing.*** A spellcaster who wears the construct's amulet can cause the construct to store one spell of 4th level or lower. To do so, the wearer must cast the spell on the construct. The spell has no effect but is stored within the construct. When commanded to do so by the wearer or when a situation arises that was predefined by the spellcaster, the construct casts the stored spell with any parameters set by the original caster, requiring no components. When the spell is cast or a new spell is stored, any previously stored spell is lost.

## Actions

***Multiattack.*** The construct makes two fist attacks.

***Fist.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) bludgeoning damage.

## Reactions

***Shield.*** When a creature makes an attack against the wearer of the construct's amulet, the construct grants a +2 bonus to the wearer's AC if the construct is within 5 feet of the wearer.
```
^statblock