---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
aliases: ["Giant Whirlwyrm"]
---
# Giant Whirlwyrm
*Source: Turn of Fortune's Wheel p. 55*  

```ad-statblock
title: Giant Whirlwyrm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/Giant%20Whirlwyrm.webp#token)
*Huge monstrosity, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 168 (`16d12 + 64`)
- **Speed** 50 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|16 (+3)|18 (+4)| 7 (-2)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +6, Stealth +7
- **Senses** darkvision 90 ft., passive Perception 16
- **Damage Immunities** lightning
- **Languages** Draconic
- **Challenge** 11

## Actions

***Multiattack.*** The whirlwyrm makes two attacks: one with its bite and one to constrict.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) piercing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one Large or smaller creature. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) bludgeoning damage plus `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) slashing damage. The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16) if the whirlwyrm isn't already constricting a creature, and the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until this grapple ends.

***Thunder Breath (Recharge 5-6).*** The whirlwyrm exhales a line of thunder that is 20 feet long and 5 feet wide. Each creature in that line must make a DC 16 Dexterity saving throw, taking `dice:12d10|noform|avg|text(66)` (`12d10`) thunder damage on a failed save, or half as much damage on a successful one.

***Swallow.*** The whirlwyrm makes one bite attack against a Medium or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the whirlwyrm, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the whirlwyrm's turns. A whirlwyrm can have only one creature swallowed at a time.

If the whirlwyrm takes 30 damage or more on a single turn from the swallowed creature, the whirlwyrm must succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the whirlwyrm. If the whirlwyrm dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock