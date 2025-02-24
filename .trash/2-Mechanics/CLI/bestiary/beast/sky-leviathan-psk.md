---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/10
- monster/size/gargantuan
- monster/type/beast
aliases: ["Sky Leviathan"]
---
# Sky Leviathan
*Source: Plane Shift: Kaladesh p. 28*  

The aethersphere is home to its own ecosystem. Tiny organisms float in the aether currents, deriving all their energy from it and serving as food for larger creatures. Leviathans (similar in form to enormous eels) and flying whales filter these organisms out of the air as they swim through the aethersphere. The whales, as a rule, are not hostile by nature, though they can cause devastating sparks or destructive storms as they move through the aether flows. But leviathans are perpetually hungry, and feed on drakes and airships just as readily as they do on smaller creatures. Along with dragons, leviathans are the primary reason that aether-mining airships carry enormous harpoons.

A sky leviathan is similar to a [purple worm](2-Mechanics/CLI/bestiary/monstrosity/purple-worm.md) in its propensity to swallow prey whole, but it lacks the worm's poison stinger and is therefore significantly less dangerous. Use the statistics presented here.

Sky whales are generally docile filter-feeders that avoid confrontations with airships and flying predators whenever possible. Use the statistics for a [giant crocodile](2-Mechanics/CLI/bestiary/beast/giant-crocodile.md), but replace its bite attack with a flipper attack that is identical to its tail attack. A sky whale has a flying speed of 50 feet and can hover.

```ad-statblock
title: Sky Leviathan
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Sky%20Leviathan.webp#token)
*Gargantuan beast, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 247 (`15d20 + 90`)
- **Speed** fly 50 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)| 7 (-2)|22 (+6)| 1 (-5)| 8 (-1)| 4 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +10, Wisdom +3
- **Skills** ⏤
- **Senses** passive Perception 9
- **Languages** —
- **Challenge** 10

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+9|noform|avg|text(22)` (`3d8 + 9`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 18 Dexterity saving throw or be swallowed by the leviathan. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the leviathan, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the leviathan's turns.

If the leviathan takes 30 damage or more on a single turn from a creature inside it, the leviathan must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the leviathan. If the leviathan dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock