---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aitfr-dn
- monster/cr/6
- monster/size/large
- monster/type/undead
aliases: ["Skeletal Horror"]
---
# Skeletal Horror
*Source: Adventures in the Forgotten Realms: Deepest Night p. 13*  

This horrid mass of bones clambers along on a dozen hands and feet without maintaining any consistent shape. One moment it moves like a centipede, the next it rears back to claw like a bear. The only consistent feature is a weird absence: no matter how many skulls make up its mass, this strange horror always seems to be headless.

The skeletal horrors in Kyrilla's lair are made from the bones of yuan-ti supplicants and cultists who came to learn her powers or, later, to steal them. She spared none of these intruders' lives, and in death their remains do her bidding.

```ad-statblock
title: Skeletal Horror
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AitFR-DN/Skeletal%20Horror.webp#token)
*Large undead, Neutral Evil*

- **Armor Class** 13
- **Hit Points** 150 (`20d10 + 40`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|15 (+2)| 6 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +3
- **Senses** darkvision 60 ft., passive Perception 16
- **Damage Vulnerabilities** bludgeoning
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 6

## Actions

***Multiattack.*** The horror makes two attacks with its claws.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+3|noform|avg|text(19)` (`3d10 + 3`) slashing damage.

***Wave of Bones (Recharge 5-6).*** The horror crashes into foes like a wave before quickly reforming. Each creature within 10 feet of the horror must make a DC 15 Dexterity saving throw, taking `dice:4d8|noform|avg|text(18)` (`4d8`) bludgeoning damage on a failed save, or half as much damage on a successful one. A creature that fails this saving throw is also knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock