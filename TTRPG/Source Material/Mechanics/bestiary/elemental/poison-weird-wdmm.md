---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/4
- monster/size/large
- monster/type/elemental
statblock: inline
aliases: ["Poison Weird"]
---
# [Poison Weird](Mechanics\bestiary\elemental/poison-weird-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 127*  

```statblock
"name": "Poison Weird (WDMM)"
"size": "Large"
"type": "elemental"
"alignment": "Neutral"
"ac": !!int "13"
"hp": !!int "58"
"hit_dice": "9d10 + 9"
"stats":
- !!int "17"
- !!int "16"
- !!int "13"
- !!int "11"
- !!int "10"
- !!int "10"
"speed": "0 ft., swim 60 ft."
"damage_resistances": "fire; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "blindsight 30 ft., passive Perception 10"
"languages": "understands Aquan but doesn't speak"
"cr": "4"
"traits":
- "desc": "The weird is [invisible](Mechanics/Rules/conditions.md#Invisible) while\
    \ fully immersed in toxic brew."
  "name": "Invisible in Water"
- "desc": "The weird dies if forced to leave the basin of toxic brew it inhabits,\
    \ or if a [purify food and drink](Mechanics/spells/purify-food-and-drink.md) spell\
    \ is cast on the brew."
  "name": "Brew Bound"
- "desc": "A creature takes 10 (3d6) poison damage at the start of each of its turns\
    \ while [grappled](Mechanics/Rules/conditions.md#Grappled) by a poison weird."
  "name": "Poisonous Body"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one creature. Hit:\
    \ 13 (3d6 + 3) bludgeoning damage. If the target is Medium or smaller, it is\
    \ [grappled](Mechanics/Rules/conditions.md#Grappled) (escape DC 13) and pulled\
    \ 5 feet toward the poison weird. Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ the poison weird tries to drown it, and the poison weird can't constrict another\
    \ target."
  "name": "Constrict"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Poison%20Weird.webp"
```
^statblock