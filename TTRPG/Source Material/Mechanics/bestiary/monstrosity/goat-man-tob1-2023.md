---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/badlands
- monster/environment/grassland
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Goat-Man"]
---
# [Goat-Man](Mechanics\bestiary\monstrosity/goat-man-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 214*  

*This hunched, man-like figure lurches with a strange, half-hopping gait. Tattered clothing hangs from its muscled shoulders, and its legs are those of a ram, ending in cloven hooves.*

## Trespassers on the Rites

The first of the goat-men was the victim of a powerful curse intended to punish him for spying on magical rites exclusive to the women of his tribe. Admiring the grotesque result, the Black Goat of the Woods With a Thousand Young adopted him as its servant, and ensured that all who committed the same taboo fell to the same curse, and thus into the Black Goat's service.

## Bleating Speech

A goat-man's head is tusked, adorned with curling ram's horns, and its beard often drips with gore. Rows of transparent, needle-like, malformed teeth fill its mouth, making clear speech impossible for goat-men.

## Serve Foul Cults

Cultists of Shub-Niggurath or the Black Goat in good standing are sometimes granted the services of a goat-man. The creatures guard ritual sites, visit settlements to capture or purchase suitable sacrifices, and perform certain unspeakable acts with cult members to call forth ritual magic.

```statblock
"name": "Goat-Man (ToB1-2023)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "19"
- !!int "14"
- !!int "14"
- !!int "10"
- !!int "13"
- !!int "8"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "4"
"skillsaves":
  "Athletics": !!int "6"
  "Stealth": !!int "6"
  "Acrobatics": !!int "4"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "understands Common, Giant, and Trollkin but can't speak"
"cr": "3"
"traits":
- "desc": "If the goat-man moves at least 20 feet straight toward a target and then\
    \ hits it with a Slam attack on the same turn, the target takes an extra 4 (1d8)\
    \ bludgeoning damage. If the target is a creature, it must succeed on a DC 14\
    \ Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Charge"
"actions":
- "desc": "The goat-man makes one Bite attack and two Slam attacks. If both Slam attacks\
    \ hit the same target, the target must succeed on a DC 14 Constitution saving\
    \ throw or be [stunned](Mechanics/Rules/conditions.md#Stunned) until the end of\
    \ its next turn."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) bludgeoning damage."
  "name": "Slam"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Goat-Man.webp"
```
^statblock

## Environment

badlands, grassland