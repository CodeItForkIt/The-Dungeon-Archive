---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
aliases: ["Gomazoa"]
---
# Gomazoa
*Source: Plane Shift: Zendikar p. 26*  

Zendikar's seas and skies tend to blur together, and creatures typically found in the sea often find their way to the clouds, gliding through the plane's gravitational currents by consuming the mana infused in the wind. The windrider eels hunted by the kor and the cloud mantas sometimes ridden by Emeria-creed merfolk are two examples. The gomazoas found in Murasa and the Makindi Trenches are another.

Gomazoas are similar to aquatic jellyfish, but their bodies are encased in stony growths. A gomazoa drifts motionless among floating rocks or hedrons with its long, sticky tentacles dangling below. When they brush against another creature, those tentacles grab and constrict it, or might slam larger prey against a cliff face. Some species can withdraw their tentacles into their bodies, extending them only to grab their prey. Gomazoas almost never release prey once they've caught it.

A gomazoa might be represented by the [roper](2-Mechanics/CLI/bestiary/monstrosity/roper.md) statistics in the *Monster Manual*, with a flying speed of 10 feet in place of its walking and climbing speeds.

```ad-statblock
title: Gomazoa
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Gomazoa.webp#token)
*Large monstrosity, Neutral Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 93 (`11d10 + 33`)
- **Speed** fly 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 8 (-1)|17 (+3)| 7 (-2)|16 (+3)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 16
- **Languages** —
- **Challenge** 5

## Traits

***False Appearance.*** While the gomazoa remains motionless, it is indistinguishable from a normal cave formation, such as a stalagmite.

***Grasping Tendrils.*** The gomazoa can have up to six tendrils at a time. Each tendril can be attacked (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying a tendril deals no damage to the gomazoa, which can extrude a replacement tendril on its next turn. A tendril can also be broken if a creature takes an action and succeeds on a DC 15 Strength check against it.

***Spider Climb.*** The gomazoa can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The gomazoa makes four attacks with its tendrils, uses Reel, and makes one attack with its bite.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) piercing damage.

***Tendril.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 50 ft., one creature. *Hit:* The target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until the grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and has disadvantage on Strength checks and Strength saving throws, and the gomazoa can't use the same tendril on another target.

***Reel.*** The gomazoa pulls each creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it up to 25 feet straight toward it.
```
^statblock