---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/
- monster/size/large
- monster/type/dragon
statblock: inline
aliases: ["Draconic Spirit"]
---
# [Draconic Spirit](Mechanics\bestiary\dragon/draconic-spirit-ftd.md)
*Source: Fizban's Treasury of Dragons p. 21*  

```statblock
"name": "Draconic Spirit (FTD)"
"size": "Large"
"type": "dragon"
"alignment": "Neutral"
"ac_class": "14 + the level of the spell (natural armor)"
"stats":
- !!int "19"
- !!int "14"
- !!int "17"
- !!int "10"
- !!int "14"
- !!int "14"
"speed": "30 ft., fly 60 ft., swim 30 ft."
"damage_resistances": "acid, cold, fire, lightning, poison (Chromatic and Metallic\
  \ Only)"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 30 ft., darkvision 60 ft., passive Perception 12"
"languages": "Draconic, understands the languages you speak"
"traits":
- "desc": "When you summon the dragon, choose one of its damage resistances. You have\
    \ resistance to the chosen damage type until the spell ends."
  "name": "Shared Resistances"
"actions":
- "desc": "The dragon makes a number of Rend attacks equal to half the spell's level\
    \ (rounded down), and it uses Breath Weapon."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: your spell attack modifier to hit, reach 10 ft.,\
    \ one target. Hit: 1d6 + 4 + the spell's level piercing damage."
  "name": "Rend"
- "desc": "The dragon exhales destructive energy in a 30-foot cone. Each creature\
    \ in that area must make a Dexterity saving throw against your spell save DC.\
    \ A creature takes 2d6 damage of a type this dragon has resistance to (your\
    \ choice) on a failed save, or half as much damage on a successful one."
  "name": "Breath Weapon"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Draconic%20Spirit.webp"
```
^statblock