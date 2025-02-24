---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1
- monster/environment/forest
- monster/environment/swamp
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Wampus Cat"]
---
# [Wampus Cat](Mechanics\bestiary\monstrosity/wampus-cat-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 392*  

*A raven-haired young woman rises to the surface of the water as she swims, singing softly to herself. Her lower body is revealed to be that of a mountain lion, and her sweet song suddenly turns to a yowl of rage.*

Wampus cats are all born from an ancient shaman's curse. Trollkin, orc, goblin, and human shamans alike all claim to be able to transform those who practice forbidden magic into wampus cats.

## Forest Streams

The wampus cat stalks the shores of woodland waterways, using her magic to disguise her true form and lure unsuspecting victims to the water's edge. She is particularly fond of attacking bathers or those pulling water from a stream.

## Hatred of the Holy

While she prefers to feast on intelligent male humanoids, she holds special animosity toward holy men of any kind. Unless near starvation or if provoked, however, she will not kill women. Indeed, a wampus cat may strike up a temporary friendship with any woman who is having difficulties with men, though these friendships typically last only as long as their mutual enemies live. Some witches are said to gain their trust and keep them as companions.

## Swamp Team Ups

Will-o'-wisps and miremals enjoy working in tandem with wampus cats; the wisps alter their light to mimic the flicker of a torch or candle and illuminate the disguised cat, the better to lure in victims, then assist the cat in the ensuing battle. Miremals use a tall story to lure travelers into a swamp when the hour grows late, then abandon them.

```statblock
"name": "Wampus Cat (ToB1-2023)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "14"
- !!int "18"
- !!int "15"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "40 ft., climb 20 ft., swim 30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Persuasion": !!int "5"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common"
"cr": "1"
"traits":
- "desc": "The wampus cat has advantage on attack rolls against creatures wielding\
    \ divine or celestial power, such as clerics, paladins, or aasimars."
  "name": "Divine Animosity"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claw (True Form Only)"
- "desc": "The wampus cat sings a sweet melody. Each creature within 60 feet of her\
    \ that can hear the song must succeed on a DC 13 Charisma saving throw or be [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success. If a creature's saving throw\
    \ is successful or the effect ends for it, the creature is immune to the wampus\
    \ cat's Sweet Song for the next 24 hours."
  "name": "Sweet Song (Recharge 5-6)"
- "desc": "The wampus cat emits an ear‑piercing yowl. Each creature within 15 feet\
    \ of the wampus cat that can hear the yowl must make a DC 13 Wisdom saving throw.\
    \ On a failure, a creature takes 10 (3d6) thunder damage and is [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ until the end of its next turn. On a success, a creature takes half the damage\
    \ and isn't [frightened](Mechanics/Rules/conditions.md#Frightened)."
  "name": "Terrifying Yowl (Recharge 5-6)"
"bonus_actions":
- "desc": "The wampus cat magically polymorphs into a Medium female Humanoid, or back\
    \ into her true form. Her statistics are the same in each form. Any equipment\
    \ she is wearing or carrying transforms with her. She reverts to her true form\
    \ if she dies."
  "name": "Change Shape"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Wampus%20Cat.webp"
```
^statblock

## Environment

forest, swamp