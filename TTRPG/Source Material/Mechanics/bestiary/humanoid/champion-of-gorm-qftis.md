---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/2
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Champion of Gorm"]
---
# [Champion of Gorm](Mechanics\bestiary\humanoid/champion-of-gorm-qftis.md)
*Source: Quests from the Infinite Staircase p. 203*  

Champions are blessed by Gorm to lead their fellow guardians. In battle, they channel auras of ghostly lightning to protect Gorm's servants.

## Guardians of Gorm

The Guardians of Gorm are stalwart Cynidiceans who worship Gorm, an ancient god of justice, storms, and war. Members of the order wear brass masks bearing the face of their god, who is depicted as a long-haired, bearded man with a stern gaze. Each fully initiated guardian has a small blue lightning bolt tattooed on their right shoulder.

Guardians follow a strict code of decorum that values bravery, honesty, and justice tempered with mercy. Still, they are quick to chastise blasphemers, criminals, and cultists who oppose their cause, buffeting these foes with their shocking implements.

```statblock
"name": "Champion of Gorm (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Lawful Good"
"ac": !!int "19"
"ac_class": "[splint armor](Mechanics/items/splint-armor.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "17"
- !!int "10"
- !!int "12"
- !!int "12"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Strength": !!int "5"
"skillsaves":
  "Athletics": !!int "5"
  "Religion": !!int "3"
  "Insight": !!int "4"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "The champion has advantage on saving throws against the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition."
  "name": "Brave"
"actions":
- "desc": "The champion makes two Lightning Mace attacks or three Handaxe attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 5 (2d4) lightning damage."
  "name": "Lightning Mace"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 6 (1d6 + 3) slashing damage."
  "name": "Handaxe"
"bonus_actions":
- "desc": "The champion exudes an aura of ghostly lightning that fills a 10-foot-radius\
    \ sphere centered on itself. While this aura is active, the champion and each\
    \ creature of its choice within the aura have advantage on saving throws. The\
    \ aura moves with the champion and lasts for 1 minute, until the champion has\
    \ the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated) condition,\
    \ or until the champion uses another bonus action to end the aura."
  "name": "Aura of Resilience (1/Day)"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Champion%20of%20Gorm.webp"
```
^statblock