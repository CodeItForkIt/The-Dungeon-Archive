---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/forest
- monster/size/medium
- monster/type/fey
aliases: ["Duskthorn Dryad"]
---
# Duskthorn Dryad
*Source: Tome of Beasts 1 (2023 Edition) p. 150*  

*This striking woman with obvious fey features and skin the color of slate sits in the shade of an ancient, vine-wrapped tree. Clothed in vines and leaves, she is almost indistinguishable from the tree.*

## Creeper Vine Spirits

Duskthorn dryads are spirits tied to thorn-bearing creeper vines. They seek out dead trees as homes for their vines. They can travel through trees to escape their foes but must stay near their vines.

## Grove Guardians

Duskthorn dryads use their vines and the plants in their glades to defend themselves. They often call on the aid of forest animals and children of the briar. Occasionally, a circle of duskthorn dryads work together to call on the aid of an enormously strong vine troll skeleton to protect their grove.

> [!note] Duskthorn Dryads in Midgard
> 
> These dryads are commonly found near the ruins of Thorn, in the Arbonesse Forest, and in the Shadow Realms. They are close friends to the darker fey and are thought by some to be created from ordinary dryads drawn into the corruption of the Shadow Realm. Certainly, their mastery of the shadowy Umbral language shows their close ties to this darker world.
^duskthorn-dryads-in-midgard

## Statblock

```ad-statblock
title: Duskthorn Dryad
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Duskthorn%20Dryad.webp#token)
*Medium fey, Chaotic Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 77 (`14d8 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|20 (+5)|13 (+1)|14 (+2)|15 (+2)|24 (+7)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +3, Wisdom +4
- **Skills** Animal Handling +4, Deception +9, Nature +6, Perception +4, Persuasion +9, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Common, Elvish, Sylvan, Umbral
- **Challenge** 3

## Traits

***Magic Resistance.*** The dryad has advantage on saving throws against spells and other magical effects.

***Speak with Beasts and Plants.*** The dryad can communicate with beasts and plants as if they shared a language.

***Tree Stride.*** Once on her turn, the dryad can use 10 feet of her movement to step magically into one dead tree within her reach and emerge from a second dead tree within 60 feet of the first tree, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be Large or bigger.

***Spellcasting.*** The dryad casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [druidcraft](2-Mechanics/CLI/spells/druidcraft.md)

**1/day each**: [barkskin](2-Mechanics/CLI/spells/barkskin.md), [spike growth](2-Mechanics/CLI/spells/spike-growth.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**3/day each**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [entangle](2-Mechanics/CLI/spells/entangle.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md)

## Actions

***Multiattack.*** The duskthorn dryad makes two Thorned Slam or Thorn attacks.

***Thorned Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage.

***Thorn.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 80/320 ft., one target. *Hit:* `dice:2d4+5|noform|avg|text(10)` (`2d4 + 5`) piercing damage.

***Children of the Forest (1/Day).*** The dryad magically calls `dice:1d4|noform|avg` (`1d4`) boars, constrictor snakes, or wolves, or it calls 1 child of the briar. The called creatures arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of the dryad and obeying her spoken commands. The creatures remain for 1 hour, until the dryad dies, or until the dryad dismisses them as a bonus action.
```
^statblock

## Environment

forest