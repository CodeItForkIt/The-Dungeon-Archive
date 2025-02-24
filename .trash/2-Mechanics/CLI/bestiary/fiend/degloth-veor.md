---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/11
- monster/size/large
- monster/type/fiend/demon
aliases: ["Degloth"]
---
# Degloth
*Source: Vecna: Eve of Ruin p. 218*  

Degloths are massive, blue, bipedal demons with razor-studded fists. They are commonly used as shock troops on the front lines of wars waged in the Abyss and other Outer Planes. Degloths gravitate toward violence and mayhem without caring about the reasons behind the bloodshed. They enjoy ripping their enemies limb from limb using their razor-studded fists, which are equally adept at slashing foes and crushing the life from them.

```ad-statblock
title: Degloth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Degloth.webp#token)
*Large fiend (demon), typically  Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 133 (`14d10 + 56`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|17 (+3)|18 (+4)| 6 (-2)|11 (+0)| 9 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +10, Constitution +8
- **Skills** Athletics +10, Perception +4
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, telepathy 120 ft.
- **Challenge** 11

## Traits

***Magic Resistance.*** The degloth has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The degloth makes two Razor Fist attacks.

***Razor Fist.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) slashing damage, and if the target is a Medium or smaller creature, the target has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 18). Until this grapple ends, the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition, and the degloth can't use this fist to grapple another target. The degloth has two fists.

## Bonus Actions

***Crush.*** The degloth targets one creature currently [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The target must make a DC 18 Strength saving throw, taking `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) bludgeoning damage on a failed save or half as much damage on a successful one.
```
^statblock