---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/forest
- monster/size/medium
- monster/type/plant
aliases: ["Vine Lord"]
---
# Vine Lord
*Source: Tome of Beasts 1 (2023 Edition) p. 388*  

*Covered with dark green bark and twining tendrils, this longlimbed humanoid exudes a palpable aura of horror.*

## Melding of Flesh and Vine

Vine lords are formed from the union of a vine-infested humanoid and the force-grown descendants of plantfolk. Their servants include most plant creatures, including the tendril puppets the vine lord creates.

## Walking Forests

Vine lords seek to expand and empower forests and jungles in the service of their patron gods and demons or simply to expand their own power. In many cases, they compel trees to walk into grasslands or plowed fields on moonless nights, claiming that territory for the trees.

## Plant Servants

Over time, a vine lord eventually commands a small army of plant creatures, fey, and even plant-based undead, such as vine troll skeletons, to enact its will. When no other allies present themselves, vine lords turn to creating tendril puppets by planting vine roots into humanoids. The vines eventually kill and animate the humanoids, which become mindless servants and expendable scouts. The puppets are connected to each other and the vine lord through a magical "root mind" that relays information almost instantaneously.

> [!note] Vine Lords in Midgard
> 
> Vine lords owe much of their parentage to the Kijani, the original inhabitants of Kush. They are agents of the Green Walker, working to spread the Living Jungle beyond its current borders. Vine lords marshal jungle denizens to fight for them as tendril puppets, and they often entice druid circles with promises of great power.
^vine-lords-in-midgard

## Statblock

```ad-statblock
title: Vine Lord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Vine%20Lord.webp#token)
*Medium plant, Lawful Neutral*

- **Armor Class** 16 (natural armor)
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|20 (+5)|16 (+3)|14 (+2)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +7, Wisdom +7, Charisma +8
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 13
- **Damage Vulnerabilities** fire
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened)
- **Languages** Common, Sylvan
- **Challenge** 9

## Traits

***Green Regeneration.*** While in a forest, the vine lord regains 10 hp at the start of its turn if it hast at least 1 hp.

***Magic Resistance.*** The vine lord has advantage on saving throws against spells and other magical effects.

***Root Mind.*** The vine lord and the tendril puppets it has created are connected via a hive mind. The vine lord and its puppets can telepathically communicate with each other, provided the communicating creatures are within 1 mile of each other. In addition, while in a forest, the vine lord can't be surprised.

***Vine Seed.*** A creature infected with a vine lord's vine seed suffers near-constant pain as the seed takes root and spreads tendrils throughout its body. For the first 24 hours after infection, the creature has disadvantage on attack rolls and ability checks, as the pain from the spreading roots distracts it. Then, the seed becomes a disease, devouring the creature from the inside as it grows vines throughout the creature's body. Until the disease is cured, the infected creature can't regain hp, and its hp maximum decreases by `dice:2d6|noform|avg|text(7)` (`2d6`) for every 24 hours that elapse. This reduction lasts until the disease is cured. The creature dies if this disease reduces its hp maximum to 0.

This potent disease can be cured only by the [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell or similar magic. Alternatively, a creature can take 10 minutes and remove the growing seed from the infected creature within the first 24 hours of infection by succeeding on a DC 16 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check. A Humanoid slain by this disease rises 24 hours later as a tendril puppet under the vine lord's control.

***Woodland Walk.*** Difficult terrain composed of plants doesn't cost the vine lord extra movement. In addition, it can pass through plants without being slowed by them and without taking damage from them if they have thorns, spines, or a similar hazard.

## Actions

***Multiattack.*** The vine lord makes one Tendril attack and two Thorned Slam attacks.

***Tendril.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:1d4+5|noform|avg|text(7)` (`1d4 + 5`) slashing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage, and the target must succeed on a DC 16 Constitution saving throw or become infected with a vine seed (see the Vine Seed trait).

***Thorned Slam.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) bludgeoning damage plus `dice:4d4|noform|avg|text(10)` (`4d4`) piercing damage.

***Forest Protectors (1/Day).*** The vine lord magically calls `dice:1d4|noform|avg` (`1d4`) awakened trees or tendril puppets, or it calls 1 Plant with a challenge rating of 4 or lower. The called creatures arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of the vine lord and obeying its spoken commands. The Plants remain for 1 hour, until the vine lord dies, or until the vine lord dismisses them as a bonus action.
```
^statblock

## Environment

forest