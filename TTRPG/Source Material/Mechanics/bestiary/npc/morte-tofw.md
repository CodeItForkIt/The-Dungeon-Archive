---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/1-4
- monster/size/tiny
- monster/type/undead
statblock: inline
aliases: ["Morte"]
---
# [Morte](Mechanics\bestiary\npc/morte-tofw.md)
*Source: Turn of Fortune's Wheel p. 10, Morte's Planar Parade*  

The talking skull Morte is a curmudgeonly interplanar traveler plucked from his eternal punishment in the Nine Hells. Tormented by the lies he told in life, Morte masks his pain with a morbid sense of humor and an insufferable dose of sarcasm.

```statblock
"name": "Morte (ToFW)"
"size": "Tiny"
"type": "undead"
"alignment": "Chaotic Good"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "4d4 + 12"
"stats":
- !!int "10"
- !!int "16"
- !!int "16"
- !!int "13"
- !!int "10"
- !!int "12"
"speed": "0 ft., fly 30 ft. (hover)"
"skillsaves":
  "Stealth": !!int "5"
  "Arcana": !!int "3"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"cr": "1/4"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) piercing damage."
  "name": "Bite"
"source":
- "ToFW"
- "MPP"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/Morte.webp"
```
^statblock