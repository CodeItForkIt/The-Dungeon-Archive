---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/0
- monster/size/small
- monster/type/beast
statblock: inline
aliases: ["Flying Monkey"]
---
# [Flying Monkey](Mechanics\bestiary\beast/flying-monkey-toa.md)
*Source: Tomb of Annihilation p. 220*  

Flying monkeys are slightly more clever and curious than common monkeys, and they can be domesticated and taught to obey simple commands. They come in many colors and varieties, with feathered wings that have a span of about 5 feet. With the DM's permission, the [find familiar](Mechanics/spells/find-familiar.md) spell can summon a flying monkey.

```statblock
"name": "Flying Monkey (ToA)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"stats":
- !!int "8"
- !!int "14"
- !!int "11"
- !!int "5"
- !!int "12"
- !!int "6"
"speed": "30 ft., climb 20 ft., fly 30 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "0"
"traits":
- "desc": "The flying monkey has advantage on an attack roll against a creature if\
    \ at least one of the monkey's allies is within 5 feet of the creature and the\
    \ ally isn't [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Pack Tactics"
- "desc": "With the DM's permission, the [find familiar](Mechanics/spells/find-familiar.md)\
    \ spell can summon a flying monkey."
  "name": "Familiar"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target Hit: 1 (1d4\
    \ - 1) piercing damage."
  "name": "Bite"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Flying%20Monkey.webp"
```
^statblock