---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/1
- monster/size/small-or-medium
- monster/type/humanoid/wizard
statblock: inline
aliases: ["Scholarly Agent"]
---
# [Scholarly Agent](Mechanics\bestiary\humanoid/scholarly-agent-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 206*  

Scholarly agents are low-ranking members of an academic organization. They know a few tricks to help them avoid danger, and they study magic that enables them to decipher secrets of the past and identify magical relics.

## Scholars of Allsight

The Allegiance of Allsight is a scholarly faction that operates primarily within the Marquesian metropolis of Ank'Harel. Though most members of the allegiance are academics unfamiliar with combat, the faction's field agents are skilled archaeologists who are also trained to contend with and overcome the threats that lurk in the depths of Exandria.

```statblock
"name": "Scholarly Agent (CRCotN)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "wizard"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "10"
- !!int "12"
- !!int "12"
- !!int "16"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"saves":
  "Intelligence": !!int "5"
"skillsaves":
  "Investigation": !!int "5"
  "History": !!int "5"
  "Arcana": !!int "5"
"senses": "passive Perception 11"
"languages": "Common plus one other language"
"cr": "1"
"traits":
- "desc": "The agent casts one of the following spells, using Intelligence as the\
    \ spellcasting ability:\n\nAt will: [dancing lights](Mechanics/spells/dancing-lights.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md)\n\n1/day each: [comprehend languages](Mechanics/spells/comprehend-languages.md),\
    \ [identify](Mechanics/spells/identify.md) (as an action), [mage armor](Mechanics/spells/mage-armor.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 30 ft.,\
    \ one target. Hit: 14 (2d10 + 3) lightning damage. If the target is a creature,\
    \ it can't take reactions until the start of its next turn."
  "name": "Arcane Shock"
"reactions":
- "desc": "The agent adds 2 to its AC against one attack that would hit it. To do\
    \ so, the agent must be able to see the attacker and have a free hand."
  "name": "Glyph of Shielding"
"source":
- "CRCotN"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Scholarly%20Agent.webp"
```
^statblock