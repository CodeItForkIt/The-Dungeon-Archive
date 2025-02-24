---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/14
- monster/environment/mountain
- monster/environment/underdark
- monster/size/huge
- monster/type/elemental
aliases: ["Magma Landshark"]
---
# Magma Landshark
*Source: Tal'Dorei Campaign Setting Reborn p. 247*  

Lurking inside volcanoes, subterranean magma pits, and the endless seas of flame within the Elemental Plane of Fire, magma landsharks live only to eat. These creatures are physically similar to [bulettes](2-Mechanics/CLI/bestiary/monstrosity/bulette.md), the common landshark of the "Dividing Plains", but are filled with churning elemental power.

This fiery, armored predator burrows and burns through solid rock and can sense the slightest movement in the ground around it. When hungry—and these creatures are always hungry—a magma landshark erupts from under the earth, oblivious to any obstruction or danger, uprooting trees, destroying roads, unleashing avalanches, and leaving sinkholes behind in its wake. Its jaws widen as it swallows prey whole, and even creatures that initially survive the attack must contend with an aura of intense heat if they can't escape.

```ad-statblock
title: Magma Landshark
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Magma%20Landshark.webp#token)
*Huge elemental, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 150 (`12d12 + 72`)
- **Speed** 50 ft., burrow 50 ft., swim 50 ft. (lava only)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|11 (+0)|22 (+6)| 2 (-4)|14 (+2)| 5 (-3)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** Perception +7
- **Senses** darkvision 60 ft., tremorsense 120 ft., passive Perception 17
- **Damage Immunities** fire
- **Languages** —
- **Challenge** 14

## Traits

***Searing Presence.*** Any creature that starts its turn within 10 feet of the landshark takes `dice:2d10|noform|avg|text(11)` (`2d10`) fire damage.

***Standing Leap.*** The landshark's long jump is up to 40 feet and its high jump is up to 20 feet, with or without a running start.

***Illumination.*** The landshark sheds bright light in a 15-foot radius and dim light for an additional 15 feet.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:6d12+6|noform|avg|text(45)` (`6d12 + 6`) piercing damage, and `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage. If the target is a Large or smaller creature, it must succeed on a DC 18 Dexterity saving throw or be swallowed by the landshark. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the landshark, and it takes `dice:12d6|noform|avg|text(42)` (`12d6`) fire damage at the start of each of the landshark's turns.

If the landshark takes 30 damage or more on a single turn from a creature inside it, the landshark must succeed on a DC 23 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the landshark. If the landshark dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Deadly Leap.*** If the landshark jumps at least 15 feet as part of its movement, it can then use this action to land on its feet in a space that contains one or more other creatures. Each of those creatures must succeed on a DC 18 Strength or Dexterity saving throw (target's choice) or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone) and take `dice:6d6+6|noform|avg|text(27)` (`6d6 + 6`) bludgeoning damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) fire damage. On a successful save, the creature takes only half the damage, isn't knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone), and is pushed 5 feet out of the landshark's space into an unoccupied space of the creature's choice. If no unoccupied space is within range, the creature instead falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in the landshark's space.

***Lava Pool (Recharge 6).*** If the landshark is on solid ground, it melts the area around it, creating a pool of lava in a 10-foot radius. Any creature that starts its turn in the area or enters it for the first time on a turn takes `dice:8d10|noform|avg|text(44)` (`8d10`) fire damage.
```
^statblock

## Environment

mountain, underdark