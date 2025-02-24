---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pota
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
aliases: ["Molten Magma Roper"]
---
# Molten Magma Roper
*Source: Princes of the Apocalypse p. 143*  

```ad-statblock
title: Molten Magma Roper
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PotA/Molten%20Magma%20Roper.webp#token)
*Large monstrosity, Neutral Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 93 (`11d10 + 33`)
- **Speed** 10 ft., climb 10 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 8 (-1)|17 (+3)| 7 (-2)|16 (+3)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6, Stealth +5
- **Senses** darkvision 60 ft., passive Perception 16
- **Damage Vulnerabilities** cold
- **Damage Immunities** fire
- **Languages** —
- **Challenge** 5

## Traits

***False Appearance.*** While the roper remains motionless, it is indistinguishable from a normal cave formation, such as a stalagmite.

***Grasping Tendrils.*** The roper can have up to six tendrils at a time. Each tendril can be attacked (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying a tendril deals no damage to the roper, which can extrude a replacement tendril on its next turn. A tendril can also be broken if a creature takes an action and succeeds on a DC 15 Strength check against it.

***Spider Climb.*** The roper can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The roper makes four attacks with its tendrils, uses Reel, and makes one attack with its bite.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) fire damage.

***Tendril.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 50 ft., one creature. *Hit:* `dice:1d8|noform|avg|text(4)` (`1d8`) fire damage and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until the grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and has disadvantage on Strength checks and Strength saving throws, and the roper can't use the same tendril on another target. A creature takes `dice:1d8|noform|avg|text(4)` (`1d8`) fire damage each time it ends its turn grappled by the roper.

***Reel.*** The roper pulls each creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it up to 25 feet straight toward it.
```
^statblock