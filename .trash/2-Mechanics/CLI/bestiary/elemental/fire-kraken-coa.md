---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/21
- monster/size/gargantuan
- monster/type/elemental
aliases: ["Fire Kraken"]
---
# Fire Kraken
*Source: Chains of Asmodeus p. 120*  

```ad-statblock
title: Fire Kraken
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Fire%20Kraken.webp#token)
*Gargantuan elemental, Chaotic Neutral*

- **Armor Class** 16 (natural armor)
- **Hit Points** 402 (`23d20 + 161`)
- **Speed** 30 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|11 (+0)|24 (+7)|10 (+0)|20 (+5)|15 (+2)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +7, Constitution +14
- **Skills** Athletics +15, Nature +7, Survival +12
- **Senses** blindsight 120 ft., passive Perception 15
- **Damage Immunities** fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed)
- **Languages** understands Abyssal, Celestial, Infernal, and Primordial but can't speak, telepathy 120 ft.
- **Challenge** 21

## Traits

***Freedom of Movement.*** The kraken ignores difficult terrain, and magical effects can't reduce its speed or cause it to be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). It can spend 5 feet of movement to escape from nonmagical restraints or grapples.

***Legendary Resistance (3/Day).*** If the kraken fails a saving throw, it can choose to succeed instead.

***Siege Monster.*** The kraken deals double damage to objects and structures.

## Actions

***Multiattack.*** The kraken makes two attacks using its Tentacle, Fling, or a combination of the two.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:3d6+8|noform|avg|text(18)` (`3d6 + 8`) piercing damage and `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage. If the target is a Large or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the kraken, the creature is swallowed and the grapple ends. While swallowed, a creature has the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions, has total cover against attacks and other effects outside the kraken, and takes `dice:12d6|noform|avg|text(42)` (`12d6`) fire damage at the start of the kraken's turns. If the kraken takes 50 damage or more on a single turn from a creature inside it, it must succeed on a DC 23 Constitution saving throw or regurgitate all swallowed creatures, which fall into a space within 10 feet of the kraken and now have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. If the kraken dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 15 feet of movement, exiting with the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 20 ft., one target. *Hit:* `dice:2d4+8|noform|avg|text(13)` (`2d4 + 8`) fire damage. If the target is a Huge or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 16). While [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), the target also has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition. Any target that starts its turn [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the kraken takes `dice:2d4|noform|avg|text(5)` (`2d4`) fire damage. The kraken has five tentacles, each of which can grapple one target.

***Fling.*** One Large or smaller object or creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the kraken is thrown up to 60 feet in a random direction, and now has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. If a thrown target strikes a solid surface, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at a creature, that creature must succeed on a DC 16 Dexterity saving throw or take the same damage and be knocked down with the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

## Legendary Actions

***Appendage.*** The kraken makes a Fling attack.

***Fire Breath (Costs 3 Actions).*** The kraken exhales fire in a 60-foot cone. Each creature in that area must make a DC 20 Dexterity saving throw, taking `dice:8d8|noform|avg|text(36)` (`8d8`) fire damage on a failed save, or half as much damage on a successful one.
```
^statblock