---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/8
- monster/size/huge
- monster/type/construct
statblock: inline
aliases: ["Ruidium Elephant"]
---
# [Ruidium Elephant](Mechanics\bestiary\construct/ruidium-elephant-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 95*  

Unknown to anyone who has come into contact with it, the elephant figurine was infected with ruidium during its time in Cael Morrow, and that substance has warped its magical properties.

When a character tries to retrieve the figurine, it reacts as if it had been activated, transforming into a crystalline version of the creature it was meant to become. This creature can't be controlled.

```statblock
"name": "Ruidium Elephant (CRCotN)"
"size": "Huge"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"stats":
- !!int "24"
- !!int "9"
- !!int "21"
- !!int "3"
- !!int "11"
- !!int "6"
"speed": "40 ft."
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "passive Perception 10"
"languages": ""
"cr": "8"
"traits":
- "desc": "If the elephant moves at least 20 feet straight toward a creature and then\
    \ hits it with a Gore attack on the same turn, that target must succeed on a DC\
    \ 16 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ If the target is [prone](Mechanics/Rules/conditions.md#Prone), the elephant\
    \ can make one Stomp attack against it as a bonus action."
  "name": "Trampling Charge"
"actions":
- "desc": "Melee Weapon Attack: +10 to hit (with advantage if the target is a\
    \ creature missing any hit points), reach 10 ft., one target. Hit: 25 (4d8\
    \ + 7) piercing damage plus 7 (2d6) psychic damage."
  "name": "Gore"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one [prone](Mechanics/Rules/conditions.md#Prone)\
    \ creature. Hit: 29 (4d10 + 7) bludgeoning damage plus 7 (2d6) psychic damage."
  "name": "Stomp"
"source":
- "CRCotN"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Ruidium%20Elephant.webp"
```
^statblock