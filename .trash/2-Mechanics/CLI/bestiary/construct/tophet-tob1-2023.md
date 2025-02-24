---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/8
- monster/environment/urban
- monster/size/huge
- monster/type/construct
aliases: ["Tophet"]
---
# Tophet
*Source: Tome of Beasts 1 (2023 Edition) p. 364*  

*An enormous bronze and iron statue filled with fire towers above the ring of chanting, frenzied worshipers.*

Worshipers of fire gods use tophets to incinerate sacrifices in their flaming maws. A tophet has a large opening in the front where the flames can be seen; sometimes this is an enormous mouth, and at other times it is a large hole in the tophet's belly. Horns and expressions of anger or wide‑mouthed laughter are common.

## Eager for Sacrifices

Among fire cultists, it's widely known that when a tophet's hands are raised above its mouth, it is demanding a sacrifice to roll down its palms and into its fiery maw.

## Heed Musical Commands

Flutes and drums can be used to control the actions of a tophet during sacrifices. They have the fortunate side effect of drowning out the cries and screams of living sacrifices.

## Magical Fires

The fires within a tophet's bronze body are largely magical and fueled by sacrifices. They don't require more than a symbolic amount of wood or coal to keep burning, but they do require sacrifices of food, cloth, and living creatures to keep them under control. A tophet that is not granted a sacrifice when it demands one might go on a fiery rampage, burning down buildings, granaries, or barns until its hunger is satisfied.

## Statblock

```ad-statblock
title: Tophet
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Tophet.webp#token)
*Huge construct, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 161 (`14d12 + 70`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|10 (+0)|20 (+5)| 6 (-2)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +8, Dexterity +3, Constitution +8
- **Skills** Perception +3
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** cold
- **Damage Immunities** fire, poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 8

## Traits

***Burning Heart.*** The tophet sheds bright light in a 30-foot radius and dim light for an additional 30 feet. Each creature in the bright light has resistance to cold damage. At the start of each of its turns, the tophet chooses whether this light is active.

***Construct Nature.*** The tophet doesn't require air, food, drink, or sleep.

***Heated Body.*** A creature that touches the tophet or hits it with a melee attack while within 5 feet of it takes `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage.

## Actions

***Multiattack.*** The tophet makes two Slam attacks. It can replace one Slam attack with a use of Burning Belly.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16) if it is a Large or smaller creature.

***Burning Belly.*** The tophet makes one Slam attack against a target it is grappling as it shoves the creature into its open, flame-filled belly. If the attack hits, the target is forced into the tophet's burning belly, and the grapple ends. While inside the belly, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), has three-quarters cover against attacks and other effects outside the belly, and it takes `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage at the start of each of its turns. A creature, including the target, can take its action to pull the target free from the belly by succeeding on a DC 16 Strength check. The creature making the attempt takes `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

***Gout of Flame (Recharge 5-6).*** Flames erupt on a point the tophet can see within 100 feet of it. Each creature within 10 feet of that point must make a DC 16 Dexterity saving throw, taking `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

urban