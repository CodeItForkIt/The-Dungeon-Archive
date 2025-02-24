---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/10
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Archon of Redemption"]
---
# [Archon of Redemption](Mechanics\bestiary\celestial/archon-of-redemption-psz.md)
*Source: Plane Shift: Zendikar p. 22*  

Like angels, archons are incarnations of white mana. They serve the archangels as embodiments of white mana's harsher aspects: a rigid sense of justice and a ruthless execution of punishment for those who defy the law. The appearance of the archons is deceptive: they look like hooded humans riding winged lions, but they are single creatures with just one mind and will.

An archon's game statistics are nearly identical to those of a [deva](Mechanics/bestiary/celestial/deva.md).

```statblock
"name": "Archon of Redemption (PSZ)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"stats":
- !!int "18"
- !!int "18"
- !!int "18"
- !!int "17"
- !!int "20"
- !!int "20"
"speed": "30 ft., fly 90 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "9"
"skillsaves":
  "Insight": !!int "9"
  "Perception": !!int "9"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "10"
"traits":
- "desc": "The archon's innate spellcasting ability is Charisma (spell save DC 17).\
    \ The archon can innately cast the following spells, requiring only verbal components:\n\
    \nAt will: [detect evil and good](Mechanics/spells/detect-evil-and-good.md)\n\
    \n1/day each: [destructive wave](Mechanics/spells/destructive-wave.md), [geas](Mechanics/spells/geas.md)"
  "name": "Innate Spellcasting"
- "desc": "The archon's weapon attacks are magical. When the archon hits with any\
    \ weapon, the weapon deals an extra 3d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "The archon can't be compelled to act in a manner contrary to its nature\
    \ or its understanding of justice."
  "name": "Axiomatic Mind"
- "desc": "The archon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Though it appears as a humanoid creature riding a mount, an archon is a\
    \ single being. The \"rider\" can't be dismounted, and no other means can separate\
    \ the two portions of the archon's being short of its death."
  "name": "One Being"
"actions":
- "desc": "The archon makes two attacks: one with its sword and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage plus 13 (3d8) radiant damage."
  "name": "Sword"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage plus 13 (3d8) radiant damage."
  "name": "Claws"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Archon%20of%20Redemption.webp"
```
^statblock