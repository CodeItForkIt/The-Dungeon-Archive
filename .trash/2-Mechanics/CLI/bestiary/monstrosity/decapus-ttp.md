---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ttp
- monster/cr/4
- monster/size/large
- monster/type/monstrosity
aliases: ["Decapus"]
---
# Decapus
*Source: The Tortle Package p. 21*  

Decapuses are carnivorous, solitary hunters that swing through trees, scooping up prey with their 10-foot-long, suckered tentacles. Decapuses also use their tentacles to climb walls and ceilings.

After securing a high vantage point, a decapus hangs by one tentacle and attacks with the other nine. On the ground, a decapus is slower and less dangerous. It must use half of its tentacles to support its weight upright, leaving five tentacles with which it can attack and defend itself.

## Marine Decapus

A marine decapus is similar to its land-dwelling cousin, except that it gains a swimming speed of 30 feet and can breathe only underwater.

## Statblock

```ad-statblock
title: Decapus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TTP/Decapus.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 75 (`10d10 + 20`)
- **Speed** 15 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|14 (+2)| 4 (-3)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Athletics +4, Perception +2, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 12
- **Languages** —
- **Challenge** 4

## Actions

***Multiattack.*** The decapus makes two attacks: one with its bite and one with its tentacles.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the decapus. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) piercing damage.

***Tentacles.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 10 ft., one target. *Hit:* `dice:9d4+2|noform|avg|text(24)` (`9d4 + 2`) bludgeoning damage or `dice:5d4+2|noform|avg|text(14)` (`5d4 + 2`) bludgeoning damage if the decapus is grappling a creature other than the target or if the decapus is on the ground or floor. The target is also [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14) unless the decapus is already grappling a creature. Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained).
```
^statblock