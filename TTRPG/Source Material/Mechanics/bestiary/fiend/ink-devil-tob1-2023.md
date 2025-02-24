---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/planar
- monster/size/small
- monster/type/fiend/devil
statblock: inline
aliases: ["Ink Devil"]
---
# [Ink Devil](Mechanics\bestiary\fiend/ink-devil-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 96*  

*This small devil wears a small red hat. A wicked grin flashes black teeth, and the creature nervously wrings its hands, baring long, needle-like claws.*

Ink devils have small, pursed mouths and long, thin, bony fingers with nails that resemble quills. Their heads are often bald or shaved in a monastic tonsure, and they have two small horns, no larger than an acorn. Their skin tends toward walnut, indigo, and black tones, though the eldest are as pale as parchment. They often wear robes and carry scroll cases.

## Cowards at Heart

Ink devils are talkers and cowards. They prefer chatting, whining, and pleading to any form of combat. When they are forced to fight, they prefer to hide behind other devils. They force lesser devils, like lemures, to fight for them, resorting to their sharp claws only as a last resort.

## False Gifts

They often give strangers false gifts, like letters of credit, charters, or scholarly papers inscribed with a dangerous glyph.

## Bibliophiles and Bookworms

Ink devils live in libraries and scriptoria in Hell and related planes. Their speed and keen vision make them excellent accountants, record keepers, translators, and note takers. They cannot be trusted, and they delight in altering documents for their own amusement or in their master's service.

```statblock
"name": "Ink Devil (ToB1-2023)"
"size": "Small"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "54"
"hit_dice": "12d6 + 12"
"stats":
- !!int "12"
- !!int "18"
- !!int "12"
- !!int "20"
- !!int "8"
- !!int "18"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "6"
"skillsaves":
  "Deception": !!int "6"
  "Stealth": !!int "6"
  "History": !!int "9"
  "Arcana": !!int "9"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 9"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "2"
"traits":
- "desc": "The ink devil casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 14):\n\
    \nAt will: [detect magic](Mechanics/spells/detect-magic.md), [illusory script](Mechanics/spells/illusory-script.md)\
    \ (as an action)\n\n1/day: [glyph of warding](Mechanics/spells/glyph-of-warding.md)"
  "name": "Spellcasting"
- "desc": "Magical darkness doesn't impede the ink devil's darkvision."
  "name": "Devil's Sight"
- "desc": "The ink devil has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 14\
    \ (3d6 + 4) slashing damage."
  "name": "Claw"
- "desc": "Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 13 (2d8 + 4) poison damage, and the target must succeed\
    \ on a DC 13 Dexterity saving throw or be marked with a small, fiendish tattoo\
    \ for 24 hours. Devils have advantage on attack rolls against the marked target,\
    \ and the target has disadvantage on saving throws against the spells and abilities\
    \ of devils."
  "name": "Devil's Ink"
- "desc": "The ink devil touches a scroll, corrupting it. A creature using the scroll\
    \ must succeed a DC 13 Intelligence saving throw or the spell harms the caster\
    \ (if an offensive spell), helps the nearest devil (if beneficial), or fails,\
    \ consuming the scroll (if not offensive or if no devils are in range to benefit\
    \ from the magic)."
  "name": "Corrupt Scroll"
- "desc": "The ink devil magically turns [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ until it attacks or uses Disrupt Concentration, or until its [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ ends (as if concentrating on a spell). Any equipment the ink devil wears or\
    \ carries is [invisible](Mechanics/Rules/conditions.md#Invisible) with it."
  "name": "Invisibility"
"bonus_actions":
- "desc": "One spellcaster concentrating on a spell within 30 feet of the ink devil\
    \ that the devil can see must succeed on a DC 13 Wisdom saving throw or lose [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ on the spell."
  "name": "Disrupt Concentration"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ink%20Devil.webp"
```
^statblock

## Environment

planar