---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/13
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Sunbird"]
---
# Sunbird
*Source: Plane Shift: Ixalan p. 32*  

The people of the Sun Empire revere certain dinosaurs as incarnations of the Threefold Sun. But the fiery phoenixes, also called sunbirds, are thought to be messengers of Tilonalli, embodying the destructive aspect of the sun but also the rebirth that follows. Legends hold that somewhere within the mountains sleeps Xuatl—a scaled bird formed from the sun's fire. Xuatl molts its skin and feathers during the summer months, often setting the trees and slopes ablaze.

```ad-statblock
title: Sunbird
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Sunbird.webp#token)
*Gargantuan monstrosity, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 279 (`18d20 + 90`)
- **Speed** 20 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|10 (+0)|20 (+5)|13 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +5, Constitution +10, Wisdom +7, Charisma +7
- **Skills** Perception +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire
- **Languages** Giant Owl, understands Common but can't speak it
- **Challenge** 13

## Traits

***Death Throes.*** When the sunbird dies, it explodes, and each creature within 30 feet of it must make a DC 18 Dexterity saving throw, taking `dice:12d6|noform|avg|text(42)` (`12d6`) fire damage on a failed save, or half as much damage on a successful one. The explosion ignites flammable objects in that area that aren't being worn or carried. The sunbird's body turns to ash, but an egg is left where the sunbird was.

***Fire Aura.*** At the start of each of the sunbird's turns, each creature within 5 feet of it takes `dice:2d10|noform|avg|text(11)` (`2d10`) fire damage, and flammable objects in the area that aren't being worn or carried ignite. A creature that touches the sunbird or hits it with a melee attack while within 5 feet of it takes `dice:2d10|noform|avg|text(11)` (`2d10`) fire damage. The aura also sheds bright light in a 60-foot radius and dim light for an additional 60 feet.

***Flyby.*** The sunbird doesn't provoke opportunity attacks when it flies out of an enemy's reach.

***Keen Hearing and Sight.*** The sunbird has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on hearing or sight.

## Actions

***Multiattack.*** The sunbird makes two talon attacks.

***Talon.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+9|noform|avg|text(16)` (`2d6 + 9`) slashing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) fire damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 18). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the sunbird can't attack another target with that talon. A [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) creature takes `dice:2d10|noform|avg|text(11)` (`2d10`) fire damage at the start of each of the sunbird's turns.
```
^statblock