---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/7
- monster/size/small-or-medium
- monster/type/humanoid/bard
statblock: inline
aliases: ["Silverquill Professor of Radiance"]
---
# [Silverquill Professor of Radiance](Mechanics\bestiary\humanoid/silverquill-professor-of-radiance-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 215*  

Professors of radiance call up magic through spoken words and glyphs formed of magically shaped ink and light. The professors channel radiance to illuminate their allies, bolstering them with encouragement and inspiring any who witness their orations. Professors of radiance can turn their words into potent assets in battle or strike at their foes with searing radiance.

These Silverquill teachers seek to inspire greatness in all that they do, pushing their students to look for the good in all things and bring that into the light.

## Silverquill Scholars

The scholars of Silverquill College study the power of magic shaped through spoken and written words. They use that power either to illuminate and guide or to obscure and demoralize.

```statblock
"name": "Silverquill Professor of Radiance (SCC)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "bard"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "97"
"hit_dice": "15d8 + 30"
"stats":
- !!int "11"
- !!int "14"
- !!int "14"
- !!int "16"
- !!int "13"
- !!int "19"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "5"
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "Deception": !!int "7"
  "Performance": !!int "10"
  "Arcana": !!int "6"
  "Persuasion": !!int "10"
"damage_resistances": "radiant"
"senses": "passive Perception 11"
"languages": "Common plus any four languages"
"cr": "7"
"traits":
- "desc": "The professor casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 15):\n\
    \nAt will: [dancing lights](Mechanics/spells/dancing-lights.md), [friends](Mechanics/spells/friends.md)\n\
    \n1/day each: [hypnotic pattern](Mechanics/spells/hypnotic-pattern.md), [tongues](Mechanics/spells/tongues.md)\n\
    \n2/day each: [bless](Mechanics/spells/bless.md), [command](Mechanics/spells/command.md),\
    \ [cure wounds](Mechanics/spells/cure-wounds.md), [daylight](Mechanics/spells/daylight.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The professor makes two Radiant Strike attacks. The professor can replace\
    \ one of the attacks with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 17 (3d8 + 4) radiant damage. If the target is a creature,\
    \ it must succeed on a DC 15 Constitution saving throw be [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ until the end of its next turn."
  "name": "Radiant Strike"
"source":
- "SCC"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Silverquill%20Professor%20of%20Radiance.webp"
```
^statblock