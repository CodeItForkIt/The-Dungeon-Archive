---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/3
- monster/size/large
- monster/type/fiend/devil
aliases: ["Nergaliid"]
---
# Nergaliid
*Source: Explorer's Guide to Wildemount p. 296*  

Corpulent, scaled, and utterly repulsive, these vicious devils stalk the dark edges of society away from prying eyes, subsisting on the life force of unsuspecting humanoids. Creatures that die to the nergaliid's feeding leave a corrupted undead corpse behind known as a husk zombie (see earlier in this chapter).

The nergaliid favors feeding on the life force of sleeping humanoids, feasting on the same prey nightly—so long as its victim remains unaware. This ensures a lasting source of nourishment, with the victim beset by terrible nightmares as long as the feeding continues. When a nergaliid is discovered, it tries to strike a deal with the one who uncovered it. It might offer material wealth in exchange for freedom and silence. Only when an accord seems unlikely does the nergaliid attack.

```ad-statblock
title: Nergaliid
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Nergaliid.webp#token)
*Large fiend (devil), Lawful Evil*

- **Armor Class** 12 (natural armor)
- **Hit Points** 42 (`4d10 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|12 (+1)|20 (+5)|12 (+1)|10 (+0)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +5, Perception +2, Stealth +5
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Infernal
- **Challenge** 3

## Traits

***Shadow Stealth.*** While in dim light or darkness, the nergaliid can take the Hide action as a bonus action.

***Standing Leap.*** The nergaliid's long jump is up to 30 feet and its high jump is up to 20 feet, with or without a running start.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage, and the target must succeed on a DC 15 Constitution saving throw or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. The [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Tongue Lash.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 20 ft., one target. *Hit:* `dice:1d12+4|noform|avg|text(10)` (`1d12 + 4`) bludgeoning damage.

***Siphon Life (Recharge 4-6).*** The nergaliid magically draws the life from a humanoid it can see within 40 feet of it. The target must make a DC 15 Wisdom saving throw. An [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) target fails the save automatically. On a failed save, the creature takes `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage, and the nergaliid gains temporary hit points equal to the damage taken. On a successful save, the target takes half as much damage, and the nergaliid doesn't gain temporary hit points. If this damage kills the target, its body rises at the end of the nergaliid's current turn as a [husk zombie](2-Mechanics/CLI/bestiary/undead/husk-zombie-egw.md) (see earlier in this chapter).
```
^statblock