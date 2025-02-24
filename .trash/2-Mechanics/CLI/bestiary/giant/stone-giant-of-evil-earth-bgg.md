---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgg
- monster/cr/9
- monster/size/huge
- monster/type/giant
aliases: ["Stone Giant of Evil Earth"]
---
# Stone Giant of Evil Earth
*Source: Bigby Presents: Glory of the Giants p. 179*  

Stone giants with a bent toward cruelty and destruction might reject the gods of the Ordning and turn to the worship of Ogrémoch, the Prince of Evil Earth. These giants view the surface world not as a realm of dream but as a nightmare worthy only of destruction, so they lend their strength to cults that plan to reduce the world to rubble.

Outfitted in heavy armor crafted to resemble the cult's patron, stone giants of Evil Earth wield weapons that pulse with thunderous energy. These giants serve as the muscle for the cult, wielding their might to destroy the surface world in the name of Ogrémoch.

```ad-statblock
title: Stone Giant of Evil Earth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGG/Stone%20Giant%20of%20Evil%20Earth.webp#token)
*Huge giant, typically  Neutral Evil*

- **Armor Class** 20 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 137 (`11d12 + 66`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|13 (+1)|22 (+6)|10 (+0)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +10, Constitution +10
- **Skills** Athletics +14, Perception +5
- **Senses** darkvision 60 ft., passive Perception 15
- **Languages** Common, Giant, Terran
- **Challenge** 9

## Actions

***Multiattack.*** The giant makes two Thundering Stone Club or Boulder attacks in any combination.

***Thundering Stone Club.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 15 ft., one target. *Hit:* `dice:3d6+6|noform|avg|text(16)` (`3d6 + 6`) bludgeoning damage. The giant can cause the club to emit a burst of thunderous energy that deals `dice:3d6|noform|avg|text(10)` (`3d6`) thunder damage to each creature, other than the giant, within 30 feet of the target. The club can emit a burst this way only once per turn.

***Boulder.*** *Ranged Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, range 60/240 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) bludgeoning damage, and the target must succeed on a DC 18 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition. After the giant throws the boulder, roll a `dice:d6|noform|avg` (`d6`); on a roll of 3 or lower, the giant has no more boulders to throw.

## Reactions

***Unyielding.*** In response to failing a saving throw to avoid being moved, having the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition, or both, the giant succeeds instead.
```
^statblock