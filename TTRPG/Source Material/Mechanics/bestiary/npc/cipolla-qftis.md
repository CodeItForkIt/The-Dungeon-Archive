---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/1
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Cipolla"]
---
# [Cipolla](Mechanics\bestiary\npc/cipolla-qftis.md)
*Source: Quests from the Infinite Staircase*  

```statblock
"name": "Cipolla (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "10"
"ac_class": "13 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "22"
"hit_dice": "5d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Insight": !!int "4"
  "History": !!int "5"
  "Arcana": !!int "5"
"damage_resistances": "cold"
"senses": "passive Perception 12"
"languages": "Common plus any three languages, Draconic"
"cr": "1"
"traits":
- "desc": "Cipolla casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (spell save DC 13):\n\nAt will: [Dancing Lights](Mechanics/spells/dancing-lights.md),\
    \ [Mage Hand](Mechanics/spells/mage-hand.md), [Prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n1/day each: [Arcane Lock](Mechanics/spells/arcane-lock.md), [Burning Hands](Mechanics/spells/burning-hands.md),\
    \ [Comprehend Languages](Mechanics/spells/comprehend-languages.md), [Detect Magic](Mechanics/spells/detect-magic.md),\
    \ [Levitate](Mechanics/spells/levitate.md), [Mage Armor](Mechanics/spells/mage-armor.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Cipolla makes two Arcane Burst attacks and can use Starry Radiance if available."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 8 (1d10 + 3) radiant damage."
  "name": "Arcane Burst"
- "desc": "Dazzling light bursts from Cipolla's fingertips in a 15-foot cone. Each\
    \ creature in that area must succeed on a DC 13 Constitution saving throw or have\
    \ the [blinded](Mechanics/Rules/conditions.md#Blinded) condition until the end\
    \ of Cipolla's next turn."
  "name": "Starry Radiance (Recharge 5-6)"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Cipolla.webp"
```
^statblock