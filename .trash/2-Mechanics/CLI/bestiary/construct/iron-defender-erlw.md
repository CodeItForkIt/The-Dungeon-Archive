---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/1
- monster/size/medium
- monster/type/construct
aliases: ["Iron Defender"]
---
# Iron Defender
*Source: Eberron: Rising from the Last War p. 293*  

An iron defender fights for its creator. They come in many shapes and are often crafted in the form of animals. More creative artificers craft iron defenders in the shape of hybrid animals or other fantastical creatures.

## Constructed Nature

A homunculus doesn't require air, food, drink, or sleep.

A homunculus is a construct servant created for certain tasks. Artificers and wizards are responsible for most of the homunculi in existence.

Each kind of homunculus has a body constructed from different kinds of materials, including clay, iron, and bits of hair and feathers. The process that creates a homunculus sees those materials mixed with the creator's blood and animated through an extended magical ritual.

## Statblock

```ad-statblock
title: Iron Defender
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Iron%20Defender.webp#token)
*Medium construct, Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 30 (`4d8 + 12`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|16 (+3)| 8 (-1)|11 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Stealth +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 1

## Traits

***Keen Senses.*** The defender has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks.

***Telepathic Bond.*** While the defender is on the same plane of existence as its master, it can magically convey what it senses to its master, and the two can communicate telepathically.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or take an extra `dice:1d6|noform|avg|text(3)` (`1d6`) piercing damage and be [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 13). The defender can have only one creature [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) in this way at a time.
```
^statblock