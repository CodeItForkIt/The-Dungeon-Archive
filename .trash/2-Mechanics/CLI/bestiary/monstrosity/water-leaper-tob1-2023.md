---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/underwater
- monster/size/large
- monster/type/monstrosity
aliases: ["Water Leaper"]
---
# Water Leaper
*Source: Tome of Beasts 1 (2023 Edition) p. 394*  

*The frogheaded, legless creature with wide, batlike wings opens its gaping maw and shrieks. Its long, sinuous tail whips around it, tipped in a barb dripping with poison.*

## Gliding Wings

The creature has no legs or arms, but it sports a pair of wide, membranous wings. It uses its wings to glide beneath the water and to soar through the air.

## Scourge of Waterways

Water leapers plague fresh lakes and rivers. They prey on animals that come to the water's edge to drink, as well as on fishermen that ply their trade in the water leaper's territory. Stories circulate among fishers of waterways known for broken lines and missing bait. Fishers give these areas a wide berth for fear of water leapers. Desperate or unwary fishers who ignore the warnings are never seen again; drifting, empty boats are the signs of their passing.

## Statblock

```ad-statblock
title: Water Leaper
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Water%20Leaper.webp#token)
*Large monstrosity, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 97 (`13d10 + 26`)
- **Speed** 5 ft., fly 50 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|15 (+2)| 4 (-3)|12 (+1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Stealth +4
- **Senses** darkvision 60 ft., passive Perception 11
- **Languages** —
- **Challenge** 4

## Traits

***Amphibious.*** The water leaper can breathe air and water.

***Underwater Camouflage.*** The water leaper has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made while underwater.

## Actions

***Multiattack.*** The water leaper makes one Bite attack and one Stinger attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) piercing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the water leaper can't Bite another target.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, the creature takes `dice:2d4|noform|avg|text(5)` (`2d4`) poison damage at the start of each of its turns. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Swallow.*** The water leaper makes a Bite attack against a Medium or smaller creature it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the water leaper, and it takes `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage at the start of each of the water leaper's turns. The water leaper can have only one creature swallowed at a time.

If the water leaper takes 15 damage or more on a single turn from the swallowed creature, the leaper must succeed on a DC 12 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 5 feet of the leaper. If the leaper dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 10 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

underwater