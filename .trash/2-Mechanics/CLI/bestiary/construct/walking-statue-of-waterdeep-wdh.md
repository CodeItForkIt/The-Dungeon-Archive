---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdh
- monster/cr/18
- monster/size/gargantuan
- monster/type/construct
aliases: ["Walking Statue of Waterdeep"]
---
# Walking Statue of Waterdeep
*Source: Waterdeep: Dragon Heist p. 219*  

Scattered throughout Waterdeep are eight enormous statues that can defend the city in times of great peril. Because they are so destructive, the walking statues are used only to fend off armies and seemingly insurmountable foes.

Each statue has a name and a unique appearance (see "The Walking Statues"), but in terms of statistics they are similar. The statue known as the Swordmaiden is too broken to be animated, and only the wielder of the Blackstaff (see appendix A) can animate the other seven.

## Landmarks

Over the years, Waterdavians have built structures around and on top of several of the statues, believing them to be little more than landmarks at this point. In their inanimate state, the statues pose little danger-but any structures attached to a walking statue are destroyed the first time it animates.

## Constructed Nature

A walking statue doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Walking Statue of Waterdeep
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDH/Walking%20Statue%20of%20Waterdeep.webp#token)
*Gargantuan construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 314 (`17d20 + 136`)
- **Speed** 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|30 (+10)| 8 (-1)|27 (+8)| 1 (-5)|10 (+0)| 1 (-5)|

- **Proficiency Bonus** +6
- **Saving Throws** Constitution +14
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 10
- **Damage Immunities** cold; fire; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks not made with adamantine weapons
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 18

## Traits

***Crumbling Colossus.*** When the statue drops to 0 hit points, it crumbles and is destroyed. Any creature on the ground within 30 feet of the crumbling statue must make a DC 22 Dexterity saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) bludgeoning damage on a failed save, or half as much damage on a successful one.

***Immutable Form.*** The statue is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The statue has advantage on saving throws against spells and other magical effects.

***Siege Monster.*** The statue deals double damage to objects and structures.

## Actions

***Multiattack.*** The statue makes two melee attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 5 ft., one target. *Hit:* `dice:3d12+10|noform|avg|text(29)` (`3d12 + 10`) bludgeoning damage.

***Hurled Stone.*** *Ranged Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, range 200/800 ft., one target. *Hit:* `dice:6d10+10|noform|avg|text(43)` (`6d10 + 10`) bludgeoning damage.
```
^statblock