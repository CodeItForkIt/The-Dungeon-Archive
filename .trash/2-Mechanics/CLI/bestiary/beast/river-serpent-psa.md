---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/2
- monster/size/huge
- monster/type/beast
aliases: ["River Serpent"]
---
# River Serpent
*Source: Plane Shift: Amonkhet p. 38*  

The Luxa river is an abundant source of life, fertilizing the lush valley around Naktamun and providing water to humanoids and animals alike. It is also a vibrant habitat for countless creatures, including many species of birds, fish, and frogs. [Crocodiles](2-Mechanics/CLI/bestiary/beast/crocodile.md) and [hippopotamuses](2-Mechanics/CLI/bestiary/beast/hippopotamus-psa.md) can be a danger to boats and barges, but perhaps the most feared denizens of the river are the [giant serpents](2-Mechanics/CLI/bestiary/monstrosity/giant-river-serpent-psa.md) known to lurk near its bottom. When roused to anger, they can sink fishing boats by the dozens and flood the shore.

Monsters found in the river include fish such as [quippers](2-Mechanics/CLI/bestiary/beast/quipper.md), [giant frogs](2-Mechanics/CLI/bestiary/beast/giant-frog.md), and [crocodiles](2-Mechanics/CLI/bestiary/beast/crocodile.md).

River serpents range from fairly mundane specimens that resemble [giant constrictor snakes](2-Mechanics/CLI/bestiary/beast/giant-constrictor-snake.md) to more monstrous versions with the statistics of a [behir](2-Mechanics/CLI/bestiary/monstrosity/behir.md) (but without lightning immunity or lightning breath).

```ad-statblock
title: River Serpent
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/River%20Serpent.webp#token)
*Huge beast, Unaligned*

- **Armor Class** 12
- **Hit Points** 60 (`8d12 + 8`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|14 (+2)|12 (+1)| 1 (-5)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +2
- **Senses** blindsight 10 ft., passive Perception 12
- **Languages** —
- **Challenge** 2

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 10 ft., one creature. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the creature is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the serpent can't constrict another target.
```
^statblock