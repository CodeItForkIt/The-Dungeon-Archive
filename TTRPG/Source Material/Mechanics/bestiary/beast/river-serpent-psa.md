---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/2
- monster/size/huge
- monster/type/beast
statblock: inline
aliases: ["River Serpent"]
---
# [River Serpent](Mechanics\bestiary\beast/river-serpent-psa.md)
*Source: Plane Shift: Amonkhet p. 38*  

The Luxa river is an abundant source of life, fertilizing the lush valley around Naktamun and providing water to humanoids and animals alike. It is also a vibrant habitat for countless creatures, including many species of birds, fish, and frogs. [Crocodiles](Mechanics/bestiary/beast/crocodile.md) and [hippopotamuses](Mechanics/bestiary/beast/hippopotamus-psa.md) can be a danger to boats and barges, but perhaps the most feared denizens of the river are the [giant serpents](Mechanics/bestiary/monstrosity/giant-river-serpent-psa.md) known to lurk near its bottom. When roused to anger, they can sink fishing boats by the dozens and flood the shore.

Monsters found in the river include fish such as [quippers](Mechanics/bestiary/beast/quipper.md), [giant frogs](Mechanics/bestiary/beast/giant-frog.md), and [crocodiles](Mechanics/bestiary/beast/crocodile.md).

River serpents range from fairly mundane specimens that resemble [giant constrictor snakes](Mechanics/bestiary/beast/giant-constrictor-snake.md) to more monstrous versions with the statistics of a [behir](Mechanics/bestiary/monstrosity/behir.md) (but without lightning immunity or lightning breath).

```statblock
"name": "River Serpent (PSA)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "60"
"hit_dice": "8d12 + 8"
"stats":
- !!int "19"
- !!int "14"
- !!int "12"
- !!int "1"
- !!int "10"
- !!int "3"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "blindsight 10 ft., passive Perception 12"
"languages": ""
"cr": "2"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one creature. Hit:\
    \ 11 (2d6 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 13\
    \ (2d8 + 4) bludgeoning damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 16). Until this grapple ends, the creature is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the serpent can't constrict another target."
  "name": "Constrict"
"source":
- "PSA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/River%20Serpent.webp"
```
^statblock