---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/3
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
aliases: ["Society of Sensation Muse"]
---
# [Society of Sensation Muse](Mechanics\bestiary\humanoid/society-of-sensation-muse-mpp.md)
*Source: Morte's Planar Parade p. 61, Sigil and the Outlands, Turn of Fortune's Wheel*  

The muses of the Society of Sensation are performers who enthrall crowds with spectacle and minor sensory experiences. When threatened, they beguile their foes, placating their enemies with magical displays.

```statblock
"name": "Society of Sensation Muse (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](Mechanics/items/leather-armor.md)"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "8"
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "14"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Dexterity": !!int "5"
"skillsaves":
  "Stealth": !!int "5"
  "Insight": !!int "4"
  "Perception": !!int "4"
  "Performance": !!int "7"
"senses": "passive Perception 14"
"languages": "Common plus two more languages"
"cr": "3"
"traits":
- "desc": "The muse casts one of the following spells, using Charisma as the spellcasting\
    \ ability (spell save DC 13):\n\nAt will: [dancing lights](Mechanics/spells/dancing-lights.md)\n\
    \n1/day each: [comprehend languages](Mechanics/spells/comprehend-languages.md),\
    \ [hypnotic pattern](Mechanics/spells/hypnotic-pattern.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The muse makes two Beguiling Resonance attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 90 ft.,\
    \ one target. Hit: 9 (2d8) psychic damage. If the target is a creature, it\
    \ must succeed on a DC 13 Charisma saving throw or have disadvantage on the next\
    \ attack roll it makes until the end of its next turn."
  "name": "Beguiling Resonance"
"bonus_actions":
- "desc": "Each creature within 30 feet of the muse must make a DC 13 Wisdom saving\
    \ throw. On a failed save, the creature has the [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ condition for 1 minute. On a successful save, the creature becomes immune to\
    \ any muse's Enchanting Presence for 24 hours.\n\nWhenever the muse deals damage\
    \ to the [charmed](Mechanics/Rules/conditions.md#Charmed) creature, the [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ creature can repeat the saving throw, ending the effect on itself on a success."
  "name": "Enchanting Presence"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Society%20of%20Sensation%20Muse.webp"
```
^statblock