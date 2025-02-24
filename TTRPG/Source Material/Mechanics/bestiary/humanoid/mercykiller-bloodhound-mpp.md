---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
aliases: ["Mercykiller Bloodhound"]
---
# [Mercykiller Bloodhound](Mechanics\bestiary\humanoid/mercykiller-bloodhound-mpp.md)
*Source: Morte's Planar Parade p. 60, Sigil and the Outlands, Turn of Fortune's Wheel*  

Clad in black armor and spiked gauntlets that end in steel claws, bloodhounds hunt down those guilty of serious offenses in Sigil. These trackers pursue their targets across the planes.

```statblock
"name": "Mercykiller Bloodhound (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md)"
"hp": !!int "104"
"hit_dice": "16d8 + 48"
"stats":
- !!int "17"
- !!int "12"
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "8"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "8"
  "Survival": !!int "8"
"senses": "passive Perception 18"
"languages": "Common plus one more language"
"cr": "7"
"traits":
- "desc": "The bloodhound can sense the presence of portals within 30 feet of itself,\
    \ including inactive portals, and instinctively knows the destination of each\
    \ portal."
  "name": "Portal Sense"
"actions":
- "desc": "The bloodhound makes three Clawed Gauntlet attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage plus 10 (3d6) necrotic damage."
  "name": "Clawed Gauntlet"
"bonus_actions":
- "desc": "The bloodhound attempts to place a magical mark on a creature it can see\
    \ within 30 feet of itself. The target must succeed on a DC 13 Charisma saving\
    \ throw or become cursed for 24 hours. A creature missing any of its hit points\
    \ has disadvantage on this saving throw. While cursed in this way, the bloodhound\
    \ can sense the direction and distance to the target as long as the two are on\
    \ the same plane of existence. If the target isn't on the same plane, the bloodhound\
    \ knows what plane the target is on."
  "name": "Marked for Pursuit (3/Day)"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Mercykiller%20Bloodhound.webp"
```
^statblock