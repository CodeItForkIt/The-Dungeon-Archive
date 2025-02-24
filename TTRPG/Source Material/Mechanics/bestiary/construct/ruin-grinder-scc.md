---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/5
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Ruin Grinder"]
---
# [Ruin Grinder](Mechanics\bestiary\construct/ruin-grinder-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 211*  

Created by the archaeomancers of Lorehold College, ruin grinders are mighty automatons built to excavate ancient ruins and artifacts. The massive toothed shovels attached to a ruin grinder's arms tear through millennia-old bedrock with ease, leading some Lorehold mages to fear that the grinders destroy more history than they unearth.

```statblock
"name": "Ruin Grinder (SCC)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d10 + 22"
"stats":
- !!int "22"
- !!int "13"
- !!int "15"
- !!int "3"
- !!int "10"
- !!int "1"
"speed": "30 ft., burrow 30 ft."
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "5"
"traits":
- "desc": "Whenever the ruin grinder is subjected to fire damage, it regains a number\
    \ of hit points equal to half the fire damage dealt."
  "name": "Fire Absorption"
- "desc": "The ruin grinder deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "The ruin grinder can burrow through solid rock at half its burrowing speed\
    \ and leaves a 10-foot-diameter tunnel in its wake."
  "name": "Tunneler"
"actions":
- "desc": "The ruin grinder makes two Excavator attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d6 + 6) force damage. If the target is a Huge or smaller creature, it must\
    \ succeed on a DC 17 Strength saving throw or be pushed up to 10 feet away and\
    \ knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Excavator"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Ruin%20Grinder.webp"
```
^statblock