---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/6
- monster/size/medium
- monster/type/construct
aliases: ["Istarian Drone"]
---
# Istarian Drone
*Source: Dragonlance: Shadow of the Dragon Queen p. 202*  

Istarian drones are ancient Constructs made of marble and gleaming metal inlaid with crystals that flash with sparks of electricity. Created to build the fantastic structures that once marked the glory of Istar, these drones resemble short, stout mantises. They have four scuttling insectile legs and barbed, scythe-shaped arms for carrying and placing building materials. The drones create a viscous gel that hardens into crystalline mortar, which they can repurpose to restrain attackers.

```ad-statblock
title: Istarian Drone
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Istarian%20Drone.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 127 (`15d8 + 60`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|18 (+4)| 4 (-3)|10 (+0)| 4 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 10
- **Damage Immunities** lightning, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages spoken by its creator but can't speak
- **Challenge** 6

## Traits

***Spider Climb.*** The drone can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Unusual Nature.*** The drone doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The drone makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) lightning damage. If the target is a Medium or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). The drone has two claws, each of which can grapple only one target.

***Crystalline Spit (Recharge 5-6).*** The drone spits crackling gel in a line 5 feet wide and 20 feet long. Each creature in the line must make a DC 15 Dexterity saving throw. On a failed save, the creature takes `dice:4d6|noform|avg|text(14)` (`4d6`) lightning damage and is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the gel, which hardens into crystal. The creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the crystal is destroyed. The crystal has AC 15, 15 hit points, immunity to poison and psychic damage, and vulnerability to thunder damage. On a successful save, the creature takes half as much damage and isn't [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained).
```
^statblock