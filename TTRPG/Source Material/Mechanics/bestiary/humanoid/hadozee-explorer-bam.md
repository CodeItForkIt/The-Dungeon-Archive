---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/2
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Hadozee Explorer"]
---
# [Hadozee Explorer](Mechanics\bestiary\humanoid/hadozee-explorer-bam.md)
*Source: Boo's Astral Menagerie p. 28, Light of Xaryxis*  

Hadozee explorers scour Wildspace systems for riches and adventure. They often serve as navigators aboard spelljamming ships. To them, the Astral Plane is a mostly uncharted expanse worthy of further exploration.

```statblock
"name": "Hadozee Explorer (BAM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[studded leather](Mechanics/items/studded-leather-armor.md)"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"stats":
- !!int "11"
- !!int "17"
- !!int "13"
- !!int "13"
- !!int "17"
- !!int "14"
"speed": "30 ft., climb 30 ft."
"saves":
  "Wisdom": !!int "5"
  "Constitution": !!int "3"
"skillsaves":
  "Athletics": !!int "2"
  "Stealth": !!int "5"
  "Perception": !!int "5"
  "Survival": !!int "5"
"senses": "passive Perception 15"
"languages": "Common, Hadozee"
"cr": "2"
"traits":
- "desc": "If it isn't [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ or wearing heavy armor, the hadozee can extend its skin membranes to move up\
    \ to 5 feet horizontally for every 1 foot it descends in the air."
  "name": "Glide"
"actions":
- "desc": "The hadozee makes two Shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 40/120 ft., one target. Hit:\
    \ 16 (2d12 + 3) piercing damage."
  "name": "Musket"
"bonus_actions":
- "desc": "The hadozee takes the Disengage or Hide action."
  "name": "Nimble Escape"
"reactions":
- "desc": "When it would take damage from a fall, the hadozee extends its skin membranes\
    \ to reduce the fall's damage to 0, provided it isn't wearing heavy armor."
  "name": "Safe Descent"
"source":
- "BAM"
- "LoX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Hadozee%20Explorer.webp"
```
^statblock