---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/farmland
- monster/environment/urban
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Ghost Knight"]
---
# [Ghost Knight](Mechanics\bestiary\undead/ghost-knight-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 199*  

*The skeleton's armor creaks as its decaying mount shifts and emits a ghostly whinny. The skeleton sets its lance, skulls dangling from the hilt, and charges.*

## Servants Beyond Death

Some orders of knighthood require service after death; ghost knights are one such group. Both the willing and the conscripts enter the order as living men and women, and those who serve bravely and loyally for five years or more are "raised up" into the ranks of the undead by their undead lords, becoming fully-fledged ghost knights.

## Undead Mounts

To advance through the ranks of the order, the ghost knight accepts the blessing of undeath, which extends to its mount. Riding an undead warhorse (use the statistics of a warhorse skeleton), the ghost knight is a dangerous foe, spearing enemies with its lance and trampling foes under its mount's hooves.

```statblock
"name": "Ghost Knight (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "[half plate](Mechanics/items/half-plate-armor.md)"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"stats":
- !!int "17"
- !!int "15"
- !!int "14"
- !!int "8"
- !!int "10"
- !!int "7"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "6"
  "Animal Handling": !!int "3"
  "Stealth": !!int "5"
  "Perception": !!int "3"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common"
"cr": "7"
"traits":
- "desc": "The ghost knight can't be knocked [prone](Mechanics/Rules/conditions.md#Prone),\
    \ dismounted, or moved against its will while mounted."
  "name": "Locked Saddle"
- "desc": "The ghost knight is rarely seen without its warhorse skeleton mount. The\
    \ warhorse skeleton wears custom barding that raises its Armor Class to 15, and\
    \ it has immunity to necrotic damage. While the ghost knight is mounted, its mount\
    \ can't be [charmed](Mechanics/Rules/conditions.md#Charmed) or [frightened](Mechanics/Rules/conditions.md#Frightened)."
  "name": "Mounted Warrior"
- "desc": "The ghost knight's weapon attacks are magical. When the knight hits with\
    \ any weapon, the weapon deals an extra 2d6 necrotic damage (included in the\
    \ attack)."
  "name": "Necrotic Weapons"
- "desc": "If the ghost knight moves at least 20 feet straight toward a creature while\
    \ mounted and then hits with a Lance attack on the same turn, the ghost knight\
    \ can use a bonus action to command its mount to make one melee weapon attack\
    \ against that creature as a reaction."
  "name": "Spirited Charge"
- "desc": "The ghost knight and any undead within 30 feet of it have advantage on\
    \ saving throws against effects that turn undead."
  "name": "Turning Defiance"
- "desc": "The ghost knight doesn't require air, food, drink, or sleep."
  "name": "Undead Nature"
"actions":
- "desc": "The ghost knight makes three Battleaxe or Lance attacks. If the ghost knight\
    \ is mounted, it can make two Battleaxe or Lance attacks, and its mount can make\
    \ one melee weapon attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands,\
    \ plus 7 (2d6) necrotic damage."
  "name": "Battleaxe"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 9\
    \ (1d12 + 3) piercing damage plus 7 (2d6) necrotic damage."
  "name": "Lance"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ghost%20Knight.webp"
```
^statblock

## Environment

farmland, urban