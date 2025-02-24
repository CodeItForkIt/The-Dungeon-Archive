---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/15
- monster/environment/desert
- monster/environment/grassland
- monster/environment/hill
- monster/size/medium
- monster/type/elemental
aliases: ["Slow Storm"]
---
# Slow Storm
*Source: Tome of Beasts 1 (2023 Edition) p. 333*  

*Wisps of humid wind revolve around this spiny ball. Two massive black eyes and a dark mouth are the only features visible through its static-straight quills.*

Despite its perhaps comical appearance, a slow storm is a creature of wind, lightning, and chaos, able to send minute electrical shocks into creatures that cause pain every time the creature moves. It turns the bodies of physically able creatures against them, forcing them to choose between relative inactivity or ever-increasing pain.

## Small Central Core

The nucleus of a slow storm is a sphere of ice and stone, and it is surrounded by protective, high-speed winds.

## Static Generator

A slow storm has no internal organs other than its brain, and it lives on the energy and moisture it drains from opponents. Its quills not only deflect debris but also generate static electricity that it uses when attacking.

## Statblock

```ad-statblock
title: Slow Storm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Slow%20Storm.webp#token)
*Medium elemental, Chaotic Neutral*

- **Armor Class** 19 (natural armor)
- **Hit Points** 220 (`21d8 + 126`)
- **Speed** 0 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|19 (+4)|22 (+6)|11 (+0)|18 (+4)|11 (+0)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +9, Constitution +11
- **Skills** ⏤
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 14
- **Damage Resistances** acid; cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Auran, Common
- **Challenge** 15

## Traits

***Elemental Nature.*** The slow storm doesn't require air, food, drink, or sleep.

***Eye of the Storm.*** The slow storm is surrounded by a 15-foot-radius wind storm. The storm imposes disadvantage on ranged weapon attack rolls and Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks based on sight or hearing within the area. The winds extinguish open flames and disperse fog. A flying creature in the storm must land at the end of its turn or fall. Each creature that starts its turn in the area must succeed on a DC 18 Dexterity saving throw or take `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage. The storm's area is difficult terrain for any creature other than the slow storm.

## Actions

***Multiattack.*** The slow storm makes three Slam attacks or four Lightning Bolt attacks. If two Slam attacks hit one creature, the target must succeed on a DC 18 Constitution saving throw or be wracked with pain for 1 minute. While the target is wracked with pain, minute bits of electricity dance within its body, and the target takes `dice:1d8|noform|avg|text(4)` (`1d8`) lightning damage for every 5 feet it moves. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+5|noform|avg|text(21)` (`3d10 + 5`) bludgeoning damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage.

***Lightning Bolt.*** *Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 120 ft., one target. *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) lightning damage.

***Static Shock (Recharge 5-6).*** The slow storm releases built-up electricity in a 60-foot cone. Each creature in the area must make a DC 18 Constitution saving throw, taking `dice:12d8|noform|avg|text(54)` (`12d8`) lightning damage on a failed save, or half as much damage on a successful one. A creature that fails this saving throw by 5 or more is also [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) for 1 minute. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

desert, grassland, hill