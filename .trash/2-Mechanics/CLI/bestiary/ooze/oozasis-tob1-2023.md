---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/desert
- monster/size/gargantuan
- monster/type/ooze
aliases: ["Oozasis"]
---
# Oozasis
*Source: Tome of Beasts 1 (2023 Edition) p. 290*  

*The oasis appears as an idyllic desert respite, offering water, shade, and even edible fruit and nuts in the trees above.*

## Mockmire

The oozasis, or oasis ooze, is also known as a mockmire in other climates. It mimics a peaceful, pristine watering hole to draw in unsuspecting prey. An oozasis cycles seemingly at random between activity and dormancy.

## Quest Givers

Within its odd physiology stirs an ancient mind with an inscrutable purpose. Far from being a mindless sludge, its fractured intelligence occasionally reads the thoughts of visitors. At these times, it tries to coerce them into undertaking quests for cryptic reasons.

## Ancient Minds

Some tales claim these creatures preserve the memories of mad wizards from dead empires, or that they have unimaginably ancient, inhuman origins.

## Statblock

```ad-statblock
title: Oozasis
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Oozasis.webp#token)
*Gargantuan ooze, Unaligned*

- **Armor Class** 7
- **Hit Points** 217 (`14d20 + 70`)
- **Speed** 20 ft., burrow 20 ft., swim 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)| 5 (-3)|20 (+5)| 8 (-1)|20 (+5)|13 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +3, Wisdom +9, Charisma +5
- **Skills** Deception +5, History +3, Insight +9, Perception +9
- **Senses** blindsight 120 ft. (blind beyond this radius), passive Perception 19
- **Damage Vulnerabilities** cold
- **Damage Resistances** fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** telepathy 120 ft. understands all languages but can't speak
- **Challenge** 9

## Traits

***Amorphous.*** The oozasis can move through a space as narrow as 1 foot wide without squeezing.

***Oasis Appearance.*** While the oozasis remains motionless and partially submerged on the surface of sand or soil, it is indistinguishable from a small oasis or pond. The oozasis's body provides enough water for plants to grow around it, provided the oozasis remains in the area for an extended period of time. A creature that eats a fruit from a plant growing in the oozasis's water is affected by the Waters of Unfathomable Compulsion trait as if it drank the water.

***Ooze Nature.*** The oozasis doesn't require sleep.

***Waters of Unfathomable Compulsion.*** A creature that drinks the water of an oozasis experiences a cryptic dream the next time it sleeps. When it wakes, it must succeed on a DC 16 Wisdom saving throw or be affected by the [geas](2-Mechanics/CLI/spells/geas.md) spell for 30 days. While under the geas, the affected creature must perform a specific, seemingly minor task that furthers the decades-long goals of the oozasis. Such a task could be planting a white rose in a specific garden, rescuing the next endangered young animal the target encounters, or standing in a specific spot at a certain time each day for three days.

## Actions

***Multiattack.*** The oozasis makes three Pseudopod attacks.

***Pseudopod.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 15 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage. If the target is a Large or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). The oozasis can have up to two creatures [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) at a time.

***Compelling Vapors (Recharge 5-6).*** The oozasis emits mind-altering vapors. Each creature within 20 feet of the oozasis must make a DC 16 Constitution saving throw. On a failure, a creature takes `dice:10d8|noform|avg|text(45)` (`10d8`) psychic damage and suffers either tranquility or turmoil for minute. On a success, a creature takes half the damage and doesn't suffer tranquility or turmoil. A creature suffering tranquility is [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and can't attack. A creature suffering turmoil is unable to distinguish friend from foe and must move to and attack the nearest creature other than the oozasis on each of its turns, stalking off in a random direction if no creature is in range. A creature suffering tranquility or turmoil can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock

## Environment

desert