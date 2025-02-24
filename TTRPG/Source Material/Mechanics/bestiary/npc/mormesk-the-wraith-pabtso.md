---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/5
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Mormesk the Wraith"]
---
# [Mormesk the Wraith](Mechanics\bestiary\npc/mormesk-the-wraith-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 70*  

```statblock
"name": "Mormesk the Wraith (PaBTSO)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "6"
- !!int "16"
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "15"
"speed": "0 ft., fly 60 ft. (hover)"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks that aren't silvered"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "the languages it knew in life"
"cr": "5"
"traits":
- "desc": "Mormesk can move through other creatures and objects as if they were difficult\
    \ terrain. It takes 5 (1d10) force damage if it ends its turn inside an object."
  "name": "Incorporeal Movement"
- "desc": "While in sunlight, Mormesk has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 21\
    \ (4d8 + 3) necrotic damage. The target must succeed on a DC 14 Constitution\
    \ saving throw or its hit point maximum is reduced by an amount equal to the damage\
    \ taken. This reduction lasts until the target finishes a long rest. The target\
    \ dies if this effect reduces its hit point maximum to 0."
  "name": "Life Drain"
- "desc": "Mormesk targets a humanoid within 10 feet of it that has been dead for\
    \ no longer than 1 minute and died violently. The target's spirit rises as a [specter](Mechanics/bestiary/undead/specter.md)\
    \ in the space of its corpse or in the nearest unoccupied space. The [specter](Mechanics/bestiary/undead/specter.md)\
    \ is under Mormesk's control. Mormesk can have no more than seven specters under\
    \ its control at one time."
  "name": "Create Specter"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Mormesk%20the%20Wraith.webp"
```
^statblock