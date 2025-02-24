---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/1-8
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Guardian of Gorm"]
---
# [Guardian of Gorm](Mechanics\bestiary\humanoid/guardian-of-gorm-qftis.md)
*Source: Quests from the Infinite Staircase p. 203*  

Guardians are the fearless rank and file of their faction.

## Guardians of Gorm

The Guardians of Gorm are stalwart Cynidiceans who worship Gorm, an ancient god of justice, storms, and war. Members of the order wear brass masks bearing the face of their god, who is depicted as a long-haired, bearded man with a stern gaze. Each fully initiated guardian has a small blue lightning bolt tattooed on their right shoulder. Guardians follow a strict code of decorum that values bravery, honesty, and justice tempered with mercy. Still, they are quick to chastise blasphemers, criminals, and cultists who oppose their cause, buffeting these foes with their shocking implements.

```statblock
"name": "Guardian of Gorm (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Lawful Good"
"ac": !!int "16"
"ac_class": "[chain mail](Mechanics/items/chain-mail.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "15"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "13"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Religion": !!int "2"
  "Insight": !!int "3"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "1/8"
"traits":
- "desc": "The guardian has advantage on saving throws against the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition."
  "name": "Brave"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 2 (1d4) lightning damage."
  "name": "Lightning Mace"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) slashing damage."
  "name": "Handaxe"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Guardian%20of%20Gorm.webp"
```
^statblock