---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/skt
- monster/cr/1
- monster/size/large
- monster/type/beast
aliases: ["Ice Spider"]
---
# Ice Spider
*Source: Storm King's Thunder p. 127*  

```ad-statblock
title: Ice Spider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SKT/Ice%20Spider.webp#token)
*Large beast, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 26 (`4d10 + 4`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|16 (+3)|12 (+1)| 2 (-4)|11 (+0)| 4 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +7
- **Senses** blindsight 10 ft., darkvision 60 ft., passive Perception 10
- **Damage Resistances** cold
- **Languages** —
- **Challenge** 1

## Traits

***Spider Climb.*** The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Sense.*** While in contact with a web, the spider knows the exact location of any other creature in contact with the same web.

***Web Walker.*** The spider ignores movement restrictions caused by webbing.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage, and the target must make a DC 11 Constitution saving throw, taking `dice:2d8|noform|avg|text(9)` (`2d8`) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 hour, even after regaining hit points, and is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way.

***Icy Web (Recharge 5-6).*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 30/60 ft., one creature. *Hit:* The target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by webbing, and takes 1 cold damage at the start of each of its turns. As an action, the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target can make a DC 12 Strength check, bursting the webbing on a success. The webbing can also be attacked and destroyed (AC 10; hp 5; vulnerability to fire damage; immunity to poison, and psychic damage).
```
^statblock