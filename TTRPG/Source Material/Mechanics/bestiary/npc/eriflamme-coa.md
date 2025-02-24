---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/28
- monster/size/gargantuan
- monster/type/elemental
statblock: inline
aliases: ["Eriflamme"]
---
# [Eriflamme](Mechanics\bestiary\npc/eriflamme-coa.md)
*Source: Chains of Asmodeus p. 121*  

```statblock
"name": "Eriflamme (CoA)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Unaligned"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "518"
"hit_dice": "28d20 + 224"
"stats":
- !!int "30"
- !!int "11"
- !!int "26"
- !!int "5"
- !!int "10"
- !!int "10"
"speed": "40 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "8"
  "Intelligence": !!int "5"
"skillsaves":
  "Athletics": !!int "18"
  "Arcana": !!int "5"
"damage_immunities": "fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 120 ft., passive Perception 10"
"languages": ""
"cr": "28"
"traits":
- "desc": "If the Eriflamme fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The Eriflamme has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The Eriflamme makes four Claw attacks. It can replace one of the attacks\
    \ with a Bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +18 to hit, reach 15 ft., one target. Hit: 20\
    \ (3d6 + 10) slashing damage plus 7 (2d6) fire damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +18 to hit, reach 10 ft., one target. Hit: 24\
    \ (4d6 + 10) piercing damage plus 33 (6d10) fire damage."
  "name": "Bite"
- "desc": "All the Eriflamme's fire elementals vanish and the Eriflamme reappears\
    \ in one of their spaces. The Eriflamme's hit points are equivalent to the combined\
    \ hit points of the fire elementals."
  "name": "Reform"
"reactions":
- "desc": "As a reaction to taking damage, the Eriflamme can split into fire elementals\
    \ and reduce the damage to 0. The Eriflamme can form up to 10 [fire elementals](Mechanics/bestiary/elemental/fire-elemental.md),\
    \ splitting its remaining hit points between them. The fire elementals appear\
    \ in spaces adjacent to or within the Eriflamme's old location, and all act on\
    \ the Eriflamme's initiative. They gain a +5 bonus to attack rolls and have the\
    \ Eriflamme's Reform action."
  "name": "Split (2/Day)"
"legendary_actions":
- "desc": "The Eriflamme makes a Claw attack, which deals force damage instead of\
    \ slashing damage if it hits."
  "name": "Slam"
- "desc": "The Eriflamme moves up to half its speed. It can fly during this movement."
  "name": "Fireglide"
- "desc": "The Eriflamme makes a Bite attack with advantage."
  "name": "Chomp (Costs 2 Actions)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Eriflamme.webp"
```
^statblock