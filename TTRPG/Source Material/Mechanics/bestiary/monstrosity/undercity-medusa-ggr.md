---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/6
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Undercity Medusa"]
---
# [Undercity Medusa](Mechanics\bestiary\monstrosity/undercity-medusa-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 222*  

The medusas of Ravnica, often called gorgons, are a monstrous race of creatures that appear superficially similar to human women. In place of hair, a gorgon has a writhing mass of black, serpentine cables, and its hands are scaly claws.

The gaze of a medusa's glowing eyes causes living tissue to petrify. The transformation is rapid, leaving the victim as a stone statue, usually frozen in a position of abject fear or agony-a fine trophy for the medusa's macabre collection. The medusa must exert its will to effect this transformation, so the gaze of a surprised or friendly Ravnican medusa is harmless.

This deadly gaze attack gives medusas a degree of power among the Golgari that is out of proportion with their small numbers. Medusas command a significant share of the guild's smaller cells around Ravnica, and at least one medusa is thought to be angling for control of the entire guild at the moment.

Not all gorgons are so ambitious; some prefer to simply stalk the endless shadows of the undercity like hungry predators.

```statblock
"name": "Undercity Medusa (GGR)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"stats":
- !!int "16"
- !!int "18"
- !!int "16"
- !!int "17"
- !!int "12"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "7"
  "Insight": !!int "4"
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Elvish"
"cr": "6"
"traits":
- "desc": "The medusa's innate spellcasting ability is Intelligence (spell save DC\
    \ 14). The medusa can innately cast the following spells, requiring no material\
    \ components:\n\n1/day each: [expeditious retreat](Mechanics/spells/expeditious-retreat.md),\
    \ [fog cloud](Mechanics/spells/fog-cloud.md), [misty step](Mechanics/spells/misty-step.md)"
  "name": "Innate Spellcasting"
- "desc": "The medusa has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "During the first round of combat, the medusa has advantage on attack rolls\
    \ against any creature that is [surprised](Mechanics/Rules/conditions.md#Surprised),\
    \ and it deals an extra 10 (3d6) damage each time it hits such a creature with\
    \ an attack."
  "name": "Surprise Attack"
"actions":
- "desc": "The medusa makes two claw attacks. It can also use Petrifying Gaze before\
    \ or after making these attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) slashing damage."
  "name": "Claw"
- "desc": "The medusa fixes its gaze on one creature within 60 feet of it that it\
    \ can see and that can see its eyes. The target must make a DC 14 Constitution\
    \ saving throw. If the saving throw fails by 5 or more, the creature is instantly\
    \ [petrified](Mechanics/Rules/conditions.md#Petrified). Otherwise, a creature\
    \ that fails the save begins to turn to stone and is [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ The [restrained](Mechanics/Rules/conditions.md#Restrained) creature must repeat\
    \ the saving throw at the end of its next turn, becoming [petrified](Mechanics/Rules/conditions.md#Petrified)\
    \ on a failure or ending the effect on a success. The petrification lasts until\
    \ the creature is freed by a [greater restoration](Mechanics/spells/greater-restoration.md)\
    \ spell or similar magic."
  "name": "Petrifying Gaze"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Undercity%20Medusa.webp"
```
^statblock