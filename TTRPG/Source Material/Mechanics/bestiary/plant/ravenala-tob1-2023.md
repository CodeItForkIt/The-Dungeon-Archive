---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/coastal
- monster/environment/forest
- monster/size/large
- monster/type/plant
statblock: inline
aliases: ["Ravenala"]
---
# [Ravenala](Mechanics\bestiary\plant/ravenala-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 303*  

*The tree steps forward on bark-covered legs. Its head is crowned by long-stemmed, green-paddled fronds and spiked seed pods, and its dangling arms end in hooked, wooden talons.*

## Leafy Advisors

Wise and long-lived like treants, ravenalas tend their coastal forest homes far from most societies. Tribal humanoids respect and venerate ravenalas and sometimes seek their advice or aid in times of great need. Ravenalas seldom interact with others unless approached.

## Prisoner's Lamentation

Unlike treants, ravenalas avoid physical conflict in favor of diplomacy and compromise. If annoyed, they imprison hostile creatures within their trunks rather than killing or eating the attackers. Trapped creatures must sing their own lament as they are carried off to a distant locale away from the ravenala's home.

```statblock
"name": "Ravenala (ToB1-2023)"
"size": "Large"
"type": "plant"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d10 + 60"
"stats":
- !!int "20"
- !!int "10"
- !!int "20"
- !!int "12"
- !!int "16"
- !!int "12"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "6"
"damage_vulnerabilities": "cold, fire"
"damage_resistances": "bludgeoning, piercing"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened)"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "5"
"traits":
- "desc": "The ravenala has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Difficult terrain composed of magical or nonmagical plants doesn't cost\
    \ the ravenala extra movement. In addition, it can pass through magical or nonmagical\
    \ plants without being slowed by them and without taking damage from them if they\
    \ have thorns, spines, or a similar hazard."
  "name": "Woodland Stride"
"actions":
- "desc": "The ravenala makes two Bursting Pod or Slam attacks. If both Slam attacks\
    \ hit a Medium or smaller creature, the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 14), and the ravenala uses its Lamenting Engulfment on the target."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 18\
    \ (3d8 + 5) bludgeoning damage."
  "name": "Slam"
- "desc": "Ranged Weapon Attack: +8 to hit, range 30/120 ft., one target. Hit:\
    \ 12 (2d6 + 5) bludgeoning damage, and each creature within 5 feet of the target,\
    \ including the target, must make a DC 15 Dexterity saving throw, taking 5 (2d4)\
    \ piercing damage on a failed save, or half as much damage on a successful one."
  "name": "Bursting Pod"
- "desc": "The ravenala engulfs a Medium or smaller creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by it. The engulfed target is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ and [restrained](Mechanics/Rules/conditions.md#Restrained), it has total cover\
    \ against attacks and other effects outside the ravenala, and it must succeed\
    \ on a DC 14 Charisma saving throw at the start of each of the ravenala's turns\
    \ or sing a lament of the mistakes and misdeeds it has performed in its lifetime.\
    \ While singing, the engulfed creature can still act, but it can't otherwise speak,\
    \ including casting spells with verbal components. If the ravenala moves, the\
    \ engulfed creature moves with it. The ravenala can have only one creature engulfed\
    \ at a time."
  "name": "Lamenting Engulfment"
- "desc": "The ravenala removes a leaf from its head and wraps the leaf around the\
    \ wounds of one creature it can see within 5 feet of it. The target magically\
    \ regains 10 3d6 hp and is freed from any disease, poison, blindness, or deafness."
  "name": "Healing Leaves (3/Day)"
- "desc": "The ravenala whispers magical words of growth to nonmagical plants on a\
    \ point it can see within 30 feet of it. The plants burst with life and spread\
    \ rapidly. The area within 20 feet of that point becomes difficult terrain for\
    \ 24 hours."
  "name": "Encourage Growth (3/Day)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ravenala.webp"
```
^statblock

## Environment

coastal, forest