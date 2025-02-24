---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/18
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Citadel Spider"]
---
# Citadel Spider
*Source: Vecna: Eve of Ruin p. 214*  

> [!quote] A quote from Camlash, Balor General of Lolth  
> 
> Citadel spiders aren't smart, but for sheer battlefield power and versatility, they can't be beat.

Lolth's followers breed spiders of all types and sizes, infusing the creatures with foul energy from the Demonweb Pits. Perhaps the most feared of such abominations is the citadel spider. The titanic citadel spider serves as a powerhouse weapon and mobile command post. Wedges of chitin atop a citadel spider's back shield passengers and protect the spider's biological cannon. A citadel spider can launch globs of acidic webbing from its cannon that hold victims in place until the spider can eviscerate them with its serrated jaws.

```ad-statblock
title: Citadel Spider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Citadel%20Spider.webp#token)
*Gargantuan monstrosity, typically  Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 310 (`20d20 + 150`)
- **Speed** 50 ft., climb 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|10 (+0)|21 (+5)| 6 (-2)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +6
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 11
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** —
- **Challenge** 18

## Traits

***Legendary Resistance (3/Day).*** If the spider fails a saving throw, it can choose to succeed instead.

***Spider Climb.*** The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Walker.*** The spider ignores movement restrictions caused by webbing.

## Actions

***Multiattack.*** The spider makes two Bite attacks. It can replace one of these attacks with a use of Web Bomb.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 20 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Web Bomb.*** *Ranged Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, range 300 ft./600 ft., one target. *Hit:* `dice:3d10+8|noform|avg|text(24)` (`3d10 + 8`) bludgeoning damage, and the target and all creatures within 10 feet of it must succeed on a DC 19 Dexterity saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) acid damage and have the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition until the start of the spider's next turn.

## Reactions

***Absorb Blow.*** In response to being hit with an attack roll, the spider's carapace absorbs some of the blow, reducing the damage it takes by `dice:2d10|noform|avg|text(11)` (`2d10`).
```
^statblock