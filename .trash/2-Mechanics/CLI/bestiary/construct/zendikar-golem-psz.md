---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/10
- monster/size/large
- monster/type/construct
aliases: ["Zendikar Golem"]
---
# Zendikar Golem
*Source: Plane Shift: Zendikar p. 36*  

With the power of magic at their disposal, mages of the ancient past and of Zendikar's present have been able to create objects bearing the semblance of life, capable of carrying out orders and even acting independently.

In a number of ancient sites associated with the Eldrazi, stone creatures have been found standing eternal guard. Created from fragments of hedrons or carved to resemble them, these constructs were intended to help the people of Zendikar eliminate the brood lineages after the titans were imprisoned, and were implanted with a fragment of the power that bound and imprisoned the Eldrazi. They have served as useful allies in battling the Eldrazi broods, and some mages have had limited success in prying the secrets of their magic from their artificial minds. Other hedron constructs are of more recent make, fashioned in imitation of the originals. These have no power over the Eldrazi beyond what their physical strength gives them, and their creators used them for menial tasks. They are most often found in the ancient ruins of the kor or in merfolk cities. The various **modrons** can be used to represent these dedicated constructs.

The golems of Zendikar are effectively artificial elementals, and can be represented by [stone golems](2-Mechanics/CLI/bestiary/construct/stone-golem.md). Mages fashion bodies from special stone and infuse them with the power of movement and limited understanding. Golems are rare and powerful, especially when shaped from stone that already possesses magical power.

```ad-statblock
title: Zendikar Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Zendikar%20Golem.webp#token)
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
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 10

## Traits

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The golem's weapon attacks are magical.

## Actions

***Multiattack.*** The golem makes two slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+6|noform|avg|text(19)` (`3d8 + 6`) bludgeoning damage.

***Slow (Recharge 5-6).*** The golem targets one or more creatures it can see within 10 feet of it. Each target must make a DC 17 Wisdom saving throw against this magic. On a failed save, a target can't use reactions, its speed is halved, and it can't make more than one attack on its turn. In addition, the target can take either an action or a bonus action on its turn, not both. These effects last for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock