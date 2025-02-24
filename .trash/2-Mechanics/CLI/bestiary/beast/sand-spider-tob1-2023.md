---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/badlands
- monster/environment/desert
- monster/environment/grassland
- monster/size/large
- monster/type/beast
aliases: ["Sand Spider"]
---
# Sand Spider
*Source: Tome of Beasts 1 (2023 Edition) p. 346*  

*Two speckled, tan legs erupt from the sand, plunging forward with murderous speed. The legs are quickly followed by the body of a large, orange and tan furred spider.*

## Drag Prey into Tunnels

Sand spiders lurk beneath the arid plains and dry grasslands. These carnivores hunt desert dwellers and plains travelers by burrowing into loose sand so they are completely hidden from view. When prey walks over their trap, the spider lunges up from hiding, snares the prey, and drags it down beneath the sand, where it can wrap the prey in webbing before quickly stabbing it to death.

## Spider Packs

More terrifying than a lone sand spider is a group of sand spiders hunting together. They build connected lair networks called clusters, containing one female and two or three males. They work together with one sand spider attacking to draw attention, and the others attacking from trapdoors in the opposite direction, behind the skirmish line.

## Statblock

```ad-statblock
title: Sand Spider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Sand%20Spider.webp#token)
*Large beast, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 135 (`18d10 + 36`)
- **Speed** 30 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|17 (+3)|14 (+2)| 4 (-3)|12 (+1)| 4 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +6
- **Senses** darkvision 60 ft., tremorsense 60 ft., passive Perception 14
- **Languages** —
- **Challenge** 7

## Traits

***Sand Camouflage.*** The sand spider has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made to hide in sandy terrain.

## Actions

***Multiattack.*** The sand spider makes one Bite attack and two Impaling Leg attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage.

***Impaling Leg.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage. If the target is a Medium or smaller creature, it must succeed on a DC 16 Strength saving throw or be [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and takes `dice:2d6|noform|avg|text(7)` (`2d6`) piercing damage at the start of each of its turns, and the sand spider can't use the same Impaling Leg on another target. The sand spider has four Impaling Legs.

## Reactions

***Trapdoor Ambush.*** When the sand spider is burrowed just below the surface of sand and a Medium or smaller creature enters the space on the surface just above where it is burrowed, the sand spider makes one Impaling Leg attack against the creature, bursting from the sand and revealing itself in the process. The target has disadvantage on the saving throw to avoid being [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled).
```
^statblock

## Environment

badlands, desert, grassland