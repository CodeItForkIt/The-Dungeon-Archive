---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/20
- monster/size/huge
- monster/type/fiend/demon
aliases: ["Devorastus"]
---
# Devorastus
*Source: Chains of Asmodeus p. 198*  

```ad-statblock
title: Devorastus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Devorastus.webp#token)
*Huge fiend (demon), Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 275 (`22d12 + 132`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|14 (+2)|22 (+6)| 8 (-1)| 6 (-2)|10 (+0)|

- **Proficiency Bonus** +6
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Damage Resistances** cold; fire; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** acid
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** telepathy 120 ft.
- **Challenge** 20

## Traits

***Legendary Resistance (3/Day).*** If Devorastus fails a saving throw, it can choose to succeed instead.

***Ooze Cube.*** Devorastus takes up its entire space. Other creatures can enter the space, but a creature that does so is subjected to Engulf and has disadvantage on the saving throw. Creatures inside the cube can be seen but have total cover. A creature within 5 feet of the cube can take an action to pull a creature or object out of the cube. Doing so requires a successful DC 21 Strength check, and the creature making the attempt takes `dice:10d6|noform|avg|text(35)` (`10d6`) acid damage. The cube can hold only one Huge creature or up to six Large or smaller creatures inside it at a time.

***Sticky.*** Devorastus can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Transparent.*** Even when Devorastus is in plain sight, it takes a successful DC 15 Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) check to spot Devorastus if it has neither moved nor attacked. A creature that tries to enter Devorastus' space while unaware of Devorastus is surprised by it.

## Actions

***Multiattack.*** Devorastus makes four attacks using its Pseudopod, Spit, or a combination of the two.

***Pseudopod.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 20 ft., one target. *Hit:* `dice:12d6|noform|avg|text(42)` (`12d6`) acid damage.

***Spit.*** *Ranged Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 100/200 ft., one target. *Hit:* `dice:8d6|noform|avg|text(28)` (`8d6`) acid damage. A target hit by this attack must make a DC 21 Constitution saving throw. On a failed save, the target has the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.

***Engulf.*** Devorastus moves up to its speed. While doing so, it can enter Large or smaller creatures' spaces. Whenever Devorastus enters a creature's space, the creature must make a DC 21 Dexterity saving throw. On a successful save, the creature can choose to be pushed 5 feet back or to the side of Devorastus. A creature that chooses not to be pushed suffers the consequences of a failed saving throw. On a failed save, Devorastus enters the creature's space, the creature takes `dice:10d6|noform|avg|text(35)` (`10d6`) acid damage, and is engulfed. The engulfed creature can't breathe, has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, and takes `dice:12d6|noform|avg|text(42)` (`12d6`) acid damage at the start of each of Devorastus' turns. When Devorastus moves, the engulfed creature moves with it. An engulfed creature can try to escape by making a DC 21 Strength check as an action. On a success, the creature escapes and enters a space of its choice within 5 feet of Devorastus.
```
^statblock