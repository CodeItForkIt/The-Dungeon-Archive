---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/arctic
- monster/size/large
- monster/type/elemental
aliases: ["Rime Worm"]
---
# Rime Worm
*Source: Tome of Beasts 1 (2023 Edition) p. 308*  

*The long, crusty slug sparkles like ice, and long tendrils dangle from its gaping mouth.*

## Ice Burrowers

The rime worm's tendrils help it burrow through ice and snow as well as absorb sustenance from prey. Their pale, almost translucent, skin is coated with ice crystals, making them difficult to spot in their snowy habitat.

## Spray Black Ice

The worms are fierce hunters, and their abilities to spray skewers of ice and freeze their prey make them extremely dangerous.

## Statblock

```ad-statblock
title: Rime Worm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Rime%20Worm.webp#token)
*Large elemental, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 114 (`12d10 + 48`)
- **Speed** 30 ft., burrow 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|19 (+4)| 6 (-2)|14 (+2)| 3 (-4)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Stealth +5
- **Senses** darkvision 120 ft., passive Perception 12
- **Damage Immunities** cold
- **Languages** —
- **Challenge** 6

## Traits

***Amphibious.*** The rime worm can breathe air and water.

***Icy Body.*** A creature that touches the rime worm or hits it with a melee attack while within 5 feet of it takes `dice:1d8|noform|avg|text(4)` (`1d8`) cold damage.

***Snow Camouflage.*** The rime worm has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in snowy terrain.

***Snow Stride.*** The rime worm can burrow through nonmagical snow and ice in addition to sand, earth, and mud. In addition, difficult terrain composed of snow or ice doesn't cost it extra movement.

## Actions

***Multiattack.*** The rime worm makes two Rime Tendril attacks. It can replace one attack with a use of Freeze Prey.

***Rime Tendril.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) bludgeoning damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) cold damage. The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15) if it is a Medium or smaller creature and the rime worm doesn't have another creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).

***Freeze Prey.*** One creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by the rime worm must succeed on a DC 15 Constitution saving throw or be [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) in ice for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) creature that takes fire damage has advantage on the saving throw.

***Black Ice Spray (Recharge 5-6).*** The rime worm sprays slivers of ice in a 30-foot cone. Each creature in the area must make a DC 15 Constitution saving throw, taking `dice:8d8|noform|avg|text(36)` (`8d8`) cold damage on a failed save, or half as much damage on a successful one. The area then becomes icy, difficult terrain for 1 minute.
```
^statblock

## Environment

arctic