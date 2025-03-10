---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/1
- monster/environment/desert
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Lion"]
---
# [Lion](Mechanics\bestiary\beast/lion.md)
*Source: Monster Manual p. 331, Tomb of Annihilation, Keys from the Golden Vault. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Lion"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "26"
"hit_dice": "4d10 + 4"
"stats":
- !!int "17"
- !!int "15"
- !!int "13"
- !!int "3"
- !!int "12"
- !!int "8"
"speed": "50 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
- "desc": "The lion has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The lion has advantage on an attack roll against a creature if at least\
    \ one of the lion's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Pack Tactics"
- "desc": "If the lion moves at least 20 feet straight toward a creature and then\
    \ hits it with a claw attack on the same turn, that target must succeed on a DC\
    \ 13 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ If the target is [prone](Mechanics/Rules/conditions.md#Prone), the lion can\
    \ make one bite attack against it as a bonus action."
  "name": "Pounce"
- "desc": "With a 10-foot running start, the lion can long jump up to 25 feet."
  "name": "Running Leap"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Claw"
"source":
- "MM"
- "ToA"
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Lion.webp"
```
^statblock

## Environment

mountain, grassland, hill, desert