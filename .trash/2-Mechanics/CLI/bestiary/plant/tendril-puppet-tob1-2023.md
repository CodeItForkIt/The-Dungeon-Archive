---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/forest
- monster/size/medium
- monster/type/plant
aliases: ["Tendril Puppet"]
---
# Tendril Puppet
*Source: Tome of Beasts 1 (2023 Edition) p. 389*  

*Vines crawl across the body and out of the eyes and mouth of this shambling human.*

## Plant Servants

Over time, a vine lord eventually commands a small army of plant creatures, fey, and even plant-based undead, such as vine troll skeletons, to enact its will. When no other allies present themselves, vine lords turn to creating tendril puppets by planting vine roots into humanoids. The vines eventually kill and animate the humanoids, which become mindless servants and expendable scouts. The puppets are connected to each other and the vine lord through a magical "root mind" that relays information almost instantaneously.

## Statblock

```ad-statblock
title: Tendril Puppet
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Tendril%20Puppet.webp#token)
*Medium plant, Lawful Neutral*

- **Armor Class** 13 (natural armor)
- **Hit Points** 51 (`6d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|15 (+2)|18 (+4)| 6 (-2)| 6 (-2)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Damage Vulnerabilities** fire
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened)
- **Languages** understands the languages of its vine lord but can't speak
- **Challenge** 2

## Traits

***Green Regeneration.*** While in a forest, the tendril puppet regains 5 hp at the start of its turn if it has at least 1 hp.

***Root Mind.*** The vine lord and the tendril puppets it has created are connected via a hive mind. The vine lord and its puppets can telepathically communicate with each other, provided the communicating creatures are within 1 mile of each other. In addition, while in a forest, the tendril puppet can't be surprised.

***Magic Resistance.*** The tendril puppet has advantage on saving throws against spells and other magical effects.

***Woodland Walk.*** Difficult terrain composed of nonmagical plants doesn't cost the tendril puppet extra movement, and it can pass through nonmagical plants without being slowed by them and without taking damage from them if they have thorns, spines, or a similar hazard.

## Actions

***Thorned Slam.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) bludgeoning damage plus `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage.

***Ball of Thorns.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 20/60 ft., one target. *Hit:* `dice:4d4+2|noform|avg|text(12)` (`4d4 + 2`) piercing damage, and the ball bursts, scattering sharp thorns around the target. Each creature within 5 feet of the target must succeed on a DC 13 Dexterity saving throw or take `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage.
```
^statblock

## Environment

forest