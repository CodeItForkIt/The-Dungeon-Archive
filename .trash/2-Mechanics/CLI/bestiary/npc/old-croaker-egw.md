---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Old Croaker"]
---
# Old Croaker
*Source: Explorer's Guide to Wildemount p. 240*  

```ad-statblock
title: Old Croaker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Old%20Croaker.webp#token)
*Large beast, Unaligned*

- **Armor Class** 11
- **Hit Points** 39 (`6d10 + 6`)
- **Speed** 20 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|13 (+1)|13 (+1)| 2 (-4)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 30 ft., passive Perception 10
- **Damage Immunities** cold
- **Languages** —
- **Challenge** 1

## Traits

***Amphibious.*** Old Croaker can breathe air and water.

***Standing Leap.*** Old Croaker's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) piercing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) poison damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and Old Croaker can't bite another target.

***Swallow.*** Old Croaker makes one bite attack against a Medium or smaller target it is grappling. If the attack hits, the target is swallowed, and the grapple ends. The swallowed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside Old Croaker, and it takes `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage at the start of each of Old Croaker's turns. Old Croaker can have only one target swallowed at a time.

If Old Croaker dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 5 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock