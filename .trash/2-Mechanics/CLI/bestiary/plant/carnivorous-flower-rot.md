---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/rot
- monster/cr/5
- monster/size/large
- monster/type/plant
aliases: ["Carnivorous Flower"]
---
# Carnivorous Flower
*Source: The Rise of Tiamat p. 67, Tyranny of Dragons p. 153*  

```ad-statblock
title: Carnivorous Flower
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/RoT/Carnivorous%20Flower.webp#token)
*Large plant, Neutral*

- **Armor Class** 14 (natural armor)
- **Hit Points** 114 (`12d10 + 48`)
- **Speed** 0 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|11 (+0)|19 (+4)| 6 (-2)|13 (+1)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +7
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 11
- **Languages** Otyugh
- **Challenge** 5

## Traits

***Limited Telepathy.*** The plant can magically transmit simple messages and images to any creature within 120 feet of it that can understand a language. This form of telepathy doesn't allow the receiving creature to telepathically respond.

## Actions

***Multiattack.*** The plant makes three attacks: one with its bite and two with its tentacles.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) piercing damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw against disease or become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the disease is cured. Every 24 hours that elapse, the target must repeat the saving throw, reducing its hit point maximum by `dice:1d10|noform|avg|text(5)` (`1d10`) on a failure. The disease is cured on a success. The target dies if the disease reduces its hit point maximum to 0. This reduction to the target's hit point maximum lasts until the disease is cured.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 10 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) bludgeoning damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) piercing damage. If the target is Medium or smaller, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the grapple ends. The plant has two tentacles, each of which can grapple one target.

***Tentacle Slam.*** The plant slams creatures [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it into each other or a solid surface. Each creature must succeed on a DC 14 Constitution saving throw or take `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage and be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of the plant's next turn. On a successful save, the target takes half the bludgeoning damage and isn't [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned).
```
^statblock