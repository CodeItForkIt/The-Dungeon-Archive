---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/1-4
- monster/size/medium
- monster/type/beast
aliases: ["Horned Frog"]
---
# Horned Frog
*Source: Plane Shift: Ixalan p. 39*  

Frogs are more commonly heard than seen in Ixalan, joining their voices to the vivid soundscape of the jungle. They range from tiny poisonous tree frogs found in the branches of tall trees to huge horned frogs that lurk in marshy areas.

```ad-statblock
title: Horned Frog
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Horned%20Frog.webp#token)
*Medium beast, Unaligned*

- **Armor Class** 11
- **Hit Points** 18 (`4d8`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|13 (+1)|11 (+0)| 2 (-4)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +2, Stealth +3
- **Senses** darkvision 30 ft., passive Perception 12
- **Languages** —
- **Challenge** 1/4

## Traits

***Amphibious.*** The frog can breathe air and water.

***Standing Leap.*** The frog's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+1|noform|avg|text(4)` (`1d6 + 1`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 11). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the frog can't bite another target.

***Swallow.*** The frog makes one bite attack against a Small or smaller target it is grappling. If the attack hits, the target is swallowed, and the grapple ends. The swallowed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the frog, and it takes `dice:2d4|noform|avg|text(5)` (`2d4`) acid damage at the start of each of the frog's turns. The frog can have only one target swallowed at a time. If the frog dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock