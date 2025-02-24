---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/oota
- monster/cr/1
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Spider King"]
---
# [Spider King](Mechanics\bestiary\npc/spider-king-oota.md)
*Source: Out of the Abyss p. 74*  

```statblock
"name": "Spider King (OotA)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "44"
"hit_dice": "4d10 + 4"
"stats":
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "2"
- !!int "11"
- !!int "4"
"speed": "30 ft., climb 30 ft."
"saves":
  "Wisdom": !!int "2"
  "Constitution": !!int "3"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "4"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "1"
"traits":
- "desc": "The spider can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "While in contact with a web, the spider knows the exact location of any\
    \ other creature in contact with the same web."
  "name": "Web Sense"
- "desc": "The spider ignores movement restrictions caused by webbing."
  "name": "Web Walker"
- "desc": "Because of its two heads, the Spider King has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks and on saving throws against being [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [charmed](Mechanics/Rules/conditions.md#Charmed), [deafened](Mechanics/Rules/conditions.md#Deafened),\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [stunned](Mechanics/Rules/conditions.md#Stunned),\
    \ and knocked [unconscious](Mechanics/Rules/conditions.md#Unconscious)."
  "name": "Two Heads"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 7\
    \ (1d8 + 3) piercing damage, and the target must make a DC 11 Constitution saving\
    \ throw, taking 9 (2d8) poison damage on a failed save, or half as much damage\
    \ on a successful one. If the poison damage reduces the target to 0 hit points,\
    \ the target is stable but [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ for 1 hour, even after regaining hit points, and is [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ while [poisoned](Mechanics/Rules/conditions.md#Poisoned) in this way."
  "name": "Bite"
- "desc": "Ranged Weapon Attack: +5 to hit, range 30/60 ft., one creature. Hit:\
    \ The target is [restrained](Mechanics/Rules/conditions.md#Restrained) by webbing.\
    \ As an action, the [restrained](Mechanics/Rules/conditions.md#Restrained) target\
    \ can make a DC 12 Strength check, bursting the webbing on a success. The webbing\
    \ can also be attacked and destroyed (AC 10; hp 5; vulnerability to fire damage;\
    \ immunity to bludgeoning, poison, and psychic damage)."
  "name": "Web (Recharge 5-6)"
"source":
- "OotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/OotA/Spider%20King.webp"
```
^statblock