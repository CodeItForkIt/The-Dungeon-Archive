---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aitfr-fcd
- monster/cr/1
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Mercenary Envoy"]
---
# [Mercenary Envoy](Mechanics\bestiary\humanoid/mercenary-envoy-aitfr-fcd.md)
*Source: Adventures in the Forgotten Realms: From Cyan Depths p. 10*  

These mercenaries stand for the Banner of Blades and the Iron Lions at Tyreus's fortress, but they might not be representative of those armies. These are rank-and-file warriors capable of demonstrating coordinated attacks and formations. They are neither the most capable lieutenants nor the rough-andtumble masses of these small armies.

For the purposes of their Inspired Courage feature, the mercenaries of both companies consider each other allies while at the fortress—unless the adventurers do something to drive them apart.

```statblock
"name": "Mercenary Envoy (AitFR-FCD)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "[chain shirt](Mechanics/items/chain-shirt.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"stats":
- !!int "15"
- !!int "15"
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "9"
"speed": "30 ft."
"saves":
  "Strength": !!int "4"
  "Constitution": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "1"
"traits":
- "desc": "The mercenary has advantage on savings throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
    \ or [restrained](Mechanics/Rules/conditions.md#Restrained) while within 5 feet\
    \ of at least one ally."
  "name": "Inspired Courage"
- "desc": "Once per turn, the mercenary can deal an extra 7 (2d6) damage to a creature\
    \ it hits with a weapon attack if that creature is within 5 feet of an ally of\
    \ the mercenary that isn't [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Martial Advantage"
"actions":
- "desc": "The mercenary makes two longsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range\n\n100/400 ft., one target.\
    \ Hit: 7 (1d10 + 2) piercing damage."
  "name": "Heavy Crossbow"
"source":
- "AitFR-FCD"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AitFR-FCD/Mercenary%20Envoy.webp"
```
^statblock