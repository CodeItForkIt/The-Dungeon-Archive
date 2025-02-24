---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/dwarf
statblock: inline
aliases: ["Albino Dwarf Spirit Warrior"]
---
# [Albino Dwarf Spirit Warrior](Mechanics\bestiary\humanoid/albino-dwarf-spirit-warrior-toa.md)
*Source: Tomb of Annihilation p. 210*  

The albino dwarves of Chult were driven from their subterranean homes by volcanic activity, and those who didn't seek refuge in Port Nyanzaru adapted to living in the jungle. They make armor out of dinosaur hide; shape weapons out of dinosaur bones, flint, and wood; and craft ornate jewelry out of bones, feathers, tusks, and stone beads. Albino dwarves haven't forgotten how to forge metal, but they seldom have the means to do so.

## Albino Dwarf Spirit Warriors

An albino dwarf can become so attuned to the land of Chult that a benevolent nature spirit takes notice and bestows a powerful charm on the dwarf, granting it innate spellcasting abilities. These dwarf spirit warriors dedicate themselves to preserving the natural beauty of Chult and battling unnatural threats. An albino dwarf spirit warrior has the statistics of an albino dwarf warrior, except it has a challenge rating of 1 (200 XP) and gains an Innate Spellcasting feature.

```statblock
"name": "Albino Dwarf Spirit Warrior (ToA)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[hide armor](Mechanics/items/hide-armor.md)"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"stats":
- !!int "13"
- !!int "13"
- !!int "17"
- !!int "12"
- !!int "14"
- !!int "11"
"speed": "25 ft."
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "4"
  "Survival": !!int "4"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Dwarvish"
"cr": "1"
"traits":
- "desc": "The dwarf's innate spellcasting ability is Wisdom. It can innately cast\
    \ the following spells, requiring no material components:\n\n1/day each: [hunter's\
    \ mark](Mechanics/spells/hunters-mark.md), [jump](Mechanics/spells/jump.md), [pass\
    \ without trace](Mechanics/spells/pass-without-trace.md), [speak with animals](Mechanics/spells/speak-with-animals.md),\
    \ [speak with plants](Mechanics/spells/speak-with-plants.md)"
  "name": "Innate Spellcasting"
- "desc": "The dwarf has advantage on saving throws against poison."
  "name": "Dwarven Resilience"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) slashing damage."
  "name": "Handaxe"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Albino%20Dwarf%20Spirit%20Warrior.webp"
```
^statblock