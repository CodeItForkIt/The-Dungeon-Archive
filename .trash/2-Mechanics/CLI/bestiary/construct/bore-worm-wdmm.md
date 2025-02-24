---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/16
- monster/size/gargantuan
- monster/type/construct
aliases: ["Bore Worm"]
---
# Bore Worm
*Source: Waterdeep: Dungeon of the Mad Mage p. 171*  

Trobriand modeled this 100-foot-long, 15-foot-diameter drilling machine after a purple worm. Unless Trobriand commands it to do otherwise, the worm tirelessly moves through well-worn tunnels and trenches. It mindlessly attacks anything that gets in its way, and occasionally ventures up to level 12 or down to level 14. Characters hear it long before they see it.

```ad-statblock
title: Bore Worm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Bore%20Worm.webp#token)
*Gargantuan construct, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 247 (`15d20 + 90`)
- **Speed** 50 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)| 7 (-2)|22 (+6)| 1 (-5)| 8 (-1)| 4 (-3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +11, Wisdom +4
- **Skills** ⏤
- **Senses** blindsight 30 ft., tremorsense 60 ft., passive Perception 9
- **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** —
- **Challenge** 16

## Traits

***Tunneler.*** The worm can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.

***Regeneration.*** The worm regains 10 hit points at the start of each of its turns if it has at least 1 hit point.

## Actions

***Multiattack.*** The worm makes two attacks: one with its grinding jaws and one with its stinger.

***Grinding Jaws.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+9|noform|avg|text(22)` (`3d8 + 9`) slashing damage.

***Tail Stinger.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one creature. *Hit:* `dice:3d6+9|noform|avg|text(19)` (`3d6 + 9`) piercing damage, and the target must make a DC 19 Constitution saving throw, taking `dice:12d6|noform|avg|text(42)` (`12d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock