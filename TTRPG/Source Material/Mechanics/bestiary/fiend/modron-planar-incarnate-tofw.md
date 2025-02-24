---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/22
- monster/size/gargantuan
- monster/type/fiend
statblock: inline
aliases: ["Modron Planar Incarnate"]
---
# [Modron Planar Incarnate](Mechanics\bestiary\fiend/modron-planar-incarnate-tofw.md)
*Source: Turn of Fortune's Wheel p. 92*  

```statblock
"name": "Modron Planar Incarnate (ToFW)"
"size": "Gargantuan"
"type": "fiend"
"alignment": "Any alignment"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "333"
"hit_dice": "18d20 + 144"
"stats":
- !!int "27"
- !!int "10"
- !!int "26"
- !!int "15"
- !!int "20"
- !!int "20"
"speed": "40 ft., fly 40 ft."
"skillsaves":
  "Perception": !!int "12"
"damage_immunities": "necrotic; poison; radiant; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [restrained](Mechanics/Rules/conditions.md#Restrained),\
  \ [stunned](Mechanics/Rules/conditions.md#Stunned), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "truesight 120 ft., passive Perception 22"
"languages": "all"
"cr": "22"
"traits":
- "desc": "If the incarnate fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The incarnate has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The incarnate deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "The incarnate makes two Slam or Energy Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 15 ft., one target. Hit: 27\
    \ (3d12 + 8) force damage."
  "name": "Slam"
- "desc": "Ranged Spell Attack: +12 to hit, range 120 ft., one target. Hit:\
    \ 32 (5d12) necrotic damage."
  "name": "Energy Bolt"
- "desc": "The incarnate exhales concentrated energy native to its plane in a 60-foot\
    \ cone. Each creature in that area must make a DC 23 Constitution saving throw.\
    \ On a failed save, a creature takes 52 (8d12) necrotic damage, and the creature\
    \ has the [blinded](Mechanics/Rules/conditions.md#Blinded) condition until the\
    \ end of the incarnate's next turn. On a successful save, a creature takes half\
    \ as much damage only."
  "name": "Planar Exhalation (Recharge 5-6)"
"reactions":
- "desc": "The incarnate can take up to three reactions per round but only one per\
    \ turn."
  "name": ""
- "desc": "In response to being hit by an attack roll, the incarnate turns its magical\
    \ gaze toward one creature it can see within 120 feet of itself and commands it\
    \ to combust. The target must succeed on a DC 20 Wisdom saving throw or take 16\
    \ (3d10) fire damage."
  "name": "Searing Gaze"
- "desc": "Immediately after a creature the incarnate sees ends its turn, the incarnate\
    \ teleports up to 60 feet to an unoccupied space it can see."
  "name": "Teleport"
"source":
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/Modron%20Planar%20Incarnate.webp"
```
^statblock