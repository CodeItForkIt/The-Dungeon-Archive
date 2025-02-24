---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/gos
- monster/cr/5
- monster/size/medium
- monster/type/aberration
aliases: ["Skum"]
---
# Skum
*Source: Ghosts of Saltmarsh p. 254*  

Several poor souls around the Styes have succumbed to an aboleth's magic through its disease-bearing touch. Transformed into creatures called skum, they barely resemble their past forms, their skin turning slimy and translucent while their limbs warp to resemble those of deep-sea oddities. The change makes them dependent on water, which they must immerse themselves in regularly lest they experience painful-and potentially lethal-skin eruptions. Skum are bound to their aboleth master not just by their cursed state, but by a psychic bond that compels them to serve its every sinister whim.

```ad-statblock
title: Skum
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Skum.webp#token)
*Medium aberration, Lawful Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 93 (`11d8 + 44`)
- **Speed** 20 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|11 (+0)|18 (+4)| 7 (-2)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4
- **Senses** darkvision 120 ft., passive Perception 14
- **Damage Resistances** psychic
- **Languages** Common, Deep Speech, telepathy 60 ft.
- **Challenge** 5

## Traits

***Abolethic Vassal.*** The skum is permanently [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by its aboleth master.

***Amphibious.*** The skum can breathe air and water.

***Psychic Conditioning.*** The skum is immune to the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) and [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) conditions unless they are from effects created by an aboleth.

***Water Dependency.*** The skum takes `dice:1d12|noform|avg|text(6)` (`1d12`) acid damage every 10 minutes it goes without exposure to water.

## Actions

***Multiattack.*** The skum makes three attacks: two with its trident and one with its Mind-Breaking Touch.

***Trident.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage.

***Mind-Breaking Touch.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:4d8|noform|avg|text(18)` (`4d8`) psychic damage, and the target has disadvantage on Wisdom saving throws until the end of the skum's next turn.
```
^statblock