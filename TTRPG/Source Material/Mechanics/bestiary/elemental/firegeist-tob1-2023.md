---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/planar
- monster/size/small
- monster/type/elemental
statblock: inline
aliases: ["Firegeist"]
---
# [Firegeist](Mechanics\bestiary\elemental/firegeist-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 188*  

*Wisps of black smoke and spots of bright flame coalesce into a vaguely humanoid shape.*

## Elemental Echoes

When a fire elemental meets its destruction in a particularly humiliating fashion, particularly by humanoids, while summoned away from its home plane, its remains transform into a firegeist. Malevolent and resentful, they exist for revenge.

## Indiscriminate Arsonists

Firegeists are not adept at telling one humanoid from another, and they are satisfied with burning any similar creature, providing the creature is flammable.

## Brighter Light, Darker Smoke

A firegeist can shine brightly or be primarily smoky and dark, as it wishes. It always sheds a little light.

```statblock
"name": "Firegeist (ToB1-2023)"
"size": "Small"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "82"
"hit_dice": "15d6 + 30"
"stats":
- !!int "7"
- !!int "18"
- !!int "14"
- !!int "4"
- !!int "16"
- !!int "6"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "5"
"damage_immunities": "fire, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Ignan"
"cr": "2"
"traits":
- "desc": "The firegeist doesn't require air, food, drink, or sleep."
  "name": "Elemental Nature"
- "desc": "The firegeist has advantage on Dexterity ([Stealth](Mechanics/Rules/skills.md#Stealth))\
    \ checks made to hide in fire or in areas lit by nonmagical fire."
  "name": "Hide By Firelight"
- "desc": "While in an area of light created by a spell or other magical effect, the\
    \ firegeist has disadvantage on attack rolls and ability checks."
  "name": "Magical Light Sensitivity"
- "desc": "The firegeist sheds dim light in a 5- to 20-foot radius. It can alter the\
    \ radius as a bonus action."
  "name": "Variable Illumination"
- "desc": "For every 5 feet the firegeist moves in water, or for every gallon of water\
    \ splashed on it, it takes 1 cold damage."
  "name": "Water Susceptibility"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) bludgeoning damage plus 7 (2d6) fire damage. If the target is a flammable\
    \ object, it ignites. If the target is a creature, the target must succeed on\
    \ a DC 13 Dexterity saving throw or ignite. Until a creature takes an action to\
    \ douse the fire, the target takes 3 (1d6) fire damage at the start of each\
    \ of its turns."
  "name": "Burning Slam"
- "desc": "The firegeist assaults the mind of one creature it can see within 30 feet\
    \ of it with the painful, humiliating memory of the firegeist's first death. The\
    \ target must make a DC 13 Wisdom saving throw. On a failure, the target takes\
    \ 14 (4d6) fire damage and is [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. On a success, the target takes half the damage and isn't [frightened](Mechanics/Rules/conditions.md#Frightened).\
    \ While [frightened](Mechanics/Rules/conditions.md#Frightened), the creature takes\
    \ 3 (1d6) fire damage at the start of each of its turns. The target can repeat\
    \ the saving throw at the end of each of its turns, ending the effect on itself\
    \ on a success."
  "name": "Burning Terror (Recharge 5-6)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Firegeist.webp"
```
^statblock

## Environment

planar