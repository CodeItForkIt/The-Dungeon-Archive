---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/7
- monster/size/medium
- monster/type/elemental
aliases: ["Water Elemental Myrmidon"]
---
# Water Elemental Myrmidon
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 123, Mordenkainen's Tome of Foes p. 203*  

## Elemental Myrmidons

Elemental myrmidons are Elementals conjured and bound by magic into ritually created suits of plate armor. In this form, they possess no recollection of their former existence as free Elementals. They exist only to follow the commands of their creators.

```ad-statblock
title: Water Elemental Myrmidon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Water%20Elemental%20Myrmidon.webp#token)
*Medium elemental, Typically  Neutral*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 127 (`17d8 + 51`)
- **Speed** 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|16 (+3)| 8 (-1)|10 (+0)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** acid; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Aquan, one language of its creator's choice
- **Challenge** 7

## Actions

***Multiattack.*** The myrmidon makes three Trident attacks.

***Trident.*** *Melee or Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) force damage, or `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) force damage if used with two hands to make a melee attack.

***Freezing Strikes (Recharge 6).*** The myrmidon uses Multiattack. Each attack that hits deals an extra `dice:1d10|noform|avg|text(5)` (`1d10`) cold damage. A target that is hit by one or more of these attacks has its speed reduced by 10 feet until the end of the myrmidon's next turn.
```
^statblock