---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/17
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/environment/mountain
- monster/size/gargantuan
- monster/type/elemental
statblock: inline
aliases: ["Elemental Locus"]
---
# [Elemental Locus](Mechanics\bestiary\elemental/elemental-locus-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 157*  

*The ground ripples and tears as rocks fall, jets of flame erupt, and howling winds rage around a rocky creature.*

## Spirit of the Land

Elemental loci are living spirits inhabiting or embodying tracts of land and geographical features. They are the ultimate personification of nature—the land itself come to life. They vary in size from small hills to entire ridge lines, with no discernible pattern to where they take root.

## Stubborn Nature

Elemental loci are fiercely protective of their chosen location. They tolerate no interference in the natural order and challenge all who despoil the land, be they mortal, monster, or god.

> [!note] Elemental Loci in Midgard
> 
> Among the Tamasheq, the elemental loci are cherished as minor deities, nearly as powerful as the Wind Lords themselves. The sorcerers of Kush have tried to capture and enslave loci for decades; thus far without success, but they grow bolder (and closer to their goal) with each attempt.
^elemental-loci-in-midgard

```statblock
"name": "Elemental Locus (ToB1-2023)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "290"
"hit_dice": "20d20 + 80"
"stats":
- !!int "28"
- !!int "1"
- !!int "18"
- !!int "10"
- !!int "11"
- !!int "11"
"speed": "25 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "6"
  "Intelligence": !!int "6"
"skillsaves":
  "Nature": !!int "6"
  "Perception": !!int "6"
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "acid; cold; fire; lightning; poison; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 120 ft., tremorsense 120 ft., passive Perception 16"
"languages": "Primordial"
"cr": "17"
"traits":
- "desc": "The elemental locus doesn't require air, food, drink, or sleep."
  "name": "Elemental Nature"
- "desc": "If the elemental locus dies, it returns to life in 1d12 months, regaining\
    \ all its hp and becoming active again. The new body appears in a space of the\
    \ locus's choice within its bound land. Only a [wish](Mechanics/spells/wish.md)\
    \ spell can prevent this trait from functioning."
  "name": "Immortal"
- "desc": "The elemental locus is bound to an area of land or ocean no larger than\
    \ 100 square miles. If it leaves this region, it loses its Spawn Elemental action.\
    \ If it remains outside the region, it automatically teleports back to the center\
    \ of this area after 24 hours, regardless of distance."
  "name": "Land Bound"
- "desc": "The elemental locus has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "The elemental locus deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "Moving through difficult terrain doesn't cost the elemental locus extra\
    \ movement, and its speed can't be reduced."
  "name": "Unstoppable"
"actions":
- "desc": "The elemental locus makes three Slam attacks. It can replace one attack\
    \ with a use of Spawn Elemental."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 15 ft., one target. Hit: 31\
    \ (5d8 + 9) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 18 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Slam"
- "desc": "The elemental locus magically creates up to 2d6 mephits or 1 Elemental\
    \ with a challenge rating of 5 or lower. The Elementals arrive at the start of\
    \ the locus's next turn, acting as allies of the locus and obeying its spoken\
    \ commands. The locus can create only Elementals that share an element with a\
    \ terrain feature comprising at least 100,000 square feet of the locus's bound\
    \ land. For example, a desert-bound locus can't create a water-based Elemental,\
    \ unless its bound desert contains an oasis or other source of water around the\
    \ size of a small pond. The Elementals remain for 1 hour, until the locus dies,\
    \ or until the locus dismisses them as a bonus action. The locus can have any\
    \ number of Elementals under its control at one time, provided the combined total\
    \ CR of the Elementals is no higher than 8."
  "name": "Spawn Elemental"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Elemental%20Locus.webp"
```
^statblock

## Environment

forest, grassland, hill, mountain