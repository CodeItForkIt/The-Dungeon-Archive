---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tce
- monster/cr/
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Construct Spirit (Clay)"]
---
# [Construct Spirit (Clay)](Mechanics\bestiary\construct/construct-spirit-clay-tce.md)
*Source: Tasha's Cauldron of Everything p. 111*  

```statblock
"name": "Construct Spirit (Clay) (TCE)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac_class": "13 + the level of the spell (natural armor)"
"stats":
- !!int "18"
- !!int "10"
- !!int "18"
- !!int "14"
- !!int "11"
- !!int "5"
"speed": "30 ft."
"damage_resistances": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [incapacitated](Mechanics/Rules/conditions.md#Incapacitated),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages you speak"
"actions":
- "desc": "The construct makes a number of attacks equal to half this spell's level\
    \ (rounded down)."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: YourSpellAttack to hit, reach 5 ft., one target.\
    \ Hit: 1d8 + 4 + the spell's level bludgeoning damage."
  "name": "Slam"
"reactions":
- "desc": "When the construct takes damage, it makes a slam attack against a random\
    \ creature within 5 feet of it. If no creature is within reach, the construct\
    \ moves up to half its speed toward an enemy it can see, without provoking opportunity\
    \ attacks."
  "name": "Berserk Lashing"
"source":
- "TCE"
```
^statblock