---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/underdark
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Horakh"]
---
# [Horakh](Mechanics\bestiary\monstrosity/horakh-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 234*  

*Resembling a cave cricket the size of a dog, this beast's black, chitinous thorax is topped by a translucent digestive sac. Halfdigested eyeballs of various sizes and colors float in the sac.*

## Leaping Claws

Insectoid killing machines with a penchant for consuming their victim's eyes, the bloodthirsty horakhs travel in small packs and make lightning-fast attacks against the weak or vulnerable. Their powerful rear legs enable enormous bounding leaps, while the sharp hooks at the end of their powerful claws help them to climb and latch onto prey. Heads dominated by scooped mandibles can shoot forward like pistons, shearing meat from bone.

## Leaping Screech

When attacking, a horakh leaps from its hiding spots while making a deafening screech. Horakhs are highly mobile on the battlefield. If threatened, horakhs return to the shadows to attack from a more advantageous position.

## Herd the Blinded

After blinding their prey, horakhs often herd the blind like sheep until they are ready to consume their prey and sometimes even use the blinded prey as bait to capture other creatures. Many an explorer has been ambushed, blinded, and condemned to death in the bowels of the earth by these predators.

```statblock
"name": "Horakh (ToB1-2023)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "161"
"hit_dice": "19d8 + 76"
"stats":
- !!int "18"
- !!int "19"
- !!int "19"
- !!int "5"
- !!int "15"
- !!int "10"
"speed": "40 ft., climb 30 ft."
"saves":
  "Dexterity": !!int "8"
"skillsaves":
  "Athletics": !!int "8"
  "Stealth": !!int "8"
  "Perception": !!int "6"
"senses": "darkvision 60 ft., tremorsense 30 ft., passive Perception 20"
"languages": "understands Undercommon but can't speak"
"cr": "9"
"traits":
- "desc": "If the horakh reduces a creature to 0 hp with a Bite attack or as a bonus\
    \ action while within 5 feet of a creature with 0 hp, the horakh can implant an\
    \ egg in the creature. The implanted egg rests in the creature's eye socket for\
    \ 14 days while it incubates. A host creature can carry only one horakh egg to\
    \ term at a time. While the egg is implanted, the host can't use its eye and has\
    \ disadvantage on attack rolls and on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on sight. Exactly 24 hours before the egg hatches, the host\
    \ becomes [blinded](Mechanics/Rules/conditions.md#Blinded). When the egg hatches,\
    \ the young horakh erupts from the host's head, killing the host in the process.\n\
    \nA [lesser restoration](Mechanics/spells/lesser-restoration.md) spell cast on\
    \ the host destroys the egg. Alternatively, a creature other than the host can\
    \ take an action to remove the egg by succeeding on a DC 16 Wisdom ([Medicine](Mechanics/Rules/skills.md#Medicine))\
    \ check. On a failure, the host takes 9 (2d8) slashing damage."
  "name": "Implant Egg"
- "desc": "The horakh's long jump is up to 30 feet and its high jump is up to 15 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "The horakh makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 22\
    \ (4d8 + 4) piercing damage. If the horakh scores a critical hit, it removes\
    \ one of the target's eyes, provided the target has eyes, and places the eye in\
    \ a fluid sac on its thorax. While missing half or less of its total number of\
    \ eyes, the target has disadvantage on attack rolls and Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on sight. While missing more than half its total number of\
    \ eyes, the target is [blinded](Mechanics/Rules/conditions.md#Blinded) until its\
    \ sight is restored."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 17\
    \ (3d8 + 4) slashing damage."
  "name": "Claw"
"bonus_actions":
- "desc": "While in dim light or darkness, the horakh takes the Hide action."
  "name": "Shadow Stealth"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Horakh.webp"
```
^statblock

## Environment

underdark