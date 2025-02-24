---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/4
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
aliases: ["Mind's Eye Matter Smith"]
---
# [Mind's Eye Matter Smith](Mechanics\bestiary\humanoid/minds-eye-matter-smith-mpp.md)
*Source: Morte's Planar Parade p. 60, Sigil and the Outlands, Turn of Fortune's Wheel*  

Members of the Mind's Eye believe the power to transcend the multiverse lies in every individual. Matter smiths harness this innate power to reshape reality in Sigil's Great Foundry, manifesting useful tools from nothing.

```statblock
"name": "Mind's Eye Matter Smith (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "14"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Intelligence": !!int "4"
"skillsaves":
  "Investigation": !!int "4"
  "Perception": !!int "6"
"senses": "passive Perception 16"
"languages": "Common plus two more languages"
"cr": "4"
"traits":
- "desc": "The matter smith casts one of the following spells, using Charisma as the\
    \ spellcasting ability:\n\nAt will: [mage armor](Mechanics/spells/mage-armor.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n1/day each: [create food and water](Mechanics/spells/create-food-and-water.md),\
    \ [fabricate](Mechanics/spells/fabricate.md) (as an action)"
  "name": "Spellcasting"
"actions":
- "desc": "The matter smith makes two Manifested Force attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 10 (2d6 + 3) force damage."
  "name": "Manifested Force"
"bonus_actions":
- "desc": "The matter smith magically manipulates the energy of the plane of existence\
    \ it's on to produce one of the following effects (choose one or roll a d4):\n\
    \n- 1-2 Chains. The matter smith creates spectral bindings around a creature\
    \ it can see within 30 feet of itself. The target must succeed on a DC 13 Dexterity\
    \ saving throw or have the [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ condition until the end of its next turn.  \n- 3-4 Magic Shield. The matter\
    \ smith conjures a floating, spectral shield that grants the matter smith a +5\
    \ bonus to its AC until the shield disappears at the start of the matter smith's\
    \ next turn. The first time a creature misses a melee attack roll against the\
    \ matter smith while the shield is conjured, that creature takes 7 (2d6) force\
    \ damage.  "
  "name": "Planar Smithing"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Mind%27s%20Eye%20Matter%20Smith.webp"
```
^statblock