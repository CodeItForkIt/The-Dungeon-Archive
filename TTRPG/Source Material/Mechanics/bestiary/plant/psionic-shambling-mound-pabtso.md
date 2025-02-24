---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/5
- monster/size/large
- monster/type/plant
statblock: inline
aliases: ["Psionic Shambling Mound"]
---
# [Psionic Shambling Mound](Mechanics\bestiary\plant/psionic-shambling-mound-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 108*  

```statblock
"name": "Psionic Shambling Mound (PaBTSO)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "18"
- !!int "8"
- !!int "16"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "20 ft., swim 20 ft."
"skillsaves":
  "Stealth": !!int "2"
"damage_resistances": "cold, fire"
"damage_immunities": "lightning"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened),\
  \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "5"
"traits":
- "desc": "The shambling mound casts one of the following spells, requiring no spell\
    \ components and using Intelligence as the spellcasting ability (spell save DC\
    \ 8):\n\nAt will: [minor illusion](Mechanics/spells/minor-illusion.md)\n\n\
    1/day: [charm person](Mechanics/spells/charm-person.md) (already cast)"
  "name": "Spellcasting (Psionics)"
- "desc": "Whenever the shambling mound is subjected to lightning damage, it takes\
    \ no damage and regains a number of hit points equal to the lightning damage dealt."
  "name": "Lightning Absorption"
"actions":
- "desc": "The shambling mound makes two slam attacks. If both attacks hit a Medium\
    \ or smaller target, the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 14), and the shambling mound uses its Engulf on it."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage."
  "name": "Slam"
- "desc": "The shambling mound engulfs a Medium or smaller creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by it. The engulfed target is [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained), and unable to breathe,\
    \ and it must succeed on a DC 14 Constitution saving throw at the start of each\
    \ of the mound's turns or take 13 (2d8 + 4) bludgeoning damage. If the mound\
    \ moves, the engulfed target moves with it. The mound can have only one creature\
    \ engulfed at a time."
  "name": "Engulf"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Psionic%20Shambling%20Mound.webp"
```
^statblock