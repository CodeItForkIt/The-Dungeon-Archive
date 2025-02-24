---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Sage"]
---
# [Sage](Mechanics\bestiary\humanoid/sage-cm.md)
*Source: Candlekeep Mysteries p. 9*  

Candlekeep's resident lore experts are master sages and sages who dedicate themselves to scholarship above all.

```statblock
"name": "Sage (CM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "8"
- !!int "10"
- !!int "10"
- !!int "18"
- !!int "15"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "6"
  "Nature": !!int "8"
  "Investigation": !!int "8"
  "Religion": !!int "8"
  "Insight": !!int "4"
  "History": !!int "8"
  "Arcana": !!int "8"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "1/2"
"traits":
- "desc": "The sage casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (save DC 14, +6 to hit with spell attacks):\n\nAt will: [light](Mechanics/spells/light.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [mending](Mechanics/spells/mending.md),\
    \ \n\n1/day each: [dispel magic](Mechanics/spells/dispel-magic.md), [levitate](Mechanics/spells/levitate.md),\
    \ [locate object](Mechanics/spells/locate-object.md), [see invisibility](Mechanics/spells/see-invisibility.md),\
    \ [sending](Mechanics/spells/sending.md), [tongues](Mechanics/spells/tongues.md),\
    \ [unseen servant](Mechanics/spells/unseen-servant.md)\n\n3/day each: [comprehend\
    \ languages](Mechanics/spells/comprehend-languages.md), [detect magic](Mechanics/spells/detect-magic.md),\
    \ [identify](Mechanics/spells/identify.md), "
  "name": "Spellcasting"
"actions":
- "desc": "Melee Spell Attack: +6 to hit (with advantage if the target is wearing\
    \ armor made of metal), reach 5 ft., one creature. Hit: 9 (2d8) lightning\
    \ damage, and the target can't take reactions until the start of its next turn."
  "name": "Shocking Grasp (Cantrip)"
"reactions":
- "desc": "When the sage is hit by an attack or targeted by a [magic missile](Mechanics/spells/magic-missile.md)\
    \ spell, it calls forth an [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ barrier of magical force that protects it. Until the start of its next turn,\
    \ the sage has a +5 bonus to AC, including against the triggering attack, and\
    \ it takes no damage from magic missile."
  "name": "Shield (1st-Level Spell; 3/Day)"
"source":
- "CM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Sage.webp"
```
^statblock