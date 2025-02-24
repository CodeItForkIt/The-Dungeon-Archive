---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/13
- monster/environment/farmland
- monster/environment/hill
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Haugbui"]
---
# [Haugbui](Mechanics\bestiary\undead/haugbui-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 231*  

*A thick swirl of dust rises, settles, and forms the vague outline of a human—two points of yellow light shine where its eyes should be, staring malevolently.*

## Mound Haunter

A haugbui is an undead spirit tied to its burial mound or barrow. It serves as a familiar, protective spirit to nearby farmsteads or villages, so long as tribute is regularly paid to the haugbui. Traditional offerings may include pouring the first beer from a barrel, leaving portions of meals out overnight, sacrificing blood or livestock, or burying a portion of any income in the mound. A freshly-woken haugbui devours the remains of creatures it was buried with, such as a hawk, hound, or horse.

## Milder Spirits

Haugbuis are similar to vættir but much older. They are more humble and less prone to taking umbrage, and indeed, a great many haugbui have long since forgotten their own names. They are not quick to spill blood when irritated and thus are viewed with greater tolerance by the living.

## Scrye and Watch

Haugbuis prefer to watch over their people from within their mound, and only come forth over the most grievous insults or injuries. They can do a great deal from within their mounds thanks to their scrying ability.

```statblock
"name": "Haugbui (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"stats":
- !!int "18"
- !!int "20"
- !!int "18"
- !!int "15"
- !!int "20"
- !!int "16"
"speed": "0 ft., fly 40 ft. (hover)"
"saves":
  "Dexterity": !!int "10"
  "Wisdom": !!int "10"
  "Constitution": !!int "9"
"skillsaves":
  "Intimidation": !!int "8"
  "Religion": !!int "12"
  "Perception": !!int "10"
  "History": !!int "7"
  "Arcana": !!int "7"
"damage_resistances": "acid, cold, fire, lightning, necrotic, thunder"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "truesight 60 ft., passive Perception 20"
"languages": "telepathy 120 ft. all the languages it knew in life"
"cr": "13"
"traits":
- "desc": "The haugbui casts one of the following spells, requiring no components\
    \ and using Wisdom as the spellcasting ability (spell save DC 18):\n\nAt will:\
    \ [dancing lights](Mechanics/spells/dancing-lights.md), [mending](Mechanics/spells/mending.md),\
    \ [purify food and drink](Mechanics/spells/purify-food-and-drink.md), [spare the\
    \ dying](Mechanics/spells/spare-the-dying.md)\n\n1/day each: [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [remove curse](Mechanics/spells/remove-curse.md)\n\n3/day each: [gust of\
    \ wind](Mechanics/spells/gust-of-wind.md), [telekinesis](Mechanics/spells/telekinesis.md)"
  "name": "Spellcasting"
- "desc": "The haugbui can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "While in sunlight, the haugbui has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that\
    \ rely on sight."
  "name": "Sunlight Sensitivity"
- "desc": "The haugbui has advantage on saving throws against any effect that turns\
    \ undead."
  "name": "Turn Resistance"
- "desc": "The hangbui doesn't require air, food, drink, or sleep."
  "name": "Undead Nature"
"actions":
- "desc": "The haugbui makes three Psychic Blast attacks. It can replace one attack\
    \ with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +10 to hit, range 120 ft., one target.\
    \ Hit: 27 (5d8 + 5) psychic damage."
  "name": "Psychic Blast"
- "desc": "The haugbui magically turns [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ until it attacks or casts a spell, or until its [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ ends (as if concentrating on a spell). Any equipment the haugbui wears or carries\
    \ is [invisible](Mechanics/Rules/conditions.md#Invisible) with it."
  "name": "Invisibility"
"bonus_actions":
- "desc": "While within 1 mile of its burial mound, the haugbui creates an [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ sensor within 5 miles of the mound for 1 minute. When it uses this bonus action\
    \ and as a bonus action on each of its turns for the duration, the haugbui can\
    \ switch between using its own senses and projecting its senses through the sensor.\
    \ While projecting its senses through the sensor, it can see, hear, telepathically\
    \ communicate, and cast spells as if it was in the sensor's space, and it is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ and [deafened](Mechanics/Rules/conditions.md#Deafened) with regard to its own\
    \ senses. The sensor can be dispelled (DC 14)."
  "name": "Sepulchral Scrying (Recharge 6)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Haugbui.webp"
```
^statblock

## Environment

farmland, hill