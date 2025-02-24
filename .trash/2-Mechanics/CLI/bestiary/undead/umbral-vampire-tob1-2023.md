---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/planar
- monster/environment/urban
- monster/size/medium
- monster/type/undead
aliases: ["Umbral Vampire"]
---
# Umbral Vampire
*Source: Tome of Beasts 1 (2023 Edition) p. 382*  

*This deathly pale, gaunt human has stringy hair and wears scant rags. Misty strands of darkness leak from its empty eye sockets, yawning nasal cavity, and mouth.*

## Cursed Origin

Legends speak of an ancient city whose origins are lost to the ages, where a cabal of wizards with the power to manipulate the flow of time made its citizens immortal. When the wizards fell and no longer held back the ravages of time, the citizens aged centuries in moments. Instead of dying, the wretches lingered on in their dark realm.

## Bound to Darkness

All umbral vampires originate in the City Fallen into Shadow, and under most circumstances, they're encountered only in that forsaken place. Despite the terrors it holds, adventurers continue to seek the city, chasing legends of potent artifacts and boundless treasure accumulated during its golden age. Occasionally, an umbral vampire slips into the mortal world, where it hides in a place seldom or never touched by sunlight and emerges at night to search for victims.

## Statblock

```ad-statblock
title: Umbral Vampire
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Umbral%20Vampire.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 14
- **Hit Points** 84 (`13d8 + 26`)
- **Speed** 0 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 (-5)|18 (+4)|15 (+2)|14 (+2)|14 (+2)|19 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Charisma +7
- **Skills** Perception +5, Stealth +7
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Resistances** acid; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Umbral, Void Speech
- **Challenge** 7

## Traits

***Incorporeal Movement.*** The umbral vampire can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Sunlight Sensitivity.*** While in sunlight, the umbral vampire has disadvantage on attack rolls, as well as on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on sight.

***Undead Nature.*** The umbral vampire doesn't require air.

## Actions

***Multiattack.*** The umbral vampire can use its Umbral Grasp. It then makes two Shadow Touch attacks.

***Shadow Touch.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+4|noform|avg|text(17)` (`3d8 + 4`) necrotic damage, and the target's Strength score is reduced by `dice:1d4|noform|avg` (`1d4`). The target dies if this reduces its Strength to 0. Otherwise, the reduction lasts until the target finishes a short or long rest. A non-evil Humanoid slain by this attack rises 24 hours later as a shadow under the vampire's control, unless the Humanoid is restored to life. The vampire can have no more than five shadows under its control at one time.

***Umbral Grasp.*** The umbral vampire sends a giant hand of shadow to grab one creature it can see that is in dim light or darkness within 30 feet of it. The target must succeed on a DC 15 Dexterity saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by wisps of magical shadow for 1 minute. While [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), the target takes `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage at the start of each of its turns. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. The umbral vampire can have no more than two creatures [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by its Umbral Grasp at a time.

## Bonus Actions

***Shadow Stealth.*** While in dim light or darkness, the umbral vampire takes the Hide action.
```
^statblock

## Environment

planar, urban