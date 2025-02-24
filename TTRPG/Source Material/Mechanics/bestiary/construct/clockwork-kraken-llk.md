---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/llk
- monster/cr/10
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Clockwork Kraken"]
---
# [Clockwork Kraken](Mechanics\bestiary\construct/clockwork-kraken-llk.md)
*Source: Lost Laboratory of Kwalish p. 38*  

```statblock
"name": "Clockwork Kraken (LLK)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "142"
"hit_dice": "15d10 + 60"
"stats":
- !!int "20"
- !!int "12"
- !!int "18"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_resistances": "fire; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "10"
"traits":
- "desc": "The clockwork kraken has advantage on saving throws against spells and\
    \ other magical effects."
  "name": "Magic Resistance"
- "desc": "The clockwork kraken has eight tentacles, each of which is treated as a\
    \ Medium creature, moves independently on the construct's turn, and has a flying\
    \ speed of 40 feet. The clockwork kraken's senses operate through its tentacles\
    \ as well as its main body. Each tentacle can be attacked independently, with\
    \ damage dealt to tentacles applied to the clockwork kraken's hit point total.\
    \ A tentacle is destroyed if it takes more than 20 damage.\n\nReducing the construct\
    \ to three or fewer tentacles reduces its attacks accordingly. A clockwork kraken\
    \ can regrow any destroyed tentacles at the end of a long rest."
  "name": "Independent Tentacles"
"actions":
- "desc": "The clockwork kraken makes four tentacle slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) bludgeoning damage."
  "name": "Tentacle Slam"
"source":
- "LLK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LLK/Clockwork%20Kraken.webp"
```
^statblock