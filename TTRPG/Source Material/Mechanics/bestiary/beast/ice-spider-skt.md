---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/skt
- monster/cr/1
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Ice Spider"]
---
# [Ice Spider](Mechanics\bestiary\beast/ice-spider-skt.md)
*Source: Storm King's Thunder p. 127*  

```statblock
"name": "Ice Spider (SKT)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"stats":
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "2"
- !!int "11"
- !!int "4"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "7"
"damage_resistances": "cold"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 10"
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
    \ The target is [restrained](Mechanics/Rules/conditions.md#Restrained) by webbing,\
    \ and takes 1 cold damage at the start of each of its turns. As an action, the\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained) target can make a DC\
    \ 12 Strength check, bursting the webbing on a success. The webbing can also be\
    \ attacked and destroyed (AC 10; hp 5; vulnerability to fire damage; immunity\
    \ to poison, and psychic damage)."
  "name": "Icy Web (Recharge 5-6)"
"source":
- "SKT"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SKT/Ice%20Spider.webp"
```
^statblock