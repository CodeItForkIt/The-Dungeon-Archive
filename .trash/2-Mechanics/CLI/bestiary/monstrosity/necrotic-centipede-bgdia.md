---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgdia
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
aliases: ["Necrotic Centipede"]
---
# Necrotic Centipede
*Source: Baldur's Gate: Descent Into Avernus p. 119*  

```ad-statblock
title: Necrotic Centipede
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGDIA/Necrotic%20Centipede.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 195 (`17d12 + 85`)
- **Speed** 30 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|13 (+1)|21 (+5)| 4 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., tremorsense 60 ft., passive Perception 10
- **Damage Immunities** necrotic, fire
- **Languages** —
- **Challenge** 11

## Traits

***Necrotic Body.*** A creature that touches the centipede or hits it with a melee attack while within 5 feet of it takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:6d10+7|noform|avg|text(40)` (`6d10 + 7`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. If the target is a creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the centipede can't bite another target.

***Swallow.*** The centipede makes one bite attack against a Medium or smaller creature it is grappling. If the attack hits, that creature takes the bite's damage and is swallowed, and the grapple ends. While swallowed, the creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the centipede, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the centipede's turns.

If the centipede takes 30 damage or more on a single turn from a creature inside it, the centipede must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the centipede. If the centipede dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock