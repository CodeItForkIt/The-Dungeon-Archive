---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/imr
- monster/cr/14
- monster/size/gargantuan
- monster/type/monstrosity/titan
aliases: ["Thessalkraken"]
---
# Thessalkraken
*Source: Infernal Machine Rebuild p. 87*  

The alchemist Thessalar created unknown numbers of misshapen magical creatures, including his many thessalbeasts. Among the largest was the thessalkraken—a slightly smaller variant of the legendary kraken, resembling that great tentacled titan but with a jagged-toothed maw that drips constantly with acid.

A thessalkraken lives in the dark depths, usually a sunken rift or a cavern filled with detritus, treasure, and the remains of sacrificial victims.

```ad-statblock
title: Thessalkraken
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IMR/Thessalkraken.webp#token)
*Gargantuan monstrosity (titan), Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 207 (`18d12 + 90`)
- **Speed** 20 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|11 (+0)|20 (+5)|19 (+4)|15 (+2)|17 (+3)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +12, Dexterity +5, Constitution +10, Intelligence +9, Wisdom +7
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 12
- **Damage Immunities** acid; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** understands Abyssal, Celestial, Infernal, and Primordial but can't speak, telepathy 120 ft.
- **Challenge** 14

## Traits

***Amphibious.*** The thessalkraken can breathe air and water.

***Freedom of Movement.*** The thessalkraken ignores difficult terrain, and magical effects can't reduce its speed or cause it to be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). It can spend 5 feet of movement to escape from nonmagical restraints or being [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

## Actions

***Multiattack.*** The thessalkraken makes one bite attack and two tentacle attacks. It can replace each tentacle attack with one use of Fling.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) piercing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) acid damage. If the target is a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the thessalkraken, that creature is swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the thessalkraken, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the thessalkraken's turns.

If the thessalkraken takes 35 damage or more on a single turn from a creature inside it, it must succeed on a DC 23 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the thessalkraken. If the thessalkraken dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 20 ft., one target. *Hit:* `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) slashing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The thessalkraken has ten tentacles, each of which can grapple one target.

***Fling.*** One Medium or smaller object held or creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the thessalkraken is thrown up to 40 feet in a random direction and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If a thrown target strikes a solid surface, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 16 Dexterity saving throw or take the same damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Acid Saliva (Recharge 5-6).*** The thessalkraken spits a glob of acid at a point it can see within 60 feet of it. Each creature within 10 feet of that point must make a DC 18 Dexterity saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) acid damage on a failed save, or half as much damage on a successful one.

## Legendary Actions

***Tentacle Attack.*** The thessalkraken makes one tentacle attack.

***Fling.*** The thessalkraken uses Fling.

***Ink Cloud (Costs 3 Actions).*** While underwater, the thessalkraken expels an ink cloud in a 60-foot radius. The cloud spreads around corners, and that area is heavily obscured to creatures other than the thessalkraken. Each creature other than the thessalkraken that ends its turn there must succeed on a DC 18 Constitution saving throw, taking `dice:3d10|noform|avg|text(16)` (`3d10`) poison damage on a failed save, or half as much damage on a successful one. A strong current disperses the cloud, which otherwise disappears at the end of the thessalkraken's next turn.

![Thessalkraken](2-Mechanics/CLI/bestiary/legendary-group/thessalkraken-imr.md)
```
^statblock