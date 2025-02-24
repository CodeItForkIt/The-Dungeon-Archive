---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/forest
- monster/environment/planar
- monster/size/large
- monster/type/monstrosity
statblock: inline
aliases: ["Shadhavar"]
---
# [Shadhavar](Mechanics\bestiary\monstrosity/shadhavar-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 323*  

*The gray unicorn appears desiccated with its skeleton clearly visible beneath its taut flesh. A haunting melody surrounds it.*

## Shadow Horses

Shadhavar are natives of the Plane of Shadow. Although they resemble undead unicorns, they are living creatures imbued with shadow essences.

## Fey and Undead Riders

While the shadhavar are intelligent creatures, they sometimes serve as mounts for the shadow fey, noctiny, hobgoblins, wights, or other creatures. They expect to be treated well during such an arrangement; more than one unkind rider has ridden off on a shadhavar and never returned.

## Deceptive Hunters

Shadhavar use their hollow horn to play captivating sounds for defense or to draw in prey. They hunt when they must and are not discriminating about their quarry, but shadhavar primarily eat carrion. Despite their horrific appearance, they are not naturally evil.

```statblock
"name": "Shadhavar (ToB1-2023)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d10 + 22"
"stats":
- !!int "14"
- !!int "15"
- !!int "14"
- !!int "8"
- !!int "10"
- !!int "16"
"speed": "50 ft."
"skillsaves":
  "Stealth": !!int "4"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "understands Elvish and Umbral but can't speak"
"cr": "2"
"traits":
- "desc": "The shadhavar's Gore attacks are magical."
  "name": "Magic Horn"
- "desc": "Magical darkness doesn't impede the shadhavar's darkvision."
  "name": "Shadesight"
"actions":
- "desc": "The shadhavar makes one Gore attack and one Hooves attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage."
  "name": "Gore"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) bludgeoning damage."
  "name": "Hooves"
- "desc": "A 15-foot radius of magical darkness extends out from the shadhavar, moves\
    \ with it, and spreads around corners. The darkness lasts as long as the shadhavar\
    \ maintains [concentration](Mechanics/Rules/conditions.md#Concentration), up to\
    \ 10 minutes (as if concentrating on a spell). Darkvision can't penetrate this\
    \ darkness, and no natural light can illuminate it. If any of the darkness overlaps\
    \ with an area of light created by a spell of 2nd level or lower, the spell creating\
    \ the light is dispelled."
  "name": "Darkness Aura (1/Day)"
"bonus_actions":
- "desc": "The shadhavar plays a captivating melody through its hollow horn. Each\
    \ creature within 60 feet of the shadhavar that can hear it must succeed on a\
    \ DC 13 Wisdom saving throw or be [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ until the start of the shadhavar's next turn. While [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ a creature is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated),\
    \ its speed is reduced to 0, and the shadhavar has advantage on attack rolls against\
    \ it."
  "name": "Plaintive Melody (3/Day)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Shadhavar.webp"
```
^statblock

## Environment

forest, planar