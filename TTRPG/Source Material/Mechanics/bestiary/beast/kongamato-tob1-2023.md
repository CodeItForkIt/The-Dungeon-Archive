---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/forest
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Kongamato"]
---
# [Kongamato](Mechanics\bestiary\beast/kongamato-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 247*  

*This large pterodactyl has emergent feathers and a long, beaklike jaw.*

## Boat Breaker

The kongamato's name means "breaker of boats," and, as that implies, it delights in systematically destroying the small vessels of those who come too close to its perch. No one knows what motivates this form of attack, although some sages suppose that the kongamato mistakes canoes for large prey like hippopotamuses or crocodiles.

## Spoken in Whispers

For some tribes, kongamatos present a terrible threat, and the villagers speak only in whispers about them, fearing that mention of the beasts could attract their wrath. In some cases, evil priests and cultists summon these beasts as their servitors and use them to terrify villagers.

## Maneaters

Kongamatos that have eaten human flesh develop a preference for it. These maneaters perform nightly raids on small towns, snatching locals in their claws and flying away.

```statblock
"name": "Kongamato (ToB1-2023)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "17d10 + 34"
"stats":
- !!int "19"
- !!int "18"
- !!int "14"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "10 ft., fly 60 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "6"
"traits":
- "desc": "The kongamato deals double damage to objects and structures made of wood\
    \ or lighter materials."
  "name": "Breaker of Boats"
- "desc": "The kongamato can fly at half its flying speed when dragging two creatures\
    \ it has [grappled](Mechanics/Rules/conditions.md#Grappled) or at its full flying\
    \ speed if dragging only one creature it has [grappled](Mechanics/Rules/conditions.md#Grappled)."
  "name": "Carry Off"
- "desc": "The kongamato doesn't provoke opportunity attacks when it flies out of\
    \ an enemy's reach."
  "name": "Flyby"
"actions":
- "desc": "The kongamato makes one Beak attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d10 + 4) piercing damage."
  "name": "Beak"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) slashing damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 15) if it is a Medium or smaller creature. The kongamato has two\
    \ claws, each of which can grapple only one target."
  "name": "Claw"
- "desc": "The kongamato releases a screech in a 30-foot cone. Each creature in the\
    \ area must make a DC 15 Constitution saving throw. On a failure, a creature takes\
    \ 28 (8d6) thunder damage and is [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ until the end of its next turn. On a success, a creature takes half the damage\
    \ and isn't [frightened](Mechanics/Rules/conditions.md#Frightened)."
  "name": "Terrifying Screech (Recharge 5-6)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Kongamato.webp"
```
^statblock

## Environment

forest