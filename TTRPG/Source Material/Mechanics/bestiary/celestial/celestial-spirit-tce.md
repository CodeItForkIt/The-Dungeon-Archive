---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tce
- monster/cr/
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Celestial Spirit"]
---
# [Celestial Spirit](Mechanics\bestiary\celestial/celestial-spirit-tce.md)
*Source: Tasha's Cauldron of Everything p. 110*  

```statblock
"name": "Celestial Spirit (TCE)"
"size": "Large"
"type": "celestial"
"alignment": "Unaligned"
"ac_class": "11 + the level of the spell (natural armor) + 2 (Defender only)"
"stats":
- !!int "16"
- !!int "14"
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "16"
"speed": "30 ft., fly 40 ft."
"damage_resistances": "radiant"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Celestial, understands the languages you speak"
"actions":
- "desc": "The celestial makes a number of attacks equal to half this spell's level\
    \ (rounded down)."
  "name": "Multiattack"
- "desc": "Ranged Weapon Attack: YourSpellAttack to hit, range 150/600 ft., one\
    \ target. Hit: 2d6 + 2 + the spell's level radiant damage."
  "name": "Radiant Bow (Avenger Only)"
- "desc": "Melee Weapon Attack: YourSpellAttack to hit, reach 5 ft., one target.\
    \ Hit: 1d10 + 3 + the spell's level radiant damage, and the celestial can\
    \ choose itself or another creature it can see within 10 feet of the target. The\
    \ chosen creature gains 1d10 temporary hit points."
  "name": "Radiant Mace (Defender Only)"
- "desc": "The celestial touches another creature. The target magically regains hit\
    \ points equal to 2d8 + the spell's level."
  "name": "Healing Touch (1/Day)"
"source":
- "TCE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TCE/Celestial%20Spirit.webp"
```
^statblock