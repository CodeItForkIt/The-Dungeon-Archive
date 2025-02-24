---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/15
- monster/size/huge
- monster/type/monstrosity
aliases: ["Froghemoth Elder"]
---
# Froghemoth Elder
*Source: Quests from the Infinite Staircase p. 198*  

Froghemoths are massive amphibious predators with starry origins. A froghemoth has four tentacles, a rubbery hide, a long prehensile tongue, and three bulbous eyes branching from an extendable stalk.

Though most froghemoths lurk in swamps, those raised in unnatural environs—as well as those that dine on smaller, weaker hatchlings—are unmatched in strength and hunger. These ancient specimens, known as froghemoth elders, possess alien abilities and warp the ecosystems in which they dwell.

To learn more about froghemoths, see*Mordenkainen Presents: Monsters of the Multiverse*.

## A Froghemoth Elder's Lair

Froghemoth elders lair in unnatural ecosystems that facilitate their growth, such as wrecked spaceships, primordial bogs, and radioactive pools.

## Statblock

```ad-statblock
title: Froghemoth Elder
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Froghemoth%20Elder.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 207 (`18d12 + 90`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|13 (+1)|20 (+5)| 2 (-4)|14 (+2)| 8 (-1)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +12, Constitution +10, Wisdom +7
- **Skills** Perception +12, Stealth +6
- **Senses** darkvision 60 ft., passive Perception 22
- **Damage Resistances** fire, lightning
- **Languages** —
- **Challenge** 15

## Traits

***Amphibious.*** The froghemoth can breathe air and water.

***Legendary Resistance (3/Day).*** If the froghemoth fails a saving throw, it can choose to succeed instead.

***Shock Susceptibility.*** If the froghemoth takes lightning damage, it suffers two effects until the end of its next turn: its speed is halved, and it has disadvantage on Dexterity saving throws.

## Actions

***Multiattack.*** The froghemoth makes one Bite attack and two Tentacle attacks, and it can use Tongue.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+7|noform|avg|text(23)` (`3d10 + 7`) piercing damage, and the target is swallowed if it is a Medium or smaller creature. A swallowed creature has the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions, has total cover against attacks and other effects outside the froghemoth, and takes `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage at the start of each of the froghemoth's turns.

The froghemoth's gullet can hold up to three creatures at a time. If the froghemoth takes 25 damage or more on a single turn from a creature inside it, the froghemoth must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which lands in a space within 10 feet of the froghemoth and has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. If the froghemoth dies, any swallowed creatures are no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 10 feet of movement, exiting with the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 20 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) bludgeoning damage, and the target has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 20). Until this grapple ends, the froghemoth can't use this tentacle on another target. The froghemoth has four tentacles.

***Tongue.*** The froghemoth targets one Large or smaller creature that it can see within 25 feet of it. The target must make a DC 20 Strength saving throw. On a failed save, the target is pulled into an unoccupied space within 5 feet of the froghemoth.

## Reactions

The froghemoth can take up to three reactions per round but only one per turn.

***Alien Gaze.*** When a creature the froghemoth can see damages the froghemoth, the froghemoth swivels its eyestalk toward the creature and pierces the creature's mind with its otherworldly gaze. That creature must make a DC 18 Intelligence saving throw, taking `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage on a failed save or half as much damage on a successful one.

***Leap.*** Immediately after a creature the froghemoth can see ends its turn, the froghemoth jumps up to half its speed. Each creature within 5 feet of the froghemoth when it lands must succeed on a DC 20 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

![Froghemoth Elder](2-Mechanics/CLI/bestiary/legendary-group/froghemoth-elder-qftis.md)
```
^statblock