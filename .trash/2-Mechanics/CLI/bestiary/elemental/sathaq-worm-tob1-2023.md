---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/10
- monster/environment/desert
- monster/environment/hill
- monster/environment/mountain
- monster/environment/underdark
- monster/size/huge
- monster/type/elemental
aliases: ["Sathaq Worm"]
---
# Sathaq Worm
*Source: Tome of Beasts 1 (2023 Edition) p. 317*  

*This titanic worm's rocky hide is rough and hard as stone. Its yawning gullet writhes with miniature worms like itself.*

## Elemental Predators

Sathaq worms are nightmarish predators from the Plane of Elemental Earth with rugged brown hide embedded with stones. They devour stone and flesh with equal ease.

## Guts Filled with Larvae

Sathaq worms are solitary; they approach each other only to mate. Their young incubate inside the worms' gullets. Creatures they swallow are simultaneously digested by the parent worm and devoured by the larvae.

## Painful Presence

Ultrasonic noise and magical ripples that tear at flesh and bone make the very presence of a sathaq worm extremely uncomfortable for creatures of the Material Plane.

## Statblock

```ad-statblock
title: Sathaq Worm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Sathaq%20Worm.webp#token)
*Huge elemental, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 149 (`13d12 + 65`)
- **Speed** 20 ft., burrow 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)| 6 (-2)|20 (+5)| 5 (-3)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +5, Stealth +2
- **Senses** tremorsense 60 ft., passive Perception 15
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Deep Speech and Terran but can't speak
- **Challenge** 10

## Traits

***Agonizing Aura.*** The sathaq worm emits ultrasonic noise and minor vibrations that cause pain and subtly disrupt the functions of most creatures. A creature that starts its turn within 15 feet of the sathaq worm must succeed on a DC 17 Constitution saving throw or have disadvantage on attack rolls until the start of its next turn. Creatures with resistance or immunity to thunder damage automatically succeed on the saving throw.

***Earth Glide.*** The sathaq worm can burrow through nonmagical, unworked earth and stone. While doing so, the worm doesn't disturb the material it moves through.

***Earthen Camouflage.*** The sathaq worm has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in sandy, muddy, or rocky terrain.

***Siege Monster.*** The sathaq worm deals double damage to objects and structures.

## Actions

***Multiattack.*** The sathaq worm makes one Bite attack and two Slam attacks, or it makes three Slam attacks. It can replace its Bite attack with a use of Swallow.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+6|noform|avg|text(24)` (`4d8 + 6`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the sathaq worm can't Bite another target.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) bludgeoning damage.

***Swallow.*** The sathaq worm makes one Bite attack against a Large or smaller creature it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the worm (including the worm's Agonizing Aura), and takes `dice:3d6|noform|avg|text(10)` (`3d6`) piercing damage and `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage at the start of each of the sathaq worm's turns. The sathaq worm can have only one creature swallowed at a time.

If the sathaq worm takes 30 damage or more on a single turn from the swallowed creature, the sathaq worm must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 5 feet of the sathaq worm. If the sathaq worm dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

desert, hill, mountain, underdark