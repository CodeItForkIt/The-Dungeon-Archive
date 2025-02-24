---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/12
- monster/environment/forest
- monster/size/gargantuan
- monster/type/beast
aliases: ["Titanoboa"]
---
# Titanoboa
*Source: Tome of Beasts 1 (2023 Edition) p. 363*  

*This titanic green serpent raises its enormous head high, its body extending in seemingly endless coils.*

## Territorial and Aggressive

Territorial and voracious, the rare titanoboa devours all trespassers in its domain. Stronger and faster than the giant anaconda, the true king of the rainforest is also more stubborn, fighting off entire groups of hunters and poachers. When stalking prey, these great serpents strike from ambush, swallowing even some dinosaurs in one bite.

## Blinding Scales

Against groups of foes, titanoboas trust in their ability to dazzle their enemies with the light reflected from their scales, using this distraction to entwine the stunned foes in crushing coils.

## Slow to Mate

Titanoboas mate rarely. They live for hundreds of years and never stop growing, which makes the need for propagation less urgent. When two titanoboas nest, the result is a brood of a half-dozen smaller snakes. An adult titanoboa is at least 80 feet long and weighs 6,000 pounds or more.

## Statblock

```ad-statblock
title: Titanoboa
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Titanoboa.webp#token)
*Gargantuan beast, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 232 (`15d20 + 75`)
- **Speed** 40 ft., climb 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|10 (+0)|20 (+5)| 3 (-4)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +4, Wisdom +4
- **Skills** Perception +4
- **Senses** blindsight 10 ft., passive Perception 14
- **Languages** —
- **Challenge** 12

## Traits

***Slither.*** If the titanoboa hasn't eaten a Huge creature in the last 24 hours, it can easily move through any open large enough for a Large creature, and it can squeeze through any opening large enough for a Medium creature. The titanoboa's destination must still have suitable room to accommodate its volume.

***Sparkling Scales.*** When a creature that can see the titanoboa starts its turn within 30 feet of the titanoboa and the titanoboa is in bright light, isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), and can see the creature, the titanoboa can force the creature to make a DC 17 Wisdom saving throw. On a failed save, the creature is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the start of its next turn.

Unless surprised, a creature can avert its eyes to avoid the saving throw at the start of its turn. If the creature does so, it can't see the titanoboa until the start of its next turn, when it can avert its eyes again. If the creature looks at the titanoboa in the meantime, it must immediately make the save.

## Actions

***Multiattack.*** The titanoboa makes two Bite attacks or one Bite attack and one Constrict attack. It can replace one Bite attack with a use of Swallow.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:5d8+8|noform|avg|text(30)` (`5d8 + 8`) piercing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft., one target. *Hit:* `dice:4d10+8|noform|avg|text(30)` (`4d10 + 8`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 18) if it is a Huge or smaller creature. Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the titanoboa can't Constrict another target.

***Swallow.*** The titanoboa makes one Bite attack against a Huge or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the titanoboa, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the titanoboa's turns. If the titanoboa takes 30 damage or more on a single turn from a swallowed creature, the titanoboa must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the titanoboa. If the titanoboa dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

forest