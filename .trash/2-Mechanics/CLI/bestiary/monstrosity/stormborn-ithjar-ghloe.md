---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/9
- monster/size/huge
- monster/type/monstrosity
aliases: ["Stormborn Ithjar"]
---
# Stormborn Ithjar
*Source: Grim Hollow: Lairs of Etharis p. 94*  

> [!quote]  
> 
> It takes mere moments for an ithjar to transform from a kite-like swirl of gray and red in the distance to a menace of snapping teeth.

## Salvage

Ithjar teeth and hide can fetch a fair price in larger markets. Necklaces and other decorations can be made from the teeth, and clothing can be fashioned from the skin and scales. Popular superstition says wearing ithjar teeth or hide imparts some of the creature's nimbleness to the wearer. This belief isn't wholly true, but someone who has proficiency with leatherworker's tools can make hide armor from the hide that has a base AC of 13 and allows a wearer to apply their full Dexterity bonus to AC. Creating this armor takes 10 days. Such hide armor fashioned from a stormborn ithjar is armor of resistance (lightning and thunder). This armor takes no longer to make, but it requires other materials worth 2,000 gp

The central fang of a stormborn ithjar can be fashioned into a javelin of lightning that deals `dice:2d8|noform|avg` (`2d8`) lightning damage and `dice:2d8|noform|avg` (`2d8`) thunder damage instead of only `dice:4d6|noform|avg` (`4d6`) lightning damage. A creature hit by the javelin must also succeed on a DC 13 Strength saving throw or fall prone. Someone who has proficiency with smith's tools can make this weapon with 10 days of work and other materials worth 250 gp. Somebody must also cast thunderwave on the weapon three times during its creation.

## Lore

- **DC 10 Intelligence ([Nature](2-Mechanics/CLI/rules/skills.md#Nature)).** Ithjars are fast-moving ferocious fliers, but the more powerful of these flying serpents are imbued with the power of storms and can exhale lightning and thunder.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** It's difficult to capture an ithjar. They slither out of an enemy's clutches and other restraints quickly and easily.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The stormborn ithjar is immune to lightning and thunder, allowing it to travel within storm clouds.  

## Statblock

```ad-statblock
title: Stormborn Ithjar
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Stormborn%20Ithjar.webp#token)
*Huge monstrosity, Chaotic Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 189 (`18d12 + 72`)
- **Speed** 40 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|20 (+5)|19 (+4)| 3 (-4)|12 (+1)| 5 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Acrobatics +9, Perception +5
- **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 15
- **Damage Immunities** lightning, thunder
- **Languages** —
- **Challenge** 9

## Traits

***Keen Sight.*** The stormborn ithjar has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Slippery Serpent.*** The stormborn ithjar has advantage on ability checks or saving throws made to escape a grapple and saving throws to avoid being [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained).

## Actions

***Multiattack.*** The stormborn ithjar attacks once with its bite and once with its tail.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 15 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) slashing damage and `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 15 ft., one target. *Hit:* `dice:3d8+5|noform|avg|text(18)` (`3d8 + 5`) bludgeoning damage and `dice:2d6|noform|avg|text(7)` (`2d6`) thunder damage. If the target is a Large or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the stormborn ithjar can't use its tail on another target.

***Storm Breath (Recharge 5-6).*** The stormborn ithjar exhales a 30-foot cone of lightning and thunder. Each creature in that area must make a DC 16 Dexterity saving throw. On a failure, a creature takes `dice:7d8|noform|avg|text(31)` (`7d8`) lightning damage and `dice:7d8|noform|avg|text(31)` (`7d8`) thunder damage and falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the save succeeds, the creature takes half the lightning and thunder damage and doesn't fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone). The discharge of this breath weapon is audible for 1 mile outside and 300 feet inside.
```
^statblock