---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/2
- monster/size/small
- monster/type/celestial
statblock: inline
aliases: ["Lantern Archon"]
---
# [Lantern Archon](Mechanics\bestiary\celestial/lantern-archon-mpp.md)
*Source: Morte's Planar Parade p. 17, Sigil and the Outlands, Turn of Fortune's Wheel*  

The lowest-ranked archons, lantern archons greet newly arrived souls to Mount Celestia and light the path for those who traverse the plane with reverence and respect. They appear as glowing, winged balls of vaporous light wrapped in a gleaming metal lattice, although they have no more physical substance than smoke.

When confronting those who approach with ill intentions, lantern archons strike with searing bolts of focused light, flitting from place to place between blasts to confound their foes.

## Archons

Archons are denizens of the Seven Heavens of Mount Celestia. Created by the powers of order and benevolence, archons defend their home from fiendish incursions and safeguard those threatened by wicked forces. Archons are skilled communicators, able to speak all the languages of the multiverse. When pushed into combat, they prefer to subdue foes. However, against Fiends, archons are wrathful combatants, manifesting the righteous vengeance of Mount Celestia to strike down the wicked.

Each archon's form corresponds to its place within the Celestial hierarchy. When faced in battle, archons radiate the full fury of the Upper Planes, bolstering their allies and cowing their foes.

```statblock
"name": "Lantern Archon (MPP)"
"size": "Small"
"type": "celestial"
"alignment": "typically  Lawful Good"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "5d6 + 5"
"stats":
- !!int "1"
- !!int "16"
- !!int "12"
- !!int "6"
- !!int "12"
- !!int "13"
"speed": "0 ft., fly 60 ft. (hover)"
"skillsaves":
  "Perception": !!int "3"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning, radiant"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "all"
"cr": "2"
"traits":
- "desc": "The archon casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability:\n\nAt will: [detect evil\
    \ and good](Mechanics/spells/detect-evil-and-good.md)\n\n1/day: [aid](Mechanics/spells/aid.md)"
  "name": "Spellcasting"
- "desc": "As long as the archon doesn't have the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition, each creature of the archon's choice that starts its turn within\
    \ 20 feet of the archon must make a DC 11 Wisdom saving throw. On a failed save,\
    \ the creature has the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition until the start of its next turn. On a successful save, the creature\
    \ is immune to all archons' Aura of Menace for 24 hours."
  "name": "Aura of Menace"
- "desc": "The archon sheds bright light in a 30-foot radius and dim light for an\
    \ additional 30 feet."
  "name": "Illumination"
- "desc": "The archon can move through creatures and objects as if they were difficult\
    \ terrain. If it ends its turn inside an object, it takes 5 (1d10) force damage."
  "name": "Incorporeal Movement"
"actions":
- "desc": "The archon makes two Radiant Strike attacks. It can replace one attack\
    \ with a use of Teleport."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 6 (1d6 + 3) radiant damage."
  "name": "Radiant Strike"
- "desc": "The archon teleports, along with any equipment it is wearing or carrying,\
    \ to an unoccupied space it can see within 120 feet of itself."
  "name": "Teleport"
"bonus_actions":
- "desc": "The archon reduces its Illumination to shed only dim light in a 5-foot\
    \ radius, or it returns the light to full intensity."
  "name": "Shift Radiance"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Lantern%20Archon.webp"
```
^statblock