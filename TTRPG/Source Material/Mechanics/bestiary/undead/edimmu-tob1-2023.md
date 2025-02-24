---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/desert
- monster/environment/grassland
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Edimmu"]
---
# [Edimmu](Mechanics\bestiary\undead/edimmu-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 154*  

*An evil wind swirls out of the desert, parching those it touches and whispering evil plans.*

## Bitter Exiles

Desert and plains tribes often exile their criminals to wander as outcasts. A banished criminal who dies of thirst sometimes rises as an edimmu, a hateful undead that blames all sentient living beings for its fate.

## Rise Again

Unless its body is found and given a proper burial, an edimmu is nearly impossible to destroy. Edimmus rarely venture more than a mile from their remains, but they sometimes follow prey they have cursed to seal the creature's fate. Once that creature is slain, they return to the site of their demise.

```statblock
"name": "Edimmu (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "1"
- !!int "19"
- !!int "16"
- !!int "12"
- !!int "18"
- !!int "13"
"speed": "0 ft., fly 60 ft. (hover)"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 14"
"languages": "understands Common but can't speak"
"cr": "4"
"traits":
- "desc": "The edimmu can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "If destroyed, an edimmu rises again in 2d4 days, regaining all its hp\
    \ and becoming active again. When the edimmu rises, it appears within 5 feet of\
    \ its remains. Only burying its mortal remains in consecrated or hallowed ground\
    \ prevents this trait from functioning."
  "name": "Rejuvenation"
- "desc": "The edimmu doesn't require air, food, drink, or sleep."
  "name": "Undead Nature"
- "desc": "The edimmu has advantage on attack rolls against creatures made of or gaining\
    \ power from magical water, such as water elementals, water jinnborn, water genies,\
    \ and sorcerers with water-based origins. In addition, such creatures have disadvantage\
    \ on the saving throw against the edimmu's Draining Touch and Multiattack."
  "name": "Water Siphon"
"actions":
- "desc": "The edimmu makes two Draining Touch attacks. If both attacks hit one creature\
    \ that isn't a Construct or Undead, the target must succeed on a DC 14 Constitution\
    \ saving throw or suffer one level of [exhaustion](Mechanics/Rules/conditions.md#Exhaustion).\
    \ A creature that fails this saving throw by 5 or more is also [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ until the end of its next turn."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one creature. Hit: 13\
    \ (2d8 + 4) necrotic damage, and the target must succeed on a DC 14 Constitution\
    \ saving throw or its hp maximum is reduced by an amount equal to the damage taken.\
    \ This reduction lasts until the creature finishes a long rest after drinking\
    \ 1 pint of water. The target dies if this effect reduces its hp maximum to 0."
  "name": "Draining Touch"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Edimmu.webp"
```
^statblock

## Environment

desert, grassland