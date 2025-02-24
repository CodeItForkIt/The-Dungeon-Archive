---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/2
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Great Cat"]
---
# [Great Cat](Mechanics\bestiary\beast/great-cat-psz.md)
*Source: Plane Shift: Zendikar p. 34*  

At least two varieties of great cat (similar to the [saber-toothed tiger](Mechanics/bestiary/beast/saber-toothed-tiger.md)) sport enormous blades jutting back from the forelegs, which help them cut through heavy undergrowth and take down much larger prey.

```statblock
"name": "Great Cat (PSZ)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"stats":
- !!int "18"
- !!int "14"
- !!int "15"
- !!int "3"
- !!int "12"
- !!int "8"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "2"
"traits":
- "desc": "The cat has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "If the cat moves at least 20 feet straight toward a creature and then hits\
    \ it with a claw attack on the same turn, that target must succeed on a DC 14\
    \ Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ If the target is [prone](Mechanics/Rules/conditions.md#Prone), the cat can make\
    \ one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d10 + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage."
  "name": "Claw"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Great%20Cat.webp"
```
^statblock