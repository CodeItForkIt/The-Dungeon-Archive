---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/7
- monster/size/medium
- monster/type/elemental
aliases: ["Air Elemental Myrmidon"]
---
# Air Elemental Myrmidon
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 122, Mordenkainen's Tome of Foes p. 202*  

## Elemental Myrmidons

Elemental myrmidons are Elementals conjured and bound by magic into ritually created suits of plate armor. In this form, they possess no recollection of their former existence as free Elementals. They exist only to follow the commands of their creators.

```ad-statblock
title: Air Elemental Myrmidon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Air%20Elemental%20Myrmidon.webp#token)
*Medium elemental, Typically  Neutral*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 117 (`18d8 + 36`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|14 (+2)| 9 (-1)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Auran, one language of its creator's choice
- **Challenge** 7

## Actions

***Multiattack.*** The myrmidon makes three Flail attacks.

***Flail.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) force damage.

***Lightning Strike (Recharge 6).*** The myrmidon makes one Flail attack. On a hit, the target takes an extra `dice:4d8|noform|avg|text(18)` (`4d8`) lightning damage, and the target must succeed on a DC 13 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of the myrmidon's next turn.
```
^statblock