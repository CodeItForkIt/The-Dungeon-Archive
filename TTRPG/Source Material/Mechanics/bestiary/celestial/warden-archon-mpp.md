---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/8
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Warden Archon"]
---
# [Warden Archon](Mechanics\bestiary\celestial/warden-archon-mpp.md)
*Source: Morte's Planar Parade p. 18, Sigil and the Outlands, Turn of Fortune's Wheel*  

Warden archons are vigilant, ursine guardians of portals and paths connected to goodly realms. They have powerfully built, bipedal bodies with the heads of great bears and eyes like pools of silvery light. When warden archons speak, glimmering radiance shines from within their mouths, punctuating their deep, resonant voices.

A warden archon knows when a creature uses a portal the archon is tasked to guard, and it moves swiftly to interrogate any who cross that planar boundary. If an invader enters the archon's plane, the warden strikes with claw and tooth, using its powerful bite to magically mark the intruder, which the archon pursues relentlessly.

## Archons

Archons are denizens of the Seven Heavens of Mount Celestia. Created by the powers of order and benevolence, archons defend their home from fiendish incursions and safeguard those threatened by wicked forces. Archons are skilled communicators, able to speak all the languages of the multiverse. When pushed into combat, they prefer to subdue foes. However, against Fiends, archons are wrathful combatants, manifesting the righteous vengeance of Mount Celestia to strike down the wicked.

Each archon's form corresponds to its place within the Celestial hierarchy. When faced in battle, archons radiate the full fury of the Upper Planes, bolstering their allies and cowing their foes.

```statblock
"name": "Warden Archon (MPP)"
"size": "Large"
"type": "celestial"
"alignment": "typically  Lawful Good"
"ac": !!int "18"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md)"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "20"
- !!int "10"
- !!int "17"
- !!int "15"
- !!int "18"
- !!int "18"
"speed": "30 ft., climb 30 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Athletics": !!int "8"
  "Perception": !!int "10"
  "Arcana": !!int "5"
"damage_immunities": "lightning"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)"
"senses": "darkvision 120 ft., truesight 30 ft., passive Perception 20"
"languages": "all"
"cr": "8"
"traits":
- "desc": "The archon casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 15):\n\nAt will:\
    \ [detect evil and good](Mechanics/spells/detect-evil-and-good.md)\n\n1/day\
    \ each: [aid](Mechanics/spells/aid.md), [continual flame](Mechanics/spells/continual-flame.md),\
    \ [protection from evil and good](Mechanics/spells/protection-from-evil-and-good.md),\
    \ [scrying](Mechanics/spells/scrying.md) (as an action)"
  "name": "Spellcasting"
- "desc": "As long as the archon doesn't have the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition, each creature of the archon's choice that starts its turn within\
    \ 20 feet of the archon must make a DC 15 Wisdom saving throw. On a failed save,\
    \ the creature has the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition until the start of its next turn. On a successful save, the creature\
    \ is immune to all archons' Aura of Menace for 24 hours."
  "name": "Aura of Menace"
- "desc": "The archon can't be surprised. Moreover, it knows when any creature uses\
    \ a portal it is assigned to guard."
  "name": "Eternal Vigil"
"actions":
- "desc": "The archon makes two Claw attacks and one Tracker's Bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage. If the target is a Medium or smaller creature,\
    \ the target has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition\
    \ (escape DC 18). The archon can have only one creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ in this way at a time."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 15\
    \ (3d6 + 5) piercing damage. If the target is a creature, for the next 24 hours,\
    \ the archon knows the distance and direction to the target while they are both\
    \ on the same plane of existence."
  "name": "Tracker's Bite"
- "desc": "The archon teleports, along with any equipment it is wearing or carrying,\
    \ to an unoccupied space it can see within 120 feet of itself."
  "name": "Teleport"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Warden%20Archon.webp"
```
^statblock