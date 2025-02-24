---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/grassland
- monster/environment/planar
- monster/size/tiny
- monster/type/elemental
aliases: ["Spark"]
---
# Spark
*Source: Tome of Beasts 1 (2023 Edition) p. 337*  

*This mote of electrical energy floats menacingly, erupting in a shower of sparks and tendrils of lightning. When it disappears, it leaves only the whiff of ozone.*

## Born in Storms

When a great storm rips across a world in the Material Plane, it sometimes tears loose the fabric of reality, releasing sentient creatures composed entirely of elemental energy. Occasionally when a spark forms, an oppositely charged mate is created at the same time. When this happens, the two always stay within 300 feet of one another.

## Seek Hosts

Fueled by its frenetic thought patterns and erratic actions, a spark jolts through its new world to find a physical body, drawn by an urge to know form. Some spellcasters deliberately seek out sparks for symbiosis. Spellcasters devoted to deities or study of the elements may reach an agreement with sparks, allowing the elementals to ride within their bodies for the sparks' lifetime. Sparks rarely survive longer than a year, even within a symbiotic relationship with a mortal form. When they expire, they wink out and return to the elemental planes.

## Statblock

```ad-statblock
title: Spark
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Spark.webp#token)
*Tiny elemental, Chaotic Neutral*

- **Armor Class** 15
- **Hit Points** 104 (`16d4 + 64`)
- **Speed** 10 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 (-3)|20 (+5)|18 (+4)|10 (+0)|12 (+1)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +8
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Common, Primordial
- **Challenge** 7

## Traits

***Elemental Nature.*** The spark doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The spark makes three Electric Touch attacks.

***Electric Touch.*** *Melee Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+3|noform|avg|text(16)` (`3d8 + 3`) lightning damage.

***Inhabit.*** One Humanoid that the spark can see within 5 feet of it must succeed on a DC 14 Charisma saving throw or be inhabited by the spark. The spark then disappears, fusing with the target's nervous system, and the target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and loses control of its body. The spark now controls the body but doesn't deprive the target of awareness. The spark can't be targeted by any attack, spell, or other effect, and it retains its alignment, Intelligence, Wisdom, Charisma, immunity to being [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), or [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious), and its Electric Touch attack. It otherwise uses the inhabited target's statistics, but doesn't gain access to the target's knowledge, class features, or proficiencies.

Every 24 hours that elapse, the target must succeed on a DC 14 Constitution saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) lightning damage, and its hp maximum is reduced by that amount. This reduction lasts until the target finishes a long rest after the spark no longer inhabits it. The target dies if this reduces its hp maximum to 0. Each time the spark makes an Electric Touch attack and at the end of each long rest, the target can make a DC 14 Charisma saving throw, expelling the spark on a success. Alternatively, the spark can exit the target's body as a bonus action or can be forced out by an effect like the [protection from energy](2-Mechanics/CLI/spells/protection-from-energy.md) spell. The target is immune to this spark's Inhabit for 24 hours after succeeding on the saving throw or after the spark is expelled.

A willing target retains full function of its body, doesn't need to make a Constitution saving throw every 24 hours, has immunity to lightning damage, and can communicate with the spark telepathically. If the spark inhabits a willing target, it takes its turn at the same time as the target, but the spark can attack only as a reaction to a creature moving within 5 feet of the target or as a reaction to the target attacking a creature within 5 feet of it.
```
^statblock

## Environment

grassland, planar