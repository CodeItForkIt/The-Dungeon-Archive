---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/23
- monster/size/gargantuan
- monster/type/monstrosity/titan
aliases: ["Kozilek"]
---
# Kozilek
*Source: Plane Shift: Zendikar p. 38*  

```ad-statblock
title: Kozilek
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Kozilek.webp#token)
*Gargantuan monstrosity (titan), Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 472 (`27d20 + 189`)
- **Speed** 20 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)|11 (+0)|25 (+7)|22 (+6)|18 (+4)|20 (+5)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +17, Dexterity +7, Constitution +14, Intelligence +13, Wisdom +11
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 14
- **Damage Immunities** lightning; bludgeoning, piercing, slashing from nonmagical attacks; psychic
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** Abyssal, Celestial, Infernal, Primordial, telepathy 120 ft. but can't speak
- **Challenge** 23

## Traits

***Amphibious.*** Kozilek can breathe air and water.

***Freedom of Movement.*** Kozilek ignores difficult terrain, and magical effects can't reduce its speed or cause it to be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). It can spend 5 feet of movement to escape from nonmagical restraints or being [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

***Siege Monster.*** Kozilek deals double damage to objects and structures.

## Actions

***Multiattack.*** Kozilek makes three tentacle attacks, each of which it can replace with one use of Fling.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+10|noform|avg|text(23)` (`3d8 + 10`) piercing damage. If the target is a Large or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Kozilek, that creature is swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside Kozilek, and it takes `dice:12d6|noform|avg|text(42)` (`12d6`) acid damage at the start of each of Kozilek's turns. If Kozilek takes 50 damage or more on a single turn from a creature inside it, Kozilek must succeed on a DC 25 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of Kozilek. If Kozilek dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+17|noform|text(+17)` to hit, reach 30 ft., one target. *Hit:* `dice:3d6+10|noform|avg|text(20)` (`3d6 + 10`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 18). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). Kozilek has ten tentacles, each of which can grapple one target.

***Fling.*** One Large or smaller object held or creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Kozilek is thrown up to 60 feet in a random direction and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If a thrown target strikes a solid surface, the target takes `dice:1d6|noform|avg|text(3)` (`1d6`) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 18 Dexterity saving throw or take the same damage and be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Lightning Storm.*** Kozilek magically creates three bolts of lightning, each of which can strike a target Kozilek can see within 120 feet of it. A target must make a DC 23 Dexterity saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) lightning damage on a failed save, or half as much damage on a successful one.

## Legendary Actions

***Tentacle Attack or Fling.*** Kozilek makes one tentacle attack or uses its Fling.

***Lightning Storm (Costs 2 Actions).*** Kozilek uses Lightning Storm.

***Ink Cloud (Costs 3 Actions).*** While underwater, Kozilek expels an ink cloud in a 60-foot radius. The cloud spreads around corners, and that area is heavily obscured to creatures other than Kozilek. Each creature other than Kozilek that ends its turn there must succeed on a DC 23 Constitution saving throw, taking `dice:3d10|noform|avg|text(16)` (`3d10`) poison damage on a failed save, or half as much damage on a successful one. A strong current disperses the cloud, which otherwise disappears at the end of Kozilek's next turn.
```
^statblock