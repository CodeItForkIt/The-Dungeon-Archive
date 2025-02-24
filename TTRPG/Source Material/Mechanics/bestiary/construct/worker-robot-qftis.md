---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/3
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Worker Robot"]
---
# [Worker Robot](Mechanics\bestiary\construct/worker-robot-qftis.md)
*Source: Quests from the Infinite Staircase p. 215*  

Worker robots are built for physical labor such as hauling cargo, construction, and maintenance, though some worker robots fill public-facing service roles. Antigravity technology and built-in tractor beams allow worker robots to effortlessly lift cargo and other heavy objects with their mechanical tentacles, which double as weapons if the robots are threatened or drafted for security purposes. A worker robot's voice is often utilitarian, programmed to use simple phrases without embellishment. Worker robots designed to be in public view—such as units that carry out deliveries, repairs, or transportation—have voices that more closely mimic those of their creators. These robots employ mollifying phrases or make shallow but pleasant small talk.

## Robots

Robots are Constructs created for heavy labor, menial tasks, or routine security. Despite robots' hardy construction, their circuitry is prone to overload if exposed to strong electrical currents. A robot has a pair of small appendages for fine motor control and object manipulation, as well as two larger appendages specialized for its role. Robots are programmed with intelligence, understanding, and usually loyalty to their creators. Despite that, long-operating robots sometimes develop their own personalities and ideas. Robots that endure long stretches of isolation, mistreatment, or neglect are prone to malfunctions. Some robots become despondent or cruel, while others obsessively repeat their last directive or adopt new, peculiar purposes of their own.

```statblock
"name": "Worker Robot (QftIS)"
"size": "Medium"
"type": "construct"
"alignment": "typically  Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "20"
- !!int "9"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "10"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Athletics": !!int "9"
"damage_resistances": "acid, fire"
"damage_immunities": "cold, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common plus the languages spoken by its creator"
"cr": "3"
"traits":
- "desc": "When the robot takes lightning damage, it must succeed on a DC 10 Constitution\
    \ saving throw or have the [stunned](Mechanics/Rules/conditions.md#Stunned) condition\
    \ until the start of its next turn."
  "name": "Lightning Overload"
"actions":
- "desc": "The robot makes two Cargo Tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 9\
    \ (1d8 + 5) bludgeoning damage. If the target is a Medium or smaller creature,\
    \ it has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 15). The robot has two cargo tentacles, each of which can grapple one target."
  "name": "Cargo Tentacle"
- "desc": "The robot casts [Telekinesis](Mechanics/spells/telekinesis.md), targeting\
    \ only creatures with the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition or objects. It requires no spell components and uses Wisdom as the\
    \ spellcasting ability."
  "name": "Tractor Beam"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Worker%20Robot.webp"
```
^statblock