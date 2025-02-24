---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/14
- monster/size/huge
- monster/type/undead
aliases: ["Karavarix"]
---
# Karavarix
*Source: Dragonlance: Shadow of the Dragon Queen p. 183*  

```ad-statblock
title: Karavarix
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Karavarix.webp#token)
*Huge undead, typically  Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 230 (`20d12 + 100`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|10 (+0)|20 (+5)|11 (+0)|14 (+2)|10 (+0)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +5, Wisdom +7
- **Skills** Perception +7, Stealth +5
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 17
- **Damage Resistances** piercing
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 14

## Traits

***Legendary Resistance (3/Day).*** If Karavarix fails a saving throw, it can choose to succeed instead.

***Unusual Nature.*** Karavarix doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** Karavarix makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) necrotic damage. If the target is a Large or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 19). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and Karavarix can't bite a different target.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft. one target. *Hit:* `dice:1d8+6|noform|avg|text(10)` (`1d8 + 6`) slashing damage.

***Cataclysmic Breath (Recharge 5-6).*** Karavarix exhales a wave of ghostly purple flames in a 60-foot cone. Each creature in that area must make a DC 18 Dexterity saving throw, taking `dice:10d8|noform|avg|text(45)` (`10d8`) necrotic damage on a failed save, or half as much damage on a successful one. A creature dies if the breath reduces it to 0 hit points. Additionally, any Medium or smaller Humanoid killed by the breath's damage, as well as every corpse of such a creature within the cone, becomes a zombie (see the Monster Manual) under Karavarix's control. The zombie acts on Karavarix's initiative but immediately after Karavarix's turn. Absent any other command, the zombie tries to kill any non-Undead creature it encounters.

## Legendary Actions

***Claw.*** Karavarix makes one Claw attack.

***Cataclysmic Rush (Costs 2 Actions).*** Karavarix moves up to half its flying speed without provoking opportunity attacks, carrying with it any creatures it is grappling. During this move, if it enters the space of a Medium or smaller creature, that creature takes `dice:1d8|noform|avg|text(4)` (`1d8`) necrotic damage. A creature can take this damage only once per turn.
```
^statblock