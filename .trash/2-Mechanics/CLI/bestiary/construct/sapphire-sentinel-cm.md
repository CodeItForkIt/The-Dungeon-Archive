---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/10
- monster/size/large
- monster/type/construct
aliases: ["Sapphire Sentinel"]
---
# Sapphire Sentinel
*Source: Candlekeep Mysteries p. 201*  

Stone golems are magical constructs cut and chiseled from stone to appear as tall, impressive statues. Like other golems, they are nearly impervious to spells and ordinary weapons. The golem remains a noncombatant unless it is directly attacked.

## The Sapphire

The sapphire is inside the golem's chest, hidden behind an 9-inch-diameter stone disk. The outer surface of the disk is inscribed with a blue circle that has eight golden beams radiating from it like the rays of the sun.

The disk can be removed to reveal the glowing sapphire only when the golem receives a command to use its power from someone whose commands it obeys. Otherwise, the sapphire remains hidden. The gemstone is 6 inches in diameter and has the following properties:

- It is indestructible until the golem completes its mission.  
- The sapphire has 3 charges. As an action, the golem can expend 1 charge to cast [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md) (as a 9th-level spell) from the sapphire using Constitution as its spellcasting ability. The sapphire ceases to glow if all its charges are expended, but it regains `dice:1d3|noform|avg` (`1d3`) expended charges daily at dawn and glows again once it has 1 or more charges.  
- The golem attacks anyone who tries to remove the sapphire, which is worth 25,000 gp.  

## Statblock

```ad-statblock
title: Sapphire Sentinel
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Sapphire%20Sentinel.webp#token)
*Large construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 178 (`17d10 + 85`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)| 9 (-1)|20 (+5)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common but can't speak
- **Challenge** 10

## Traits

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The golem's weapon attacks are magical.

## Actions

***Multiattack.*** The golem makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) bludgeoning damage.

***Slow (Recharge 5-6).*** The golem targets one or more creatures it can see within 10 feet of it. Each target must make a DC 17 Wisdom saving throw against this magic. On a failed save, a target can't use reactions, its speed is halved, and it can't make more than one attack on its turn. In addition, the target can take either an action or a bonus action on its turn, not both. These effects last for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Sapphire.*** The sapphire has 3 charges. As an action, the golem can expend 1 charge to cast [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md) (as a 9th-level spell) from the sapphire using Constitution as its spellcasting ability. The sapphire ceases to glow if all its charges are expended, but it regains `dice:1d3|noform|avg` (`1d3`) expended charges daily at dawn and glows again once it has 1 or more charges.
```
^statblock