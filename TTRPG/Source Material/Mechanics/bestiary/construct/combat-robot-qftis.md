---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/6
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Combat Robot"]
---
# [Combat Robot](Mechanics\bestiary\construct/combat-robot-qftis.md)
*Source: Quests from the Infinite Staircase p. 214*  

Combat robots are designed for security or military action. They make able sentries and are usually programmed to take intruders prisoner before resorting to lethal force. Combat robots signal their pursuit with built-in sirens and flashing lights, warning nearby creatures of their imminent arrival with an intimidating display. Combat robots display a wide range of voices. Some units are clearly designed to intimidate, while others offer canned, upbeat platitudes in pleasant tones even while subduing opponents.

## Robots

Robots are Constructs created for heavy labor, menial tasks, or routine security. Despite robots' hardy construction, their circuitry is prone to overload if exposed to strong electrical currents. A robot has a pair of small appendages for fine motor control and object manipulation, as well as two larger appendages specialized for its role. Robots are programmed with intelligence, understanding, and usually loyalty to their creators. Despite that, long-operating robots sometimes develop their own personalities and ideas. Robots that endure long stretches of isolation, mistreatment, or neglect are prone to malfunctions. Some robots become despondent or cruel, while others obsessively repeat their last directive or adopt new, peculiar purposes of their own.

```statblock
"name": "Combat Robot (QftIS)"
"size": "Medium"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "20"
- !!int "14"
- !!int "17"
- !!int "10"
- !!int "15"
- !!int "10"
"speed": "40 ft."
"saves":
  "Charisma": !!int "3"
  "Constitution": !!int "6"
"skillsaves":
  "Intimidation": !!int "6"
  "Athletics": !!int "8"
  "Perception": !!int "5"
"damage_resistances": "acid, fire"
"damage_immunities": "cold, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Common plus the languages spoken by its creator"
"cr": "6"
"traits":
- "desc": "When the robot takes lightning damage, it must succeed on a DC 10 Constitution\
    \ saving throw or have the [stunned](Mechanics/Rules/conditions.md#Stunned) condition\
    \ until the start of its next turn."
  "name": "Lightning Overload"
"actions":
- "desc": "The robot makes two Tentacle attacks or three Laser Beam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 10\
    \ (1d10 + 5) bludgeoning damage. If the target is a Medium or smaller creature,\
    \ it has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 16). While [grappled](Mechanics/Rules/conditions.md#Grappled), the target\
    \ also has the [restrained](Mechanics/Rules/conditions.md#Restrained) condition.\
    \ The robot has two tentacles, each of which can grapple one target."
  "name": "Tentacle"
- "desc": "Ranged Weapon Attack: +5 to hit, range 120 ft., one target. Hit:\
    \ 16 (4d6 + 2) radiant damage."
  "name": "Laser Beam"
- "desc": "The robot fires a grenade at a point it can see within 120 feet of itself.\
    \ The grenade explodes in a 20-foot-radius sphere centered on that point, creating\
    \ one of the following effects (robot's choice):"
  "name": "Grenade Launcher (Recharge 5-6)"
- "desc": "Each creature in the sphere must make a DC 15 Dexterity saving throw, taking\
    \ 21 (6d6) force damage on a failed save or half as much damage on a successful\
    \ one."
  "name": "Concussion Grenade"
- "desc": "Each creature in the sphere must succeed on a DC 15 Constitution saving\
    \ throw or have the [unconscious](Mechanics/Rules/conditions.md#Unconscious) condition\
    \ for 1 hour. The condition ends on a creature early if the creature takes damage\
    \ or if another creature uses an action to shake it awake."
  "name": "Sleep Grenade"
"bonus_actions":
- "desc": "The robot takes the Dash or Disengage action."
  "name": "Emergency Speed (2/Day)"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Combat%20Robot.webp"
```
^statblock