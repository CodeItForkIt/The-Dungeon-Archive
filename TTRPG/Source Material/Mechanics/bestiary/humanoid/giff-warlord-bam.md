---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/10
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Giff Warlord"]
---
# [Giff Warlord](Mechanics\bestiary\humanoid/giff-warlord-bam.md)
*Source: Boo's Astral Menagerie p. 25*  

A high-ranking giff who takes up the life of an independent mercenary might amass enough power and influence to become a warlord.

A giff warlord usually commands a small fleet of spelljamming ships and operates out of a heavily defended stronghold. Anyone who shares the warlord's ideology—whatever it might be—is eligible to join the ranks of the warlord's army, which is mainly made up of mages who helm the ships of the fleet and provide magical firepower, sellswords of various species, and guns for hire in the form of giff shock troopers.

```statblock
"name": "Giff Warlord (BAM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[half plate](Mechanics/items/half-plate-armor.md)"
"hp": !!int "178"
"hit_dice": "21d8 + 84"
"stats":
- !!int "22"
- !!int "15"
- !!int "18"
- !!int "14"
- !!int "14"
- !!int "18"
"speed": "30 ft., swim 30 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "6"
  "Strength": !!int "10"
  "Constitution": !!int "8"
"skillsaves":
  "Intimidation": !!int "12"
  "Athletics": !!int "10"
  "Insight": !!int "6"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "10"
"traits":
- "desc": "The giff's mastery of its weapons enables it to ignore the loading property\
    \ of any firearm."
  "name": "Firearms Knowledge"
- "desc": "If the giff fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (2/Day)"
"actions":
- "desc": "The giff makes two Morningstar attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) piercing damage."
  "name": "Morningstar"
- "desc": "Ranged Weapon Attack: +6 to hit, range 40/120 ft., one target. Hit:\
    \ 28 (4d12 + 2) piercing damage."
  "name": "Double-Barreled Musket"
"legendary_actions":
- "desc": "The giff moves up to its speed without provoking opportunity attacks."
  "name": "Move"
- "desc": "The giff ends the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition on itself and each creature of its choice that it can see within 30\
    \ feet of it."
  "name": "Rallying Cry"
- "desc": "The giff makes two Morningstar attacks or one Double-Barreled Musket attack."
  "name": "Weapon of Choice (2 Actions)"
"source":
- "BAM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Giff%20Warlord.webp"
```
^statblock