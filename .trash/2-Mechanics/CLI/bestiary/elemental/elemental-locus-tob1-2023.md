---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/17
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/gargantuan
- monster/type/elemental
aliases: ["Elemental Locus"]
---
# Elemental Locus
*Source: Tome of Beasts 1 (2023 Edition) p. 157*  

*The ground ripples and tears as rocks fall, jets of flame erupt, and howling winds rage around a rocky creature.*

## Spirit of the Land

Elemental loci are living spirits inhabiting or embodying tracts of land and geographical features. They are the ultimate personification of nature—the land itself come to life. They vary in size from small hills to entire ridge lines, with no discernible pattern to where they take root.

## Stubborn Nature

Elemental loci are fiercely protective of their chosen location. They tolerate no interference in the natural order and challenge all who despoil the land, be they mortal, monster, or god.

> [!note] Elemental Loci in Midgard
> 
> Among the Tamasheq, the elemental loci are cherished as minor deities, nearly as powerful as the Wind Lords themselves. The sorcerers of Kush have tried to capture and enslave loci for decades; thus far without success, but they grow bolder (and closer to their goal) with each attempt.
^elemental-loci-in-midgard

## Statblock

```ad-statblock
title: Elemental Locus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Elemental%20Locus.webp#token)
*Gargantuan elemental, Neutral*

- **Armor Class** 16 (natural armor)
- **Hit Points** 290 (`20d20 + 80`)
- **Speed** 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)| 1 (-5)|18 (+4)|10 (+0)|11 (+0)|11 (+0)|

- **Proficiency Bonus** +6
- **Saving Throws** Intelligence +6, Wisdom +6, Charisma +6
- **Skills** Nature +6, Perception +6
- **Senses** darkvision 120 ft., tremorsense 120 ft., passive Perception 16
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** acid; cold; fire; lightning; poison; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Primordial
- **Challenge** 17

## Traits

***Elemental Nature.*** The elemental locus doesn't require air, food, drink, or sleep.

***Immortal.*** If the elemental locus dies, it returns to life in `dice:1d12|noform|avg` (`1d12`) months, regaining all its hp and becoming active again. The new body appears in a space of the locus's choice within its bound land. Only a [wish](2-Mechanics/CLI/spells/wish.md) spell can prevent this trait from functioning.

***Land Bound.*** The elemental locus is bound to an area of land or ocean no larger than 100 square miles. If it leaves this region, it loses its Spawn Elemental action. If it remains outside the region, it automatically teleports back to the center of this area after 24 hours, regardless of distance.

***Magic Resistance.*** The elemental locus has advantage on saving throws against spells and other magical effects.

***Siege Monster.*** The elemental locus deals double damage to objects and structures.

***Unstoppable.*** Moving through difficult terrain doesn't cost the elemental locus extra movement, and its speed can't be reduced.

## Actions

***Multiattack.*** The elemental locus makes three Slam attacks. It can replace one attack with a use of Spawn Elemental.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 15 ft., one target. *Hit:* `dice:5d8+9|noform|avg|text(31)` (`5d8 + 9`) bludgeoning damage. If the target is a creature, it must succeed on a DC 18 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Spawn Elemental.*** The elemental locus magically creates up to `dice:2d6|noform|avg` (`2d6`) mephits or 1 Elemental with a challenge rating of 5 or lower. The Elementals arrive at the start of the locus's next turn, acting as allies of the locus and obeying its spoken commands. The locus can create only Elementals that share an element with a terrain feature comprising at least 100,000 square feet of the locus's bound land. For example, a desert-bound locus can't create a water-based Elemental, unless its bound desert contains an oasis or other source of water around the size of a small pond. The Elementals remain for 1 hour, until the locus dies, or until the locus dismisses them as a bonus action. The locus can have any number of Elementals under its control at one time, provided the combined total CR of the Elementals is no higher than 8.
```
^statblock

## Environment

forest, grassland, hill, mountain