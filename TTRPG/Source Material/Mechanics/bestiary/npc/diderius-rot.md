---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/rot
- monster/cr/15
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Diderius"]
---
# [Diderius](Mechanics\bestiary\npc/diderius-rot.md)
*Source: The Rise of Tiamat p. 40, Tyranny of Dragons p. 131*  

```statblock
"name": "Diderius (RoT)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"stats":
- !!int "18"
- !!int "10"
- !!int "17"
- !!int "18"
- !!int "18"
- !!int "16"
"speed": "20 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "9"
  "Intelligence": !!int "5"
  "Constitution": !!int "8"
"skillsaves":
  "Religion": !!int "5"
  "History": !!int "5"
"damage_vulnerabilities": "fire"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "the languages it knew in life"
"cr": "15"
"traits":
- "desc": "Diderius is a 10th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 17, +9 to hit with spell attacks). He has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [minor illusion](Mechanics/spells/minor-illusion.md),\
    \ [ray of frost](Mechanics/spells/ray-of-frost.md)\n\n1st level (4 slots):\
    \ [charm person](Mechanics/spells/charm-person.md), [detect magic](Mechanics/spells/detect-magic.md),\
    \ [shield](Mechanics/spells/shield.md), [thunderwave](Mechanics/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [cloud of daggers](Mechanics/spells/cloud-of-daggers.md),\
    \ [hold person](Mechanics/spells/hold-person.md), [see invisibility](Mechanics/spells/see-invisibility.md)\n\
    \n3rd level (3 slots): [animate dead](Mechanics/spells/animate-dead.md), [dispel\
    \ magic](Mechanics/spells/dispel-magic.md)\n\n4th level (3 slots): [fire shield](Mechanics/spells/fire-shield.md),\
    \ [greater invisibility](Mechanics/spells/greater-invisibility.md)\n\n5th level\
    \ (2 slots): [cloudkill](Mechanics/spells/cloudkill.md), [wall of stone](Mechanics/spells/wall-of-stone.md)"
  "name": "Spellcasting"
- "desc": "Diderius has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "A destroyed mummy lord gains a new body in 24 hours if its heart is intact,\
    \ regaining all its hit points and becoming active again. The new body appears\
    \ within 5 feet of Diderius's heart."
  "name": "Rejuvenation"
"actions":
- "desc": "The mummy can use its Dreadful Glare and makes one attack with its rotting\
    \ fist."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 14\
    \ (3d6 + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target\
    \ is a creature, it must succeed on a DC 16 Constitution saving throw or be cursed\
    \ with mummy rot. The cursed target can't regain hit points, and its hit point\
    \ maximum decreases by 10 (3d6) for every 24 hours that elapse. If the curse\
    \ reduces the target's hit point maximum to 0, the target dies, and its body turns\
    \ to dust. The curse lasts until removed by the [remove curse](Mechanics/spells/remove-curse.md)\
    \ spell or other magic."
  "name": "Rotting Fist"
- "desc": "Diderius targets one creature it can see within 60 feet of it. If the target\
    \ can see Diderius, it must succeed on a DC 16 Wisdom saving throw against this\
    \ magic or become [frightened](Mechanics/Rules/conditions.md#Frightened) until\
    \ the end of the mummy's next turn. If the target fails the saving throw by 5\
    \ or more, it is also [paralyzed](Mechanics/Rules/conditions.md#Paralyzed) for\
    \ the same duration. A target that succeeds on the saving throw is immune to the\
    \ Dreadful Glare of all mummies and mummy lords for the next 24 hours."
  "name": "Dreadful Glare"
"legendary_actions":
- "desc": "Diderius makes one attack with its rotting fist or uses its Dreadful Glare."
  "name": "Attack"
- "desc": "Blinding dust and sand swirls magically around Diderius. Each creature\
    \ within 5 feet of Diderius must succeed on a DC 16 Constitution saving throw\
    \ or be [blinded](Mechanics/Rules/conditions.md#Blinded) until the end of the\
    \ creature's next turn."
  "name": "Blinding Dust"
- "desc": "Diderius utters a blasphemous word. Each non-undead creature within 10\
    \ feet of Diderius that can hear the magical utterance must succeed on a DC 16\
    \ Constitution saving throw or be [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ until the end of Diderius's next turn."
  "name": "Blasphemous Word (Costs 2 Actions)"
- "desc": "Diderius magically unleashes negative energy. Creatures within 60 feet\
    \ of Diderius, including ones behind barriers and around corners, can't regain\
    \ hit points until the end of Diderius's next turn."
  "name": "Channel Negative Energy (Costs 2 Actions)"
- "desc": "Diderius magically transforms into a whirlwind of sand, moves up to 60\
    \ feet, and reverts to its normal form. While in whirlwind form, Diderius is immune\
    \ to all damage, and it can't be [grappled](Mechanics/Rules/conditions.md#Grappled),\
    \ [petrified](Mechanics/Rules/conditions.md#Petrified), knocked [prone](Mechanics/Rules/conditions.md#Prone),\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained), or [stunned](Mechanics/Rules/conditions.md#Stunned).\
    \ Equipment worn or carried by Diderius remain in its possession."
  "name": "Whirlwind of Sand (Costs 2 Actions)"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/RoT/Diderius.webp"
```
^statblock