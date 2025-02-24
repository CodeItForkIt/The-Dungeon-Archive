---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/size/tiny
- monster/type/beast
statblock: inline
aliases: ["Frog"]
---
# [Frog](Mechanics\bestiary\beast/frog.md)
*Source: Monster Manual p. 322, Tomb of Annihilation, Curse of Strahd, The Wild Beyond the Witchlight, Plane Shift: Ixalan, Keys from the Golden Vault, Quests from the Infinite Staircase. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

A frog has no effective attacks. It feeds on small insects and typically dwells near water, in trees, or underground. The frog's statistics can also be used to represent a toad.

```statblock
"name": "Frog"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "1"
- !!int "13"
- !!int "8"
- !!int "1"
- !!int "8"
- !!int "3"
"speed": "20 ft., swim 20 ft."
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "1"
"senses": "darkvision 30 ft., passive Perception 11"
"languages": ""
"cr": "0"
"traits":
- "desc": "The frog can breathe air and water."
  "name": "Amphibious"
- "desc": "The frog's long jump is up to 10 feet and its high jump is up to 5 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"source":
- "MM"
- "ToA"
- "CoS"
- "WBtW"
- "PSX"
- "KftGV"
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Frog.webp"
```
^statblock