---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tftyp
- monster/cr/3
- monster/size/large
- monster/type/monstrosity
aliases: ["Giant Ice Toad"]
---
# Giant Ice Toad
*Source: Tales from the Yawning Portal p. 235*  

In a cavern within the glacial rift (Against the Giants), a group of ice toads vigorously guard their territory. Waves of cold radiate from the creature, afflicting those that try to approach it, and anyone unfortunate enough to be swallowed suffers injury from cold as well as from the toad's digestive juices.

```ad-statblock
title: Giant Ice Toad
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Giant%20Ice%20Toad.webp#token)
*Large monstrosity, Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 52 (`7d10 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|13 (+1)|14 (+2)| 8 (-1)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** cold
- **Languages** Ice Toad
- **Challenge** 3

## Traits

***Amphibious.*** The toad can breathe air and water.

***Cold Aura.*** Any creature that starts its turn within 10 feet of the toad takes `dice:1d10|noform|avg|text(5)` (`1d10`) cold damage.

***Standing Leap.*** The toad's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the toad can't bite another target.

***Swallow.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one Medium or smaller creature the toad is grappling. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage, the target is swallowed, and the grapple ends. The swallowed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the toad, and it takes `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage and `dice:2d10|noform|avg|text(11)` (`2d10`) cold damage at the start of each of the toad's turns. The toad can have only one target swallowed at a time.

If the toad dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock