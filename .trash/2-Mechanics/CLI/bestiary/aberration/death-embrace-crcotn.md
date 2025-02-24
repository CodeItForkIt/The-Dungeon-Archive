---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/11
- monster/size/huge
- monster/type/aberration
aliases: ["Death Embrace"]
---
# Death Embrace
*Source: Critical Role: Call of the Netherdeep p. 197*  

Drifting through the dark waters of the Netherdeep, the death embrace is an ominous sight. Beneath its bell hangs a lacy, tendrilous mass that thrums with magic, surrounded by six 60-foot-long, barbed tentacles. The death embrace uses these tentacles to grasp and petrify its prey.

Despite its foreboding name, the death embrace is not an overly aggressive creature. It prefers to bide its time, using creatures it has caught in its tentacles as shields to absorb attacks.

```ad-statblock
title: Death Embrace
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Death%20Embrace.webp#token)
*Huge aberration, typically  Chaotic Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 147 (`14d12 + 56`)
- **Speed** 0 ft., swim 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|15 (+2)|19 (+4)| 6 (-2)| 9 (-1)| 4 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +10, Wisdom +3
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 9
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 11

## Traits

***Petrifying Tendrils.*** Any creature that starts its turn in the death embrace's space must make a DC 16 Constitution saving throw. On a failed saving throw, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). A creature [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) in this way must repeat the saving throw at the end of its next turn, becoming [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) on a failed saving throw or ending the effect on a successful one. The [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified) condition lasts until the effect is ended by a greater restoration spell or similar magic.

***Reel.*** At the start of each of its turns, the death embrace can pull each creature it is grappling up to 20 feet toward it (no action required).

***Water Breathing.*** The death embrace can breathe only underwater.

## Actions

***Multiattack.*** The death embrace makes two Tentacle attacks.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 60 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage. If the target is Large or smaller, it is also [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). The death embrace has six tentacles, each of which can grapple one target.

## Reactions

***Body Shield.*** When the death embrace is hit by an attack, one creature the death embrace is grappling (chosen by the death embrace) takes the damage instead.
```
^statblock