---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/urban
- monster/size/medium
- monster/type/fey
statblock: inline
aliases: ["Blood Hag"]
---
# [Blood Hag](Mechanics\bestiary\fey/blood-hag-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 226*  

*This bent-backed crone has long, leathery arms and cruel, flesh-shearing talons. Her face is a misshapen mass of leathery flesh with a bulbous nose, like a gnarled knot on an old oak tree, and her hair falls in ringlets of wriggling worms.*

Blood hags have long skulked on the fringes of society. The hags prey on mankind, stealing seed to propagate, blood to satisfy their insatiable thirst, and faces as trophies of these short-lived and bloody trysts.

## Worm Hair

A blood hag's hair is a morass of wriggling worms, ever-thirsty for fresh blood.

```statblock
"name": "Blood Hag (ToB1-2023)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"stats":
- !!int "20"
- !!int "16"
- !!int "18"
- !!int "19"
- !!int "21"
- !!int "17"
"speed": "30 ft., climb 30 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "7"
  "Constitution": !!int "8"
"skillsaves":
  "Intimidation": !!int "7"
  "Deception": !!int "7"
  "Stealth": !!int "7"
  "Perception": !!int "9"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 19"
"languages": "Common, Giant, Sylvan"
"cr": "11"
"traits":
- "desc": "The blood hag casts one of the following spells, requiring no material\
    \ components and using Wisdom as the spellcasting ability (spell save DC 17):\n\
    \nAt will: [disguise self](Mechanics/spells/disguise-self.md), [knock](Mechanics/spells/knock.md),\
    \ [tongues](Mechanics/spells/tongues.md)\n\n3/day each: [modify memory](Mechanics/spells/modify-memory.md),\
    \ [pass without trace](Mechanics/spells/pass-without-trace.md)"
  "name": "Spellcasting"
- "desc": "The blood hag can pinpoint the location of creatures that aren't Constructs\
    \ or Undead within 60 feet of her and can sense the general direction of such\
    \ creatures within 1 mile of her."
  "name": "Blood Sense"
"actions":
- "desc": "The blood hag makes three Claw or Blood Bolt attacks and can use Blood-Drinking\
    \ Hair or Face Peel. She can replace one attack with a use of Sanguine Curse."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 19\
    \ (4d6 + 5) slashing damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 17) if it is a Medium or smaller creature. The blood hag has two\
    \ claws, each of which can grapple only one target."
  "name": "Claws"
- "desc": "Ranged Spell Attack: +9 to hit, range 60 ft., one target. Hit: 18\
    \ (3d8 + 5) necrotic damage. If the target is a creature with blood, it must\
    \ succeed on a DC 17 Constitution saving throw or be [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ until the end of its next turn."
  "name": "Blood Bolt"
- "desc": "The hag drains blood from one creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by her. The target must make a DC 17 Constitution saving throw, taking 18 (4d8)\
    \ necrotic damage on a failed save, or half as much damage on a successful one.\
    \ The blood hag regains hp equal to half the necrotic damage taken."
  "name": "Blood-Drinking Hair"
- "desc": "The blood hag peels the face off one creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by her. The target must succeed on a DC 17 Dexterity saving throw or take 14\
    \ (4d6) slashing damage and be [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ until the end of its next turn. The target's hp maximum is reduced by an amount\
    \ equal to the damage taken. This reduction lasts until the target finishes a\
    \ long rest. While its hp maximum is reduced in this way, the target has disadvantage\
    \ on all Charisma checks. The target dies if this effect reduces its hp maximum\
    \ to 0."
  "name": "Face Peel"
- "desc": "The blood hag curses one creature she can see or sense within 60 feet of\
    \ her. The target must succeed on a DC 17 Wisdom saving throw or be cursed for\
    \ 1 minute. A creature automatically succeeds on this saving throw if it doesn't\
    \ have blood. While cursed, the target is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ and takes 9 (2d8) necrotic damage at the start of each of its turns as its\
    \ internal blood vessels rupture. The cursed target can repeat the saving throw\
    \ at the end of each of its turns, ending the curse on itself on a success.\n\n\
    The blood hag can have only one target cursed at a time. If it curses another,\
    \ the effect on the previous target ends."
  "name": "Sanguine Curse"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Blood%20Hag.webp"
```
^statblock

## Environment

urban