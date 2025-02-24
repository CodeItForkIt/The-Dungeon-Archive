---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/0
- monster/size/small
- monster/type/fiend/demon
statblock: inline
aliases: ["Gibberling"]
---
# [Gibberling](Mechanics\bestiary\fiend/gibberling-qftis.md)
*Source: Quests from the Infinite Staircase p. 202*  

A single gibberling is little more than a nuisance—a babbling, hairy creature that darts about, attacking whatever it can find. Unfortunately, gibberlings are rarely encountered alone. They rampage in dense swarms, crawling and leaping over each other to rip, shred, and devour everything in their path.

Gibberlings are named for their incoherent chattering. Loud and shrill, their exasperating nonsense distracts even the most focused creatures. Gibberling swarms are heard long before they are seen.

The first gibberlings were spawned in the jungles of the Gaping Maw, a layer of the Abyss ruled by the demon lord Demogorgon. The Prince of Demons' influence instilled in gibberlings a hive-mind-like nature, protecting them from magical compulsions. However, unlike most demons, gibberlings share a strong aversion to fire.

On the Material Plane, gibberlings tend to dwell in dense forests or the Underdark.

```statblock
"name": "Gibberling (QftIS)"
"size": "Small"
"type": "fiend"
"subtype": "demon"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "13"
- !!int "14"
- !!int "11"
- !!int "5"
- !!int "7"
- !!int "5"
"speed": "30 ft."
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 8"
"languages": "Gibberling"
"cr": "0"
"traits":
- "desc": "If the gibberling takes fire damage, it has disadvantage on attack rolls\
    \ and ability checks until the end of its next turn."
  "name": "Aversion to Fire"
- "desc": "Any non-gibberling that is within 30 feet of the gibberling and doesn't\
    \ have the [deafened](Mechanics/Rules/conditions.md#Deafened) condition has disadvantage\
    \ on Constitution saving throws to maintain [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ on spells and similar effects."
  "name": "Incessant Gibberish"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d4\
    \ + 1) piercing damage."
  "name": "Bite"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Gibberling.webp"
```
^statblock