---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1-2
- monster/environment/underdark
- monster/environment/urban
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Beggar Ghoul"]
---
# [Beggar Ghoul](Mechanics\bestiary\undead/beggar-ghoul-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 200*  

*This emaciated, gray husk of a creature wears rags and picks hungrily at a sliver of bone. It moves in a crouch so low that it's almost crawling, but its eyes glow like flickering coals and it exudes a desperate ferocity with each rot-fouled breath.*

## Lesser Ghouls

Most citizens of the ghoul empire are not darakhul but lesser strains of ghouls and ghasts. Beggar ghouls are by far the weakest of these. Though they make up the majority of any military action involving the legions, they are employed as fodder, and the most wretched of them are barely suitable even for that. They eke out miserable livings by scrounging for food near the surface or by begging in the ghoul cities.

## Withered and Deprived

Thin and emaciated even for undead, beggar ghouls are shriveled versions of their standard cousins—little more than flesh-covered skeletons. While some beggar ghouls spend their entire existence in undeath as this weak strain, at least a few were once stronger ghouls who withered when they were trapped far from sources of flesh. Others were exiled from the empire without the resources to fend for themselves.

> [!note] Ghouls in Midgard
> 
> The ghoul empire maintains complex social structures and forges serious alliances, particularly among the undead princes of Morgau and Doresh. Unofficial embassies exist in Zobeck, the Ironcrag Cantons, Krakova, and Magdar. Other hidden outposts may lurk below the Seven Cities, Illyria, or beyond.
> 
> Their patience and willingness to convert enemies into followers makes lasting victories against the darakhul difficult. Three full legions of ghouls serve Emperor Nicoforus directly, and a dozen more legions of varying quality press the fight to other races of the Underworld.
^ghouls-in-midgard

```statblock
"name": "Beggar Ghoul (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "13"
"hit_dice": "3d8"
"stats":
- !!int "10"
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Undercommon"
"cr": "1/2"
"traits":
- "desc": "The ghoul requires no air or sleep."
  "name": "Hungry Dead Nature"
- "desc": "The beggar ghoul has advantage on attack rolls against a creature if at\
    \ least one of the beggar ghoul's allies is within 5 feet of the creature and\
    \ the ally isn't [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Pack Tactics"
- "desc": "Its Bite attack is a critical hit if the beggar ghoul bites a creature\
    \ it has surprised."
  "name": "Savage Hunger"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) slashing damage. If the target is a creature other than an elf or Undead,\
    \ it must succeed on a DC 10 Constitution saving throw or be [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ for 1 minute. A [paralyzed](Mechanics/Rules/conditions.md#Paralyzed) target\
    \ can repeat the saving throw at the end of each of its turns, ending the effect\
    \ on itself on a success."
  "name": "Claws"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Beggar%20Ghoul.webp"
```
^statblock

## Environment

underdark, urban