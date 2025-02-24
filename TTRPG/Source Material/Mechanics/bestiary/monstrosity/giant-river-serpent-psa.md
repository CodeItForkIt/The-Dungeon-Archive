---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
statblock: inline
aliases: ["Giant River Serpent"]
---
# [Giant River Serpent](Mechanics\bestiary\monstrosity/giant-river-serpent-psa.md)
*Source: Plane Shift: Amonkhet p. 38*  

The Luxa river is an abundant source of life, fertilizing the lush valley around Naktamun and providing water to humanoids and animals alike. It is also a vibrant habitat for countless creatures, including many species of birds, fish, and frogs. [Crocodiles](Mechanics/bestiary/beast/crocodile.md) and [hippopotamuses](Mechanics/bestiary/beast/hippopotamus-psa.md) can be a danger to boats and barges, but perhaps the most feared denizens of the river are the [giant serpents](Mechanics/bestiary/monstrosity/giant-river-serpent-psa.md) known to lurk near its bottom. When roused to anger, they can sink fishing boats by the dozens and flood the shore.

Monsters found in the river include fish such as [quippers](Mechanics/bestiary/beast/quipper.md), [giant frogs](Mechanics/bestiary/beast/giant-frog.md), and [crocodiles](Mechanics/bestiary/beast/crocodile.md).

River serpents range from fairly mundane specimens that resemble [giant constrictor snakes](Mechanics/bestiary/beast/giant-constrictor-snake.md) to more monstrous versions with the statistics of a [behir](Mechanics/bestiary/monstrosity/behir.md) (but without lightning immunity or lightning breath).

```statblock
"name": "Giant River Serpent (PSA)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d12 + 64"
"stats":
- !!int "23"
- !!int "16"
- !!int "18"
- !!int "7"
- !!int "14"
- !!int "12"
"speed": "50 ft., climb 40 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "6"
"senses": "darkvision 90 ft., passive Perception 16"
"languages": "Draconic"
"cr": "11"
"actions":
- "desc": "The serpent makes two attacks: one with its bite and one to constrict."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d10 + 6) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one Large or smaller\
    \ creature. Hit: 17 (2d10 + 6) bludgeoning damage plus 17 (2d10 + 6) slashing\
    \ damage. The target is [grappled](Mechanics/Rules/conditions.md#Grappled) (escape\
    \ DC 16) if the serpent isn't already constricting a creature, and the target\
    \ is [restrained](Mechanics/Rules/conditions.md#Restrained) until this grapple\
    \ ends."
  "name": "Constrict"
- "desc": "The serpent makes one bite attack against a Medium or smaller target it\
    \ is grappling. If the attack hits, the target is also swallowed, and the grapple\
    \ ends. While swallowed, the target is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ and [restrained](Mechanics/Rules/conditions.md#Restrained), it has total cover\
    \ against attacks and other effects outside the serpent, and it takes 21 (6d6)\
    \ acid damage at the start of each of the serpent's turns. A serpent can have\
    \ only one creature swallowed at a time.\n\nIf the serpent takes 30 damage or\
    \ more on a single turn from the swallowed creature, the serpent must succeed\
    \ on a DC 14 Constitution saving throw at the end of that turn or regurgitate\
    \ the creature, which falls [prone](Mechanics/Rules/conditions.md#Prone) in a\
    \ space within 10 feet of the serpent. If the serpent dies, a swallowed creature\
    \ is no longer [restrained](Mechanics/Rules/conditions.md#Restrained) by it and\
    \ can escape from the corpse by using 15 feet of movement, exiting [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Swallow"
"source":
- "PSA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Giant%20River%20Serpent.webp"
```
^statblock