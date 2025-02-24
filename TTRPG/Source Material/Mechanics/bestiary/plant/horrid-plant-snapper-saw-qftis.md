---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/4
- monster/size/large
- monster/type/plant
statblock: inline
aliases: ["Horrid Plant Snapper Saw"]
---
# [Horrid Plant Snapper Saw](Mechanics\bestiary\plant/horrid-plant-snapper-saw-qftis.md)
*Source: Quests from the Infinite Staircase p. 204*  

```statblock
"name": "Horrid Plant Snapper Saw (QftIS)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "6"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"stats":
- !!int "18"
- !!int "3"
- !!int "17"
- !!int "1"
- !!int "10"
- !!int "1"
"speed": "5 ft."
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened)"
"senses": "blindsight 60 ft. (can't see beyond this radius), passive Perception 10"
"languages": ""
"cr": "4"
"traits":
- "desc": "If the horrid plant is motionless at the start of combat, it has advantage\
    \ on its initiative roll. Moreover, if a creature hasn't observed the horrid plant\
    \ move or act, that creature must succeed on a DC 18 Intelligence ([Nature](Mechanics/Rules/skills.md#Nature))\
    \ check to discern that the horrid plant isn't an ordinary plant."
  "name": "False Appearance"
"actions":
- "desc": "The horrid plant makes two Tendril attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 30 ft., one target. Hit: 7\
    \ (2d6) bludgeoning damage. If the target is a Huge or smaller creature, it\
    \ has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 14), and the horrid plant can pull the target up to 25 feet closer to itself.\
    \ Until the grapple ends, the target has the [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ condition, and the horrid plant can't use the same tendril on another target.\
    \ The horrid plant has two tendrils."
  "name": "Tendril"
"bonus_actions":
- "desc": "Creatures within 10 feet of the horrid plant and not behind total cover\
    \ must make a DC 14 Dexterity saving throw, taking 21 (6d6) slashing damage\
    \ on a failed save or half as much damage on a successful one."
  "name": "Spiked Leaves"
"source":
- "QftIS"
```
^statblock