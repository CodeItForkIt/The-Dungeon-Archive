---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/forest
- monster/environment/underdark
- monster/size/large
- monster/type/dragon
aliases: ["Elder Shadow Drake"]
---
# Elder Shadow Drake
*Source: Tome of Beasts 1 (2023 Edition) p. 143*  

*A large dragon with black scales and shadowy wings emerges from the darkness. Its red eyes glare bright as coals, and it speaks in a deep monotone.*

## Solitary Lairs

They haunt dark and lonely places, such as deep caves, dense forests, shadowy ruins, and many wild locations in the Plane of Shadow. They are long-lived for drakes, often reaching 250 years of age, and mate rarely, abandoning their eggs shortly before hatching.

## Fade Into Shadows

An elder shadow drake naturally fades from view in areas of dim light or darkness, becoming invisible until it attacks or is bathed in sunlight.

## Statblock

```ad-statblock
title: Elder Shadow Drake
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Elder%20Shadow%20Drake.webp#token)
*Large dragon, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 114 (`12d10 + 48`)
- **Speed** 20 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|13 (+1)|18 (+4)| 8 (-1)| 9 (-1)|13 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +4, Constitution +7, Charisma +4
- **Skills** Perception +5, Stealth +7
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Vulnerabilities** radiant
- **Damage Immunities** cold
- **Languages** Common, Draconic, Umbral
- **Challenge** 7

## Traits

***Shadow Sight.*** The drake has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks made while in dim light or darkness, and magical darkness doesn't impede the drake's darkvision.

## Actions

***Multiattack.*** The elder shadow drake makes one Bite attack and two Tail Slap attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) piercing damage.

***Tail Slap.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) bludgeoning damage.

***Invisibility.*** The drake magically turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) until it attacks, uses Shadow Step, or starts its turn in sunlight, or until its [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) ends (as if concentrating on a spell). Any equipment the drake wears or carries is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) with it. The drake must be in dim light or darkness to use this action.

***Stygian Breath (Recharge 5-6).*** The elder shadow drake spits a ball of black liquid on a point the dragon can see within 60 feet of it. The ball bursts into a 20-foot-radius sphere of black mist centered on that point for 1 minute. Each creature in the mist when it appears must make a DC 15 Constitution saving throw, taking `dice:12d6|noform|avg|text(42)` (`12d6`) cold damage on a failed save, or half as much damage on a successful one. The mist spreads around corners, and its area is magical darkness. No natural light can illuminate the mist. If any of the mist overlaps with an area of light created by a spell of 1st level or lower, the spell creating the light is dispelled.

## Bonus Actions

***Shadow Step.*** The drake teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see. The origin and destination spaces must be in dim light or darkness.
```
^statblock

## Environment

forest, underdark