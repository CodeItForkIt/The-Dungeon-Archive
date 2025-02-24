---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/4
- monster/size/medium
- monster/type/celestial
statblock: inline
aliases: ["Hound Archon"]
---
# [Hound Archon](Mechanics\bestiary\celestial/hound-archon-mpp.md)
*Source: Morte's Planar Parade p. 16, Turn of Fortune's Wheel*  

Hound archons are the foot soldiers of Mount Celestia, tasked with protecting the innocent and helpless. Loyal defenders, these bipedal warriors wield blades of shining radiance and can assume canine forms, allowing them to inconspicuously guard peaceable communities as dogs and wolves.

## Archons

Archons are denizens of the Seven Heavens of Mount Celestia. Created by the powers of order and benevolence, archons defend their home from fiendish incursions and safeguard those threatened by wicked forces. Archons are skilled communicators, able to speak all the languages of the multiverse. When pushed into combat, they prefer to subdue foes. However, against Fiends, archons are wrathful combatants, manifesting the righteous vengeance of Mount Celestia to strike down the wicked.

Each archon's form corresponds to its place within the Celestial hierarchy. When faced in battle, archons radiate the full fury of the Upper Planes, bolstering their allies and cowing their foes.

```statblock
"name": "Hound Archon (MPP)"
"size": "Medium"
"type": "celestial"
"alignment": "typically  Lawful Good"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "18"
- !!int "12"
- !!int "15"
- !!int "11"
- !!int "14"
- !!int "15"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "2"
"skillsaves":
  "Stealth": !!int "3"
  "Insight": !!int "4"
  "Perception": !!int "6"
"damage_immunities": "lightning"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "all"
"cr": "4"
"traits":
- "desc": "The archon casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability:\n\nAt will: [detect evil\
    \ and good](Mechanics/spells/detect-evil-and-good.md)\n\n1/day each: [aid](Mechanics/spells/aid.md),\
    \ [continual flame](Mechanics/spells/continual-flame.md)"
  "name": "Spellcasting"
- "desc": "As long as the archon doesn't have the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition, each creature of the archon's choice that starts its turn within\
    \ 20 feet of the archon must make a DC 12 Wisdom saving throw. On a failed save,\
    \ the creature has the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition until the start of its next turn. On a successful save, the creature\
    \ is immune to all archons' Aura of Menace for 24 hours."
  "name": "Aura of Menace"
"actions":
- "desc": "The archon makes two Bite attacks. It can replace one of the attacks with\
    \ a Shining Blade attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) piercing damage. If the target is a Large or smaller creature, it must\
    \ succeed on a DC 14 Strength saving throw or have the [prone](Mechanics/Rules/conditions.md#Prone)\
    \ condition."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) radiant damage."
  "name": "Shining Blade (True Form Only)"
- "desc": "The archon teleports, along with any equipment it is wearing or carrying,\
    \ to an unoccupied space it can see within 120 feet of itself."
  "name": "Teleport"
"bonus_actions":
- "desc": "The archon magically transforms into any Medium or Large dog or wolf while\
    \ retaining its game statistics (other than its size and losing its Shining Blade\
    \ attack). The archon reverts to its true form if reduced to 0 hit points or if\
    \ it uses a bonus action to do so."
  "name": "Change Shape"
"source":
- "MPP"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Hound%20Archon.webp"
```
^statblock