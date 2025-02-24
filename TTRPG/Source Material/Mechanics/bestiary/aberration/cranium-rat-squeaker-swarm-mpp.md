---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/5
- monster/size/medium
- monster/type/aberration
statblock: inline
aliases: ["Cranium Rat Squeaker Swarm"]
---
# [Cranium Rat Squeaker Swarm](Mechanics\bestiary\aberration/cranium-rat-squeaker-swarm-mpp.md)
*Source: Morte's Planar Parade p. 22, Sigil and the Outlands, Turn of Fortune's Wheel*  

The cranium rats squeakers of Sigil have no connection to the mind flayers that created their progenitors. Rather, these magical rodents cooperate with the residents of the City of Doors, whether by simply living together or by pursuing greater ambitions. When squeakers collect in large numbers, their swarms merge into a single intelligence with enhanced psionic abilities and the accumulated memories of its constituents.

```statblock
"name": "Cranium Rat Squeaker Swarm (MPP)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Neutral"
"ac": !!int "12"
"hp": !!int "76"
"hit_dice": "17d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "10"
- !!int "15"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "darkvision 30 ft., passive Perception 10"
"languages": "telepathy 30 ft."
"cr": "5"
"traits":
- "desc": "The swarm casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\nAt\
    \ will: [command](Mechanics/spells/command.md) , [detect thoughts](Mechanics/spells/detect-thoughts.md)\
    \ , [sending](Mechanics/spells/sending.md) \n\n1/day each: [confusion](Mechanics/spells/confusion.md)\
    \ , [dominate monster](Mechanics/spells/dominate-monster.md) \n\nTo cast this\
    \ spell, the swarm must have more than half its hit points remaining."
  "name": "Spellcasting (Psionics)"
- "desc": "The swarm can use its [sending](Mechanics/spells/sending.md) spell to target\
    \ someone familiar to a creature in telepathic contact with the swarm."
  "name": "Psychic Messenger"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny rat. The swarm can't regain\
    \ hit points or gain temporary hit points."
  "name": "Swarm"
- "desc": "The swarm is immune to any effect that would sense its emotions or read\
    \ its thoughts, as well as to divination spells."
  "name": "Telepathic Shroud"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 0 ft., one target in the swarm's\
    \ space. Hit: 14 (4d6) piercing damage, or 7 (2d6) piercing damage if the\
    \ swarm has half of its hit points or fewer, plus 22 (5d8) psychic damage."
  "name": "Bites"
"bonus_actions":
- "desc": "The swarm sheds dim light from its brains in a 5-foot radius, increases\
    \ the illumination to bright light in a 5- to 20-foot radius and dim light for\
    \ an additional number of feet equal to the chosen radius, or extinguishes the\
    \ light."
  "name": "Illumination"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Cranium%20Rat%20Squeaker%20Swarm.webp"
```
^statblock