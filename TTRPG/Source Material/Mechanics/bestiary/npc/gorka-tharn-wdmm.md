---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/15
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Gorka Tharn"]
---
# [Gorka Tharn](Mechanics\bestiary\npc/gorka-tharn-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 257*  

```statblock
"name": "Gorka Tharn (WDMM)"
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
- !!int "11"
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
"languages": "Dwarvish, Undercommon"
"cr": "15"
"traits":
- "desc": "The mummy lord is a 10th-level spellcaster. Its spellcasting ability is\
    \ Wisdom (spell save DC 17, +9 to hit with spell attacks). The mummy lord has\
    \ the following cleric spells prepared:\n\nCantrips (at will): [sacred flame](Mechanics/spells/sacred-flame.md),\
    \ [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\n1st level (4 slots): [command](Mechanics/spells/command.md),\
    \ [guiding bolt](Mechanics/spells/guiding-bolt.md), [shield of faith](Mechanics/spells/shield-of-faith.md)\n\
    \n2nd level (3 slots): [hold person](Mechanics/spells/hold-person.md), [silence](Mechanics/spells/silence.md),\
    \ [spiritual weapon](Mechanics/spells/spiritual-weapon.md)\n\n3rd level (3 slots):\
    \ [animate dead](Mechanics/spells/animate-dead.md), [dispel magic](Mechanics/spells/dispel-magic.md)\n\
    \n4th level (3 slots): [stone shape](Mechanics/spells/stone-shape.md), [guardian\
    \ of faith](Mechanics/spells/guardian-of-faith.md)\n\n5th level (2 slots):\
    \ [contagion](Mechanics/spells/contagion.md), [insect plague](Mechanics/spells/insect-plague.md)\n\
    \n6th level (1 slots): [harm](Mechanics/spells/harm.md)"
  "name": "Spellcasting"
- "desc": "The mummy lord has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "A destroyed mummy lord gains a new body in 24 hours if its heart is intact,\
    \ regaining all its hit points and becoming active again. The new body appears\
    \ within 5 feet of the mummy lord's heart."
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
- "desc": "The mummy lord targets one creature it can see within 60 feet of it. If\
    \ the target can see the mummy lord, it must succeed on a DC 16 Wisdom saving\
    \ throw against this magic or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ until the end of the mummy's next turn. If the target fails the saving throw\
    \ by 5 or more, it is also [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ for the same duration. A target that succeeds on the saving throw is immune\
    \ to the Dreadful Glare of all mummies and mummy lords for the next 24 hours."
  "name": "Dreadful Glare"
- "desc": "For 1 minute, the mummy lord magically increases in size, along with anything\
    \ it is wearing or carrying. While enlarged, the mummy lord is Large, doubles\
    \ its damage dice with its Rotting Fist attack, and makes Strength checks and\
    \ Strength saving throws with advantage. If the mummy lord lacks the room to become\
    \ Large, it attains the maximum size possible in the space available."
  "name": "Enlarge (Recharges after a Short or Long Rest)"
- "desc": "The mummy lord magically turns [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ for up to 1 hour or until it attacks, it casts a spell, it uses its Enlarge,\
    \ or its [concentration](Mechanics/Rules/conditions.md#Concentration) is broken\
    \ (as if concentrating on a spell). Any equipment the mummy lord wears or carries\
    \ is [invisible](Mechanics/Rules/conditions.md#Invisible) with it.\n\nThe stalagmite\
    \ in the northwest alcove is hollow and serves as Gorka Tharn's sarcophagus. The\
    \ mummy lord is lodged inside the stalagmite's funnel-shaped interior. When it\
    \ awakens, the mummy lord uses a [stone shape](Mechanics/spells/stone-shape.md)\
    \ spell to create an opening large enough for it to emerge. It destroys any intruders\
    \ in its lair, then returns to its sarcophagus and its slumber.\n\nAt the bottom\
    \ of the stalagmite's hollow cavity, four 1-foot-tall clay urns contain Gorka\
    \ Tharn's preserved internal organs, including the mummy lord's shriveled heart.\
    \ Only by destroying the heart can the characters prevent the mummy lord from\
    \ rejuvenating. The heart is a Tiny object with AC 5, 25 hit points, and immunity\
    \ to all damage except fire."
  "name": "Invisibility (Recharges after a Short or Long Rest)"
"legendary_actions":
- "desc": "The mummy lord makes one attack with its rotting fist or uses its Dreadful\
    \ Glare."
  "name": "Attack"
- "desc": "Blinding dust and sand swirls magically around the mummy lord. Each creature\
    \ within 5 feet of the mummy lord must succeed on a DC 16 Constitution saving\
    \ throw or be [blinded](Mechanics/Rules/conditions.md#Blinded) until the end of\
    \ the creature's next turn."
  "name": "Blinding Dust"
- "desc": "The mummy lord utters a blasphemous word. Each non-undead creature within\
    \ 10 feet of the mummy lord that can hear the magical utterance must succeed on\
    \ a DC 16 Constitution saving throw or be [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ until the end of the mummy lord's next turn."
  "name": "Blasphemous Word (Costs 2 Actions)"
- "desc": "The mummy lord magically unleashes negative energy. Creatures within 60\
    \ feet of the mummy lord, including ones behind barriers and around corners, can't\
    \ regain hit points until the end of the mummy lord's next turn."
  "name": "Channel Negative Energy (Costs 2 Actions)"
- "desc": "The mummy lord magically transforms into a whirlwind of sand, moves up\
    \ to 60 feet, and reverts to its normal form. While in whirlwind form, the mummy\
    \ lord is immune to all damage, and it can't be [grappled](Mechanics/Rules/conditions.md#Grappled),\
    \ [petrified](Mechanics/Rules/conditions.md#Petrified), knocked [prone](Mechanics/Rules/conditions.md#Prone),\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained), or [stunned](Mechanics/Rules/conditions.md#Stunned).\
    \ Equipment worn or carried by the mummy lord remain in its possession."
  "name": "Whirlwind of Sand (Costs 2 Actions)"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Gorka%20Tharn.webp"
```
^statblock