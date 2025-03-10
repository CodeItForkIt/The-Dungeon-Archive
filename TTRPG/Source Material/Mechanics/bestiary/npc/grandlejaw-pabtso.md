---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
statblock: inline
aliases: ["Grandlejaw"]
---
# [Grandlejaw](Mechanics\bestiary\npc/grandlejaw-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 121*  

```statblock
"name": "Grandlejaw (PaBTSO)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"stats":
- !!int "20"
- !!int "12"
- !!int "20"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "8"
"traits":
- "desc": "Grandlejaw can hold its breath for 1 hour."
  "name": "Hold Breath"
- "desc": "Grandlejaw has five heads. While it has more than one head, Grandlejaw\
    \ has advantage on saving throws against being [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [charmed](Mechanics/Rules/conditions.md#Charmed), [deafened](Mechanics/Rules/conditions.md#Deafened),\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [stunned](Mechanics/Rules/conditions.md#Stunned),\
    \ and knocked [unconscious](Mechanics/Rules/conditions.md#Unconscious).\n\nWhenever\
    \ Grandlejaw takes 25 or more damage in a single turn, one of its heads dies.\
    \ If all its heads die, Grandlejaw dies.\n\nAt the end of its turn, it grows two\
    \ heads for each of its heads that died since its last turn, unless it has taken\
    \ fire damage since its last turn. Grandlejaw regains 10 hit points for each head\
    \ regrown in this way."
  "name": "Multiple Heads"
- "desc": "For each head Grandlejaw has beyond one, it gets an extra reaction that\
    \ can be used only for opportunity attacks."
  "name": "Reactive Heads"
- "desc": "While Grandlejaw sleeps, at least one of its heads is awake."
  "name": "Wakeful"
"actions":
- "desc": "Grandlejaw makes as many bite attacks as it has heads."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 10\
    \ (1d10 + 5) piercing damage."
  "name": "Bite"
"source":
- "PaBTSO"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Grandlejaw.webp"
```
^statblock