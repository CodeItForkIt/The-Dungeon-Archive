---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/desert
- monster/environment/underdark
- monster/size/large
- monster/type/beast
aliases: ["Night Scorpion"]
---
# Night Scorpion
*Source: Tome of Beasts 1 (2023 Edition) p. 320*  

*These midnight-black scorpions have a bright-red stripe on their tails, signaling the crippling poison within.*

## Blinding Poison

This aptly named arachnid hunter blinds victims with a dose of its crippling poison. It feeds on whole camels when given the chance, but it more commonly devours goats, sheep, and people. It hunts by night, when its senses are most effective.

## Underdark Giants

The species is common in deep caves and underworld realms. They are eight feet long with a seven-foot tail and daggerlike stinger. They weigh up to 200 pounds.

## Valuable Venom

Night scorpion venom is highly prized and can command upwards of 400 gp per dose.

## Statblock

```ad-statblock
title: Night Scorpion
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Night%20Scorpion.webp#token)
*Large beast, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 90 (`12d10 + 24`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|14 (+2)| 1 (-5)| 9 (-1)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft., passive Perception 9
- **Languages** —
- **Challenge** 3

## Actions

***Multiattack.*** The scorpion makes two Claw attacks and one Sting attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 12). The scorpion has two claws, each of which can grapple only one target.

***Sting.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d10+2|noform|avg|text(7)` (`1d10 + 2`) piercing damage, and the target must make a DC 12 Constitution saving throw. On a failure, the target takes `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) for 1 hour. On a success, a creature takes half the damage and isn't [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded). If the target fails the saving throw by 5 or more, it is also [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute, and it is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) while [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

desert, underdark