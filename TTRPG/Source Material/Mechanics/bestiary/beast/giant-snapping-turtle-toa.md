---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/3
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Giant Snapping Turtle"]
---
# [Giant Snapping Turtle](Mechanics\bestiary\beast/giant-snapping-turtle-toa.md)
*Source: Tomb of Annihilation p. 222*  

Giant snapping turtles can grow to be 12 feet in diameter. Although they appear slow and ponderous, they are capable of startling bursts of speed and will aggressively attack smaller creatures that approach them. One snap of a giant turtle's jaws can cut a human in half, and these creatures aren't fussy about what they eat.

```statblock
"name": "Giant Snapping Turtle (ToA)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor; 12 while prone"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"stats":
- !!int "19"
- !!int "10"
- !!int "14"
- !!int "2"
- !!int "12"
- !!int "5"
"speed": "30 ft., swim 40 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "3"
"traits":
- "desc": "The turtle can breathe air and water."
  "name": "Amphibious"
- "desc": "Whenever an effect knocks the turtle [prone](Mechanics/Rules/conditions.md#Prone),\
    \ it can make a DC 10 Constitution saving throw to avoid being knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ A [prone](Mechanics/Rules/conditions.md#Prone) turtle is upside down. To stand\
    \ up, it must succeed on a DC 10 Dexterity check on its turn and then use all\
    \ its movement for that turn."
  "name": "Stable"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 18\
    \ (4d6 + 4) slashing damage."
  "name": "Bite"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Giant%20Snapping%20Turtle.webp"
```
^statblock