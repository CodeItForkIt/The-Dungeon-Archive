---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/skt
- monster/cr/2
- monster/size/large
- monster/type/monstrosity
aliases: ["Purple Wormling"]
---
# Purple Wormling
*Source: Storm King's Thunder p. 242*  

A purple wormling is a baby purple worm no more than six weeks old. Its rubbery body is 9 feet long and weighs 1,500 pounds. Its mouth and musculature aren't yet strong enough to allow the wormling to burrow through rock. The poison in its tail stinger and the acid in its gullet are still relatively weak as well. Nevertheless, the wormling is a voracious feeder and attacks just about anything it can wrap its mouth around. A wormling's gullet can hold up to four Small creatures.

```ad-statblock
title: Purple Wormling
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SKT/Purple%20Wormling.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 12 (natural armor)
- **Hit Points** 42 (`5d10 + 15`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 7 (-2)|16 (+3)| 1 (-5)| 6 (-2)| 2 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 30 ft., tremorsense 30 ft., passive Perception 8
- **Languages** —
- **Challenge** 2

## Actions

***Multiattack.*** The wormling makes two attacks: one with its bite and one with its stinger.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(7)` (`1d8 + 5`) piercing damage. If the target is a Small or smaller creature, it must succeed on a DC 13 Dexterity saving throw or be swallowed by the worm. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the wormling, and it takes `dice:1d6|noform|avg|text(3)` (`1d6`) acid damage at the start of each of the wormling's turns.

If the wormling takes 10 damage or more on a single turn from a creature inside it, the wormling must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the wormling. If the wormling dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tail Stinger.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage, and the target must make a DC 13 Constitution saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock