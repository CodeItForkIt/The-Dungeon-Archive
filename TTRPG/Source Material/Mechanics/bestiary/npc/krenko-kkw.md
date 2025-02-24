---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/kkw
- monster/cr/1
- monster/size/small
- monster/type/humanoid/goblinoid
statblock: inline
aliases: ["Krenko"]
---
# [Krenko](Mechanics\bestiary\npc/krenko-kkw.md)
*Source: Krenko's Way p. 168*  

```statblock
"name": "Krenko (KKW)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[chain shirt](Mechanics/items/chain-shirt.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "21"
"hit_dice": "6d6"
"stats":
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "8"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "4"
  "Stealth": !!int "6"
  "Persuasion": !!int "4"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1"
"traits":
- "desc": "Krenko can take the Disengage or Hide action as a bonus action on each\
    \ of his turns."
  "name": "Nimble Escape"
"actions":
- "desc": "Krenko makes two attacks with his scimitar."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage plus 2 (1d4) poison damage.."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Light Crossbow"
"reactions":
- "desc": "When a creature Krenko can see targets him with an attack, Krenko chooses\
    \ another goblin within 5 feet of him. The two goblins swap places, and the chosen\
    \ goblin becomes the target instead."
  "name": "Redirect Attack"
"source":
- "KKW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/KKW/Krenko.webp"
```
^statblock