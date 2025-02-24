---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/7
- monster/size/huge
- monster/type/giant
aliases: ["Boulderfoot Giant"]
---
# Boulderfoot Giant
*Source: Plane Shift: Zendikar p. 30*  

Zendikar's giants are enormous humanoids that live in tight-knit tribes as far as possible from the settlements of other races. Compared to ogres and minotaurs, they are civilized and intelligent, though they are wilder than the smaller humanoid races.

Three major groupings of giants inhabit three of Zendikar's continents. In the mountains of Akoum, the giants of the Boulderfoot tribe have a well-earned reputation for trampling their enemies underfoot (hence their name). In the Skyfang Mountains of Murasa, the giants of the Shatterskull tribe are rough brigands who often extort "tolls" from travelers trying to navigate the treacherous pass that shares the tribe's name. The Boulderfoot and Shatterskull giants are [stone giants](2-Mechanics/CLI/bestiary/giant/stone-giant.md) in D&D terms.

In Ondu, the giants of the Turntimber tribe live in the forest of the same name. They hunt baloths and other large game, living in close harmony with the woodland. Their druids are the only giants of Zendikar that are inclined toward magic. Some legends hold that the Turntimber giants are unrelated to the other giant tribes, but were originally druids who became giants only after years of living among the twisted trees. Elsewhere on Ondu, in the Makindi Trenches, a handful of deformed giants called trench giants scale the canyon walls looking for prey. They are solitary and do not think of themselves as members of a tribe. In fact, they are outcasts of the Turntimber tribe, banished because the mana of the forest warped their bodies and their hearts. The giants of the Turntimber tribe are similar to [cloud giants](2-Mechanics/CLI/bestiary/giant/cloud-giant.md), and the trench giants can be considered [fomorians](2-Mechanics/CLI/bestiary/giant/fomorian.md).

```ad-statblock
title: Boulderfoot Giant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Boulderfoot%20Giant.webp#token)
*Huge giant, Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 126 (`11d12 + 55`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|15 (+2)|20 (+5)|10 (+0)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +5, Constitution +8, Wisdom +4
- **Skills** Athletics +12, Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Giant
- **Challenge** 7

## Traits

***Stone Camouflage.*** The giant has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in rocky terrain.

## Actions

***Multiattack.*** The giant makes two greatclub attacks.

***Greatclub.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 15 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) bludgeoning damage.

***Rock.*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 60/240 ft., one target. *Hit:* `dice:4d10+6|noform|avg|text(28)` (`4d10 + 6`) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Reactions

***Rock Catching.*** If a rock or similar object is hurled at the giant, the giant can, with a successful DC 10 Dexterity saving throw, catch the missile and take no bludgeoning damage from it.
```
^statblock