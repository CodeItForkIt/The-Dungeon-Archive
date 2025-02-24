---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/half-elf
statblock: inline
aliases: ["Xandala"]
---
# [Xandala](Mechanics\bestiary\npc/xandala-toa.md)
*Source: Tomb of Annihilation p. 236*  

The half-elf sorcerer Xandala has come to Chult in search of the Ring of Winter, an artifact in Artus Cimber's possession. Xandala knows that the ring has kept Artus alive for over a century, and she craves its power. If she meets the characters, Xandala pretends to be Artus's daughter and tries to convince them to help her find him. Her plan is to cast [dominate person](Mechanics/spells/dominate-person.md) on Artus and force him to give her the ring, then escape using her [fly](Mechanics/spells/fly.md) spell.

Xandala's magic traces back to a draconic bloodline, and parts of her skin are covered by a thin sheen of protective scales. She has befriended a pseudodragon named Summerwise, who thinks that Xandala's quest for the ring is dangerous but has given up trying to talk the sorcerer out of it. Summerwise can be turned against Xandala by good-aligned characters.

## Xandala's Traits

### Ideal

"I have the blood of dragons flowing through my veins. I am destined for greatness."

### Bond

"The Ring of Winter will bring me power and immortality."

### Flaw

"I'm surrounded by fools."

```statblock
"name": "Xandala (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-elf"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"stats":
- !!int "10"
- !!int "11"
- !!int "14"
- !!int "18"
- !!int "16"
- !!int "18"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
"skillsaves":
  "Deception": !!int "10"
  "Insight": !!int "6"
  "History": !!int "7"
  "Arcana": !!int "7"
  "Survival": !!int "6"
"senses": "passive Perception 13"
"languages": "Common, Draconic, Dwarvish, Elvish, Halfling"
"cr": "7"
"traits":
- "desc": "Xandala is a 9th-level spellcaster. Her spellcasting ability is Charisma\
    \ (spell save DC 15, +7 to hit with spell attacks). Xandala has the following\
    \ sorcerer spells prepared:\n\nCantrips (at will): [acid splash](Mechanics/spells/acid-splash.md),\
    \ [fire bolt](Mechanics/spells/fire-bolt.md), [light](Mechanics/spells/light.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [ray of frost](Mechanics/spells/ray-of-frost.md)\n\
    \n1st level (4 slots): [chromatic orb](Mechanics/spells/chromatic-orb.md),\
    \ [feather fall](Mechanics/spells/feather-fall.md), [shield](Mechanics/spells/shield.md)\n\
    \n2nd level (4 slots): [invisibility](Mechanics/spells/invisibility.md), [misty\
    \ step](Mechanics/spells/misty-step.md)\n\n3rd level (3 slots): [fireball](Mechanics/spells/fireball.md),\
    \ [fly](Mechanics/spells/fly.md)\n\n4th level (3 slots): [ice storm](Mechanics/spells/ice-storm.md),\
    \ [polymorph](Mechanics/spells/polymorph.md)\n\n5th level (1 slots): [dominate\
    \ person](Mechanics/spells/dominate-person.md)"
  "name": "Spellcasting"
- "desc": "When she casts a spell that has a casting time of 1 action, Xandala changes\
    \ the casting time to 1 bonus action for that casting."
  "name": "Quickened Spell (3/Day)"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage, or 4 (1d8) bludgeoning damage when used with two hands."
  "name": "Quarterstaff"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Xandala.webp"
```
^statblock