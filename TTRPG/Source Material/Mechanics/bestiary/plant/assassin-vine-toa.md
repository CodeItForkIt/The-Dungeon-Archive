---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/3
- monster/size/large
- monster/type/plant
statblock: inline
aliases: ["Assassin Vine"]
---
# [Assassin Vine](Mechanics\bestiary\plant/assassin-vine-toa.md)
*Source: Tomb of Annihilation p. 213, Ghosts of Saltmarsh, Sleeping Dragon's Wake*  

An assassin vine is an ambulatory plant that collects its fertilizer by grabbing and crushing prey and depositing the carcasses near its roots. It usually stays put unless it needs to seek out prey. A mature plant consists of a main vine, about 20 feet long. Smaller vines up to 5 feet long branch from the main vine every 6 inches. In late summer, the secondary vines produce bunches of small fruits that resemble wild grapes. The fruit is tough and has a hearty but bitter flavor.

A subterranean variant grows near hot springs, volcanic vents, and other sources of heat. An assassin vine growing underground usually generates enough offal to support a thriving colony of mushrooms and other fungi, which spring up around the plant and help conceal it.

```statblock
"name": "Assassin Vine (ToA)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"stats":
- !!int "18"
- !!int "10"
- !!int "16"
- !!int "1"
- !!int "10"
- !!int "1"
"speed": "5 ft., climb 5 ft."
"damage_resistances": "cold, fire"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened),\
  \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [prone](Mechanics/Rules/conditions.md#Prone)"
"senses": "blindsight 30 ft., passive Perception 10"
"languages": ""
"cr": "3"
"traits":
- "desc": "While the assassin vine remains motionless, it is indistinguishable from\
    \ a normal plant."
  "name": "False Appearance"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 20 ft., one creature. Hit:\
    \ The target takes 11 (2d6 + 4) bludgeoning damage, and it is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 14). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and it takes 21 (6d6) poison damage at the start of each of its turns. The\
    \ vine can constrict only one target at a time."
  "name": "Constrict"
- "desc": "The assassin vine can animate normal vines and roots on the ground in a\
    \ 15-foot square within 30 feet of it. These plants turn the ground in that area\
    \ into difficult terrain. A creature in that area when the effect begins must\
    \ succeed on a DC 13 Strength saving throw or be [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by entangling vines and roots. A creature [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by the plants can use its action to make a DC 13 Strength ([Athletics](Mechanics/Rules/skills.md#Athletics))\
    \ check, freeing itself on a successful check. The effect ends after 1 minute\
    \ or when the assassin vine dies or uses Entangling Vines again."
  "name": "Entangling Vines"
"source":
- "ToA"
- "GoS"
- "SDW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Assassin%20Vine.webp"
```
^statblock