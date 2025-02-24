---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
aliases: ["Giant River Serpent"]
---
# Giant River Serpent
*Source: Plane Shift: Amonkhet p. 38*  

The Luxa river is an abundant source of life, fertilizing the lush valley around Naktamun and providing water to humanoids and animals alike. It is also a vibrant habitat for countless creatures, including many species of birds, fish, and frogs. [Crocodiles](2-Mechanics/CLI/bestiary/beast/crocodile.md) and [hippopotamuses](2-Mechanics/CLI/bestiary/beast/hippopotamus-psa.md) can be a danger to boats and barges, but perhaps the most feared denizens of the river are the [giant serpents](2-Mechanics/CLI/bestiary/monstrosity/giant-river-serpent-psa.md) known to lurk near its bottom. When roused to anger, they can sink fishing boats by the dozens and flood the shore.

Monsters found in the river include fish such as [quippers](2-Mechanics/CLI/bestiary/beast/quipper.md), [giant frogs](2-Mechanics/CLI/bestiary/beast/giant-frog.md), and [crocodiles](2-Mechanics/CLI/bestiary/beast/crocodile.md).

River serpents range from fairly mundane specimens that resemble [giant constrictor snakes](2-Mechanics/CLI/bestiary/beast/giant-constrictor-snake.md) to more monstrous versions with the statistics of a [behir](2-Mechanics/CLI/bestiary/monstrosity/behir.md) (but without lightning immunity or lightning breath).

```ad-statblock
title: Giant River Serpent
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Giant%20River%20Serpent.webp#token)
*Huge monstrosity, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 168 (`16d12 + 64`)
- **Speed** 50 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|16 (+3)|18 (+4)| 7 (-2)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +6, Stealth +7
- **Senses** darkvision 90 ft., passive Perception 16
- **Languages** Draconic
- **Challenge** 11

## Actions

***Multiattack.*** The serpent makes two attacks: one with its bite and one to constrict.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+6|noform|avg|text(22)` (`3d10 + 6`) piercing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one Large or smaller creature. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) bludgeoning damage plus `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) slashing damage. The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16) if the serpent isn't already constricting a creature, and the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until this grapple ends.

***Swallow.*** The serpent makes one bite attack against a Medium or smaller target it is grappling. If the attack hits, the target is also swallowed, and the grapple ends. While swallowed, the target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the serpent, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the serpent's turns. A serpent can have only one creature swallowed at a time.

If the serpent takes 30 damage or more on a single turn from the swallowed creature, the serpent must succeed on a DC 14 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the serpent. If the serpent dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 15 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock