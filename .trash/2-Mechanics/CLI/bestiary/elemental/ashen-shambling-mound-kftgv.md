---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/kftgv
- monster/cr/5
- monster/size/large
- monster/type/elemental
aliases: ["Ashen Shambling Mound"]
---
# Ashen Shambling Mound
*Source: Keys from the Golden Vault p. 158*  

```ad-statblock
title: Ashen Shambling Mound
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/KftGV/Ashen%20Shambling%20Mound.webp#token)
*Large elemental, Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 20 ft., swim 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 8 (-1)|16 (+3)| 5 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Stealth +2
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 10
- **Damage Resistances** cold
- **Damage Immunities** fire, lightning
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion)
- **Languages** —
- **Challenge** 5

## Traits

***Lightning Absorption.*** Whenever the shambling mound is subjected to lightning damage, it takes no damage and regains a number of hit points equal to the lightning damage dealt.

***Ashen Creature.*** When the shambling mound drops to 0 hit points, it is reduced to a pile of ash, and any equipment it was wearing or carrying falls to the ground.

## Actions

***Multiattack.*** The shambling mound makes two slam attacks. If both attacks hit a Medium or smaller target, the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14), and the shambling mound uses its Engulf on it.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage.

***Engulf.*** The shambling mound engulfs a Medium or smaller creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by it. The engulfed target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and unable to breathe, and it must succeed on a DC 14 Constitution saving throw at the start of each of the mound's turns or take `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage. If the mound moves, the engulfed target moves with it. The mound can have only one creature engulfed at a time.
```
^statblock