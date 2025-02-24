---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/21
- monster/size/gargantuan
- monster/type/elemental
statblock: inline
aliases: ["Fire Kraken"]
---
# [Fire Kraken](Mechanics\bestiary\elemental/fire-kraken-coa.md)
*Source: Chains of Asmodeus p. 120*  

```statblock
"name": "Fire Kraken (CoA)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "402"
"hit_dice": "23d20 + 161"
"stats":
- !!int "27"
- !!int "11"
- !!int "24"
- !!int "10"
- !!int "20"
- !!int "15"
"speed": "30 ft., swim 60 ft."
"saves":
  "Dexterity": !!int "7"
  "Constitution": !!int "14"
"skillsaves":
  "Nature": !!int "7"
  "Athletics": !!int "15"
  "Survival": !!int "12"
"damage_immunities": "fire; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)"
"senses": "blindsight 120 ft., passive Perception 15"
"languages": "understands Abyssal, Celestial, Infernal, and Primordial but can't speak,\
  \ telepathy 120 ft."
"cr": "21"
"traits":
- "desc": "The kraken ignores difficult terrain, and magical effects can't reduce\
    \ its speed or cause it to be [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ It can spend 5 feet of movement to escape from nonmagical restraints or grapples."
  "name": "Freedom of Movement"
- "desc": "If the kraken fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The kraken deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The kraken makes two attacks using its Tentacle, Fling, or a combination\
    \ of the two."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 10 ft., one target. Hit: 18\
    \ (3d6 + 8) piercing damage and 7 (2d6) fire damage. If the target is a Large\
    \ or smaller creature [grappled](Mechanics/Rules/conditions.md#Grappled) by the\
    \ kraken, the creature is swallowed and the grapple ends. While swallowed, a creature\
    \ has the [blinded](Mechanics/Rules/conditions.md#Blinded) and [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ conditions, has total cover against attacks and other effects outside the kraken,\
    \ and takes 42 (12d6) fire damage at the start of the kraken's turns. If the\
    \ kraken takes 50 damage or more on a single turn from a creature inside it, it\
    \ must succeed on a DC 23 Constitution saving throw or regurgitate all swallowed\
    \ creatures, which fall into a space within 10 feet of the kraken and now have\
    \ the [prone](Mechanics/Rules/conditions.md#Prone) condition. If the kraken dies,\
    \ a swallowed creature is no longer [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by it and can escape from the corpse using 15 feet of movement, exiting with\
    \ the [prone](Mechanics/Rules/conditions.md#Prone) condition."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +15 to hit, reach 20 ft., one target. Hit: 13\
    \ (2d4 + 8) fire damage. If the target is a Huge or smaller creature, it has\
    \ the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape DC\
    \ 16). While [grappled](Mechanics/Rules/conditions.md#Grappled), the target also\
    \ has the [restrained](Mechanics/Rules/conditions.md#Restrained) condition. Any\
    \ target that starts its turn [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the kraken takes 5 (2d4) fire damage. The kraken has five tentacles, each\
    \ of which can grapple one target."
  "name": "Tentacle"
- "desc": "One Large or smaller object or creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the kraken is thrown up to 60 feet in a random direction, and now has the\
    \ [prone](Mechanics/Rules/conditions.md#Prone) condition. If a thrown target strikes\
    \ a solid surface, the target takes 3 (1d6) bludgeoning damage for every 10\
    \ feet it was thrown. If the target is thrown at a creature, that creature must\
    \ succeed on a DC 16 Dexterity saving throw or take the same damage and be knocked\
    \ down with the [prone](Mechanics/Rules/conditions.md#Prone) condition."
  "name": "Fling"
"legendary_actions":
- "desc": "The kraken makes a Fling attack."
  "name": "Appendage"
- "desc": "The kraken exhales fire in a 60-foot cone. Each creature in that area must\
    \ make a DC 20 Dexterity saving throw, taking 36 (8d8) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Fire Breath (Costs 3 Actions)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Fire%20Kraken.webp"
```
^statblock