---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/23
- monster/size/huge
- monster/type/celestial/titan
statblock: inline
aliases: ["Ulamog"]
---
# [Ulamog](Mechanics\bestiary\npc/ulamog-psz.md)
*Source: Plane Shift: Zendikar p. 38*  

```statblock
"name": "Ulamog (PSZ)"
"size": "Huge"
"type": "celestial"
"subtype": "titan"
"alignment": "Chaotic Good or Neutral Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "313"
"hit_dice": "19d12 + 190"
"stats":
- !!int "30"
- !!int "21"
- !!int "30"
- !!int "21"
- !!int "22"
- !!int "27"
"speed": "50 ft., fly 50 ft., swim 50 ft."
"saves":
  "Charisma": !!int "15"
  "Wisdom": !!int "13"
  "Intelligence": !!int "12"
  "Strength": !!int "17"
"skillsaves":
  "Insight": !!int "13"
  "Persuasion": !!int "15"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks; psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "truesight 120 ft., passive Perception 16"
"languages": "all"
"cr": "23"
"traits":
- "desc": "Ulamog's innate spellcasting ability is Charisma (spell save DC 23, +15\
    \ to hit with spell attacks). It can innately cast the following spells, requiring\
    \ no material components:\n\nAt will: [greater restoration](Mechanics/spells/greater-restoration.md),\
    \ [pass without trace](Mechanics/spells/pass-without-trace.md), [water breathing](Mechanics/spells/water-breathing.md),\
    \ [water walk](Mechanics/spells/water-walk.md)\n\n1/day each: [commune](Mechanics/spells/commune.md),\
    \ [dispel evil and good](Mechanics/spells/dispel-evil-and-good.md), [earthquake](Mechanics/spells/earthquake.md),\
    \ [fire storm](Mechanics/spells/fire-storm.md), [plane shift](Mechanics/spells/plane-shift.md)\
    \ (self only)"
  "name": "Innate Spellcasting"
- "desc": "If Ulamog fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Ulamog has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Ulamog's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 31\
    \ (6d6 + 10) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 15 Constitution saving throw or be [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ until the end of Ulamog's next turn."
  "name": "Maul"
- "desc": "Ranged Spell Attack: +15 to hit, range 600 ft., one target. Hit:\
    \ 24 (7d6) damage of one of the following types (empyrean's choice): acid, cold,\
    \ fire, force, lightning, radiant, or thunder."
  "name": "Bolt"
"legendary_actions":
- "desc": "Ulamog makes one attack."
  "name": "Attack"
- "desc": "Ulamog bolsters all nonhostile creatures within 120 feet of it until the\
    \ end of its next turn. Bolstered creatures can't be [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ or [frightened](Mechanics/Rules/conditions.md#Frightened), and they gain advantage\
    \ on ability checks and saving throws until the end of Ulamog's next turn."
  "name": "Bolster"
- "desc": "Ulamog strikes the ground with its maul, triggering an earth tremor. All\
    \ other creatures on the ground within 60 feet of Ulamog must succeed on a DC\
    \ 25 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Trembling Strike (Costs 2 Actions)"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Ulamog.webp"
```
^statblock