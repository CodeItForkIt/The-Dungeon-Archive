---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/3
- monster/size/large
- monster/type/beast
aliases: ["Serpopard"]
---
# Serpopard
*Source: Plane Shift: Amonkhet p. 37*  

Serpopards are strange felines with serpentine features, including long, flexible bodies, venomous fangs, and sensitive tongues they can use to detect the scent of prey from a great distance. They like to perch in trees near desert oases or along the Luxa river, inside the Hekma, to drop down on creatures that come near the water.

## The Desert Lands

The desolate wilderness beyond the protection of the Hekma is largely uncharted. Immediately beyond the protective veil is a chaotic dune sea called Shefet, the Scouring Sands. The desert wears away at the edges of the fertile lands surrounding Naktamun, serving as a constant reminder that only the bounty and protection of the God-Pharaoh stand between the people of the city-state and a grisly death in the sands beyond. Beyond Shefet are parched, cracked expanses called Ramunap, the Broken Lands. The ruins of ancient civilizations are said to lie in the Broken Lands, though no one has ever explored such ruins and returned to Naktamun to tell of them.

## Statblock

```ad-statblock
title: Serpopard
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Serpopard.webp#token)
*Large beast, Unaligned*

- **Armor Class** 12
- **Hit Points** 52 (`7d10 + 14`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|15 (+2)| 3 (-4)|12 (+1)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +3, Stealth +6
- **Senses** passive Perception 13
- **Languages** —
- **Challenge** 3

## Traits

***Keen Smell.*** The serpopard has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks that rely on smell.

***Pounce.*** If the serpopard moves at least 20 feet straight toward a creature and then hits it with a bite attack on the same turn, that target must succeed on a DC 14 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the target is [prone](2-Mechanics/CLI/rules/conditions.md#Prone), the serpopard can make one bite attack against it as a bonus action.

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) piercing damage, and the target must make a DC 14 Constitution saving throw, taking `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock