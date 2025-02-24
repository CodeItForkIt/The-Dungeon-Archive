---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/underdark
- monster/size/huge
- monster/type/monstrosity
aliases: ["Angler Worm"]
---
# Angler Worm
*Source: Tome of Beasts 1 (2023 Edition) p. 20*  

*As patient as a fisherman, the angler worm lights a beacon in the darkness and waits for its next meal.*

## Silk Snares

The angler worm burrows into the ceilings of caves and tunnels, where it creates snares from strong silk threads coated with sticky mucus. It then lures prey into its snares while remaining safely hidden, emerging only to feed. With dozens of snares, food always comes to the angler worm eventually.

## Statblock

```ad-statblock
title: Angler Worm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Angler%20Worm.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 104 (`11d12 + 33`)
- **Speed** 20 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)| 5 (-3)|16 (+3)| 3 (-4)|14 (+2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** tremorsense 60 ft., passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 4

## Traits

***Keen Touch.*** The angler worm has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on vibrations.

***Snare Walker.*** The angler worm ignores movement restrictions caused by its snares or the snares of other angler worms.

***Spider Climb.*** The angler worm can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Transparent Trap.*** With 10 minutes of work, the angler worm can create a web of nearly transparent snares in a 20-foot cube. The web must be anchored between two solid masses or layered across a floor, wall, or ceiling. A web of snares layered over a flat surface has a depth of 5 feet. The web is difficult terrain, and the snares forming it are nearly transparent, requiring a successful DC 15 Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check to notice them.

A creature that starts its turn in the web of snares or enters the web during its turn must succeed on a DC 13 Dexterity saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the sticky snares. A creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the snares can use its action to free itself by succeeding on a DC 13 Strength check.

## Actions

***Multiattack.*** The angler worm makes two Bite attacks or one Bite attack and one Coils attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) piercing damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) acid damage.

***Coils.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 10 ft., one creature. *Hit:* `dice:3d6+2|noform|avg|text(12)` (`3d6 + 2`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by the angler worm, it can't breathe, it takes `dice:3d6|noform|avg|text(10)` (`3d6`) bludgeoning damage at the start of each of the angler worm's turns, and the angler worm can't use its Coils on another target.

***Ethereal Lure (Recharge 4-6).*** The angler worm creates an orb of faint, blue light on a point it can see within 20 feet of it. The light glows until the start of the worm's next turn. When a creature that isn't an angler worm starts its turn within 60 feet of the orb and can see the light, it must succeed on a DC 13 Wisdom saving throw or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) until the start of its next turn. While [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), the creature must take the Dash action and move toward the light by the most direct route, trying to get within 5 feet of the light. It doesn't avoid opportunity attacks, but before moving into damaging terrain, such as lava or a pit, the creature can repeat the saving throw, ending the effect on itself on a success. If the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) creature enters the worm's snares, it has disadvantage on the saving throw to avoid being [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained).
```
^statblock

## Environment

underdark