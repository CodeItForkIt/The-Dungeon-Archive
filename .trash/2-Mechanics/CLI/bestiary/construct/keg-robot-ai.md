---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ai
- monster/cr/2
- monster/size/medium
- monster/type/construct
aliases: ["Keg Robot"]
---
# Keg Robot
*Source: Acquisitions Incorporated p. 212*  

> [!quote]  
> 
> This beer is delicious. But did the spigot really have to be placed in that spot?

A keg robot is a stout wood-and-metal construct, vaguely reminiscent of a dwarf wearing a horned helm and possessing a barrel for a body. These constructs are another achievement of the Heuristic Arcane Research and Development (HARD) department of Acquisitions Incorporated. These devices have a number of practical purposes, including the ability to be filled with a variety of substances of use to an adventuring party. Specific models are nominally named for their primary function, including "ambulatory fermenter," "mobile alchemical dispensary," and so forth. But their prominent use as portable beer dispensers has placed the name "keg robot" firmly into public consciousness.

A keg robot can hold up to three different kinds of liquid in its body cavity, from water and other potables to alchemical substances and lamp oil. Its individual storage compartments can leak, providing drinkable liquids with a unique but mostly safe flavor. These constructs have a rudimentary intellect that allows them to operate independently and discern friend from foe-and which sometimes causes them to operate with a crass sense of humor that has never been fully explained.

```ad-statblock
title: Keg Robot
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AI/Keg%20Robot.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 39 (`6d8 + 12`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|16 (+3)|15 (+2)| 6 (-2)| 8 (-1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +1
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common but can't speak
- **Challenge** 2

## Traits

***Customizable Storage.*** A keg robot can hold up to three types of liquid payload totaling 12 gallons within its hollow, barrel-shaped body. A full keg robot can make one liquid attack per gallon before the liquid must be refilled. Filling a keg robot takes 2 rounds per gallon. Differing payloads can alter the keg robot's attacks from those presented here.

## Actions

***Fist.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) bludgeoning damage.

***Acid Squirt.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 20/40 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) acid damage.

***Beer Shower.*** The keg robot spews an unnaturally potent beer in a 15-foot cone or in a 30-foot line that is 5 feet wide. Each creature in the area must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, a creature has its speed halved by exposure to the potent brew. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

Additionally, the beer shower extinguishes any fires or open flames in its area.

***Hot Oil Spray (Recharge 5-6).*** The keg robot sprays hot oil in a 15-foot cone or in a 30-foot line that is 5 feet wide. Each creature in the area must make a DC 13 Dexterity saving throw. On a failed save, a creature takes `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) fire damage and falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone). On a successful save, a creature takes half as much damage and doesn't fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

Any creature affected by the hot oil spray that takes fire damage before the oil dries (after 1 minute) takes an additional `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage, and the oil burns away.

If the oil that remains in the area of the spray is lit, it burns for `dice:1d4|noform|avg` (`1d4`) rounds and deals `dice:1d6|noform|avg|text(3)` (`1d6`) fire damage to any creature that enters the area for the first time on a turn or ends its turn there.
```
^statblock