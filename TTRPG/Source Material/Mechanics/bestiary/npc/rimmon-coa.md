---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/20
- monster/size/medium
- monster/type/fiend/devil
statblock: inline
aliases: ["Rimmon"]
---
# [Rimmon](Mechanics\bestiary\npc/rimmon-coa.md)
*Source: Chains of Asmodeus p. 209*  

```statblock
"name": "Rimmon (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "262"
"hit_dice": "25d8 + 150"
"stats":
- !!int "18"
- !!int "17"
- !!int "22"
- !!int "27"
- !!int "25"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "13"
  "Intelligence": !!int "14"
  "Constitution": !!int "12"
"skillsaves":
  "Sleight of Hand": !!int "9"
  "Investigation": !!int "14"
  "Perception": !!int "13"
  "History": !!int "20"
  "Arcana": !!int "20"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 23"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "20"
"traits":
- "desc": "Rimmon has advantage to hit creatures under an infernal contract and when\
    \ he hits such creatures he delivers an additional 9 (2d8) damage of a type\
    \ the target is most vulnerable to. A creature bound under an infernal contract\
    \ also makes all saving throws against effects originating from Rimmon with disadvantage."
  "name": "Contractually Obligated"
- "desc": "Magical darkness doesn't impede Rimmon's darkvision."
  "name": "Devil's Sight"
- "desc": "Rimmon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Rimmon makes four Sharpened Tongue or Wordplay attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 11\
    \ (3d4 + 4) slashing damage."
  "name": "Sharpened Tongue"
- "desc": "Ranged Spell Attack: +14 to hit, range 60 ft., one target. Hit: 35\
    \ (6d8 + 8) psychic damage."
  "name": "Wordplay"
- "desc": "Rimmon emits a burst of energy that arcs towards a creature he can see\
    \ within 150 feet of him. Three bolts then leap from that target to as many as\
    \ three other targets, each of which must be within 30 feet of the first target.\
    \ A target must make a DC 22 Dexterity saving throw, taking 63 (14d8) damage\
    \ on a failed save, or half as much damage on a successful one. The damage type\
    \ inflicted is of a type the first target is most vulnerable to."
  "name": "Connected Clauses (1/Day)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Rimmon.webp"
```
^statblock