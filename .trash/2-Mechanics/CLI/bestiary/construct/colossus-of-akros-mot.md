---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/23
- monster/size/gargantuan
- monster/type/construct
aliases: ["Colossus of Akros"]
---
# Colossus of Akros
*Source: Mythic Odysseys of Theros p. 218*  

An enormous golem of bronze and iron overlooks the path leading to the polis of Akros. Though it is rarely called on to defend the polis, the sight of its towering form is enough to ease the minds of the populace. In truly desperate times, priests of Purphoros work their magic to call the colossus to life, whereupon the earth rumbles as it steps down from its twin plinths to place itself before the threat.

```ad-statblock
title: Colossus of Akros
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Colossus%20of%20Akros.webp#token)
*Gargantuan construct, Unaligned*

- **Armor Class** 21 (natural armor)
- **Hit Points** 350 (`20d20 + 140`)
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|10 (+0)|25 (+7)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +16, Constitution +14
- **Skills** Athletics +16, Perception +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Immunities** fire; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** understands Common and Celestial but can't speak
- **Challenge** 23

## Traits

***Crumbling Destruction.*** When the colossus drops to 0 hit points, it crumbles and is destroyed. Any creature on the ground within 30 feet of the crumbling statue must make a DC 22 Dexterity saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) bludgeoning damage and `dice:4d10|noform|avg|text(22)` (`4d10`) fire damage on a failed save, or half as much damage on a successful one.

***Fire Absorption.*** Whenever the colossus is subjected to fire damage, it takes no damage and instead regains a number of hit points equal to the fire damage dealt.

***Immutable Form.*** The colossus is immune to any spell or effect that would alter its form.

***Magic Weapons.*** The colossus's weapon attacks are magical.

***Siege Monster.*** The colossus deals double damage to objects and structures.

## Actions

***Multiattack.*** The colossus of Akros makes two melee attacks.

***Spear.*** *Melee or Ranged Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 15 ft., or range 200/600 ft., one target. *Hit:* `dice:4d6+9|noform|avg|text(23)` (`4d6 + 9`) piercing damage, or `dice:4d8+9|noform|avg|text(27)` (`4d8 + 9`) piercing damage if used with two hands to make a melee attack. If the colossus makes a ranged attack with this spear, the spear magically returns to its hand after the attack.

***Sword.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 15 ft., one target. *Hit:* `dice:6d8+9|noform|avg|text(36)` (`6d8 + 9`) slashing damage.

***Flames of Akros (Recharge 6).*** Magical flames issue from the colossus toward up to three creatures the colossus can see within 90 feet of it. Each target must make a DC 24 Dexterity saving throw, taking `dice:8d8|noform|avg|text(36)` (`8d8`) fire damage on a failed save, or half as much damage on a successful one. On a failed save, a target also magically catches fire for 1 minute. At the end of each of its turns thereafter, the burning target repeats the saving throw. It takes `dice:4d8|noform|avg|text(18)` (`4d8`) fire damage on a failed save, and the effect ends on a successful one.
```
^statblock