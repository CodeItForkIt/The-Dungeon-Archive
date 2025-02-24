---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/15
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Wurm"]
---
# Wurm
*Source: Plane Shift: Kaladesh p. 31*  

Wurms are enormous, legless creatures that burrow under the forests, mountains, and plains of Kaladesh, and which can exceed fifty feet in length when fully grown. A wurm devours everything in its path—flora, fauna, and inanimate objects alike—with a gaping maw containing multiple rings of sharp teeth and grinding plates. Rumor has it that at least one wurm tunnels beneath the large, lush park in Ghirapur called the Cowl, accounting for at least some of the mysterious disappearances there.

Both the colored scales of a wurm's skin and the winding patterns of its tunnels mimic the flow of aether through the sky. Some elf aether-seers believe that these tunnels reveal a deep connection between wurms and aether, and they explore wurm burrows in the hope of developing a similar connection. It is said that a wurm never doubles back along its own path, so following those paths is less dangerous than it might seem. However, the existence of a single wurm in an area suggests that others might be nearby, and wurm tunnels do cross each other—so not all these brave aether-seers return. Those who do are said to gain insights that they find difficult to express to others.

The [purple worm](2-Mechanics/CLI/bestiary/monstrosity/purple-worm.md) in the "Monster Manual" works well as a representation of Kaladesh's wurms.

```ad-statblock
title: Wurm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Wurm.webp#token)
*Gargantuan monstrosity, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 247 (`15d20 + 90`)
- **Speed** 50 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)| 7 (-2)|22 (+6)| 1 (-5)| 8 (-1)| 4 (-3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +11, Wisdom +4
- **Skills** ⏤
- **Senses** blindsight 30 ft., tremorsense 60 ft., passive Perception 9
- **Languages** —
- **Challenge** 15

## Traits

***Tunneler.*** The wurm can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.

## Actions

***Multiattack.*** The wurm makes two attacks: one with its bite and one with its stinger.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+9|noform|avg|text(22)` (`3d8 + 9`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Dexterity saving throw or be swallowed by the wurm. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the wurm, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the wurm's turns.

If the wurm takes 30 damage or more on a single turn from a creature inside it, the wurm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the wurm. If the wurm dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tail Stinger.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one creature. *Hit:* `dice:3d6+9|noform|avg|text(19)` (`3d6 + 9`) piercing damage, and the target must make a DC 19 Constitution saving throw, taking `dice:12d6|noform|avg|text(42)` (`12d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock