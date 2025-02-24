---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1
- monster/environment/any
- monster/size/medium
- monster/type/undead
aliases: ["Ashwalker"]
---
# Ashwalker
*Source: Tome of Beasts 1 (2023 Edition) p. 28*  

*A winged shadow eclipsed the sun, and an inferno consumed the city. An ashen corpse rose from the dirt and walked the charred streets as if its world had not just been incinerated.*

Ashwalkers are the unfortunate result of humanoids who met their end from the breath of a dragon while in a place suffused with powerful magical energy. These undead creatures often emerge in hordes after a dragon's rage has leveled a city. Though burnt almost to ashes, many ashwalkers can rasp out a few words, typically words of hate for those who were spared the ashwalker's fate.

## The Last Breath

While the fire of a red dragon's breath is the most common source of ashwalkers, they can be created from any dragon's breath. The magical infusion of the dragon's breath that kills the individual leaves residual energy of a similar type in the remains. For example, an ashwalker killed by poison breath often exudes some of the noxious clouds as it walks the wastelands of its destroyed home.

## Unlived Dreams

Ashwalkers have no purpose in undeath and rarely serve a master. Sometimes they carry on a sad mimicry of their former life, acting out the final hours before their demise, not fully aware of what happened. Some ashwalkers even return to the site of their homes and lay down in the dirt to sleep, although sleep never comes. Adventurers who seek the riches of lost civilizations leveled by dragon fire have reported seeing smoldering corpses milling about marketplaces or theatre spaces until a living soul snaps them from their reverie, often driving them into maddened rages.

## Statblock

```ad-statblock
title: Ashwalker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ashwalker.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 12
- **Hit Points** 31 (`7d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|15 (+2)|10 (+0)| 7 (-2)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands all languages it knew in life but can't speak
- **Challenge** 1

## Traits

***Breath Born.*** The ashwalker has immunity to a type of damage based on the type of dragon that killed it: acid (black, copper), cold (silver, white), fire (brass, gold, red), lightning (blue, bronze), or poison (green).

***Burst of Breath.*** A creature that touches the ashwalker or hits it with a melee attack while within 5 feet of it takes `dice:1d6|noform|avg|text(3)` (`1d6`) damage of the type noted in its Breath Born trait.

***Last Breath.*** The first time the ashwalker is reduced to 0 hp, it drops to 1 hp instead and its Draconic Breath automatically recharges. The ashwalker transforms into raw energy of the type noted in its Breath Born trait. While in this energy form, it is immune to all damage and to being [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). At the end of the ashwalker's next turn, it is destroyed.

***Undead Nature.*** The ashwalker doesn't require air, food, drink, or sleep.

## Actions

***Slam.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) bludgeoning damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) damage of the type noted in the ashwalker's Breath Born trait.

***Draconic Breath (Recharge 6).*** The ashwalker exhales elemental energy in a 15-foot cone. Each creature in the area must make a DC 12 Constitution saving throw, taking `dice:4d6|noform|avg|text(14)` (`4d6`) damage of the type noted in its Breath Born trait on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

any