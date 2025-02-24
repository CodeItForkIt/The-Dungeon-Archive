---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/1
- monster/size/medium
- monster/type/fey
aliases: ["Dryad"]
---
# Dryad
*Source: Plane Shift: Ixalan p. 38*  

It is said that the only force on Ixalan not interested in finding the golden city is Ixalan itself. Dryads, as incarnations of the land and its will, prove the saying true. Their only concern is the health of the forest: when the trees and ferns are healthy, the dryads flourish. But when the vampires' dusk fog or a demon's unwholesome influence cause the jungle to wither, the dryads suffer. As a result, they are generally friendly with the River Heralds, who live in harmony with nature, and hostile to the Legion of Dusk.

The dryads otherwise have no stake in the conflict between the people of Ixalan and the invaders, but as creatures of life and growth, they hate to see any living being suffer. Thus, they have been known to tend to wounded people left in the jungle to die, sharing their own abundant life energy with those in their care.

Ixalan's dryads are identical to the [dryads](2-Mechanics/CLI/bestiary/fey/dryad.md) in the "Monster Manual".

```ad-statblock
title: Dryad
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Dryad.webp#token)
*Medium fey, Neutral*

- **Armor Class** 11 (16 with [barkskin](2-Mechanics/CLI/spells/barkskin.md))
- **Hit Points** 22 (`5d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|12 (+1)|11 (+0)|14 (+2)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Elvish, Sylvan
- **Challenge** 1

## Traits

***Magic Resistance.*** The dryad has advantage on saving throws against spells and other magical effects.

***Speak with Beasts and Plants.*** The dryad can communicate with beasts and plants as if they shared a language.

***Tree Stride.*** Once on her turn, the dryad can use 10 feet of her movement to step magically into one living tree within her reach and emerge from a second living tree within 60 feet of the first tree, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be large or bigger.

***Innate Spellcasting.*** The dryad's innate spellcasting ability is Charisma (spell save DC 14). The dryad can innately cast the following spells, requiring no material components:

**At will**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md)

**1/day each**: [barkskin](2-Mechanics/CLI/spells/barkskin.md), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md), [shillelagh](2-Mechanics/CLI/spells/shillelagh.md)

**3/day each**: [entangle](2-Mechanics/CLI/spells/entangle.md), [goodberry](2-Mechanics/CLI/spells/goodberry.md)

## Actions

***Club.*** *Melee Weapon Attack:* `dice:1d20+2|noform|text(+2)` to hit (`dice:1d20+6|noform|text(+6)` to hit with shillelagh), reach 5 ft., one target. *Hit:* `dice:1d4|noform|avg|text(2)` (`1d4`) bludgeoning damage, or `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage with shillelagh.

***Fey Charm.*** The dryad targets one humanoid or beast that she can see within 30 feet of her. If the target can see the dryad, it must succeed on a DC 14 Wisdom saving throw or be magically [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed). The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) creature regards the dryad as a trusted friend to be heeded and protected. Although the target isn't under the dryad's control, it takes the dryad's requests or actions in the most favorable way it can.

Each time the dryad or its allies do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until the dryad dies, is on a different plane of existence from the target, or ends the effect as a bonus action. If a target's saving throw is successful, the target is immune to the dryad's Fey Charm for the next 24 hours.

The dryad can have no more than one humanoid and up to three beasts [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) at a time.
```
^statblock