---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/imr
- monster/cr/8
- monster/size/large
- monster/type/giant
statblock: inline
aliases: [""The Demogorgon""]
---
# ["The Demogorgon"](Mechanics\bestiary\npc/the-demogorgon-imr.md)
*Source: Infernal Machine Rebuild p. 53*  

```statblock
"name": "\"The Demogorgon\" (IMR)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "123"
"hit_dice": "13d12 + 39"
"stats":
- !!int "21"
- !!int "8"
- !!int "17"
- !!int "6"
- !!int "10"
- !!int "8"
"speed": "40 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Giant, Orc"
"cr": "8"
"traits":
- "desc": "The ettin has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks and on saving throws against being [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [charmed](Mechanics/Rules/conditions.md#Charmed), [deafened](Mechanics/Rules/conditions.md#Deafened),\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [stunned](Mechanics/Rules/conditions.md#Stunned),\
    \ and knocked [unconscious](Mechanics/Rules/conditions.md#Unconscious)."
  "name": "Two Heads"
- "desc": "When one of the ettin's heads is asleep, its other head is awake."
  "name": "Wakeful"
"actions":
- "desc": "The ettin makes two attacks: one with its battleaxe and one with its morningstar."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) slashing damage."
  "name": "Battleaxe"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) piercing damage."
  "name": "Morningstar"
- "desc": "The ettin's right head exhales fire in a 30-foot cone. Each creature in\
    \ that area must make a DC 14 Dexterity saving throw, taking 45 (10d8) fire\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
- "desc": "The ettin's left head exhales an icy blast in a 30-foot cone. Each creature\
    \ in that area must make a DC 14 Constitution saving throw, taking 45 (10d8)\
    \ cold damage on a failed save, or half as much damage on a successful one."
  "name": "Cold Breath (Recharge 5-6)"
- "desc": "The ettin turns its magical gaze toward one creature that it can see within\
    \ 120 feet of it. That target must make a DC 14 Wisdom saving throw. Unless the\
    \ target is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated), it can\
    \ avert its eyes to avoid the gaze and to automatically succeed on the save. If\
    \ the target does so, it can't see the ettin until the start of the ettin's next\
    \ turn. If the target looks at the ettin in the meantime, it must immediately\
    \ make the save.\n\nIf the target fails the save, it suffers one of the following\
    \ effects of the ettin's choice or at random:"
  "name": "Gaze"
- "desc": "The target is [stunned](Mechanics/Rules/conditions.md#Stunned) until the\
    \ start of the ettin's next turn or until the ettin is no longer within line of\
    \ sight."
  "name": "Beguiling Gaze"
- "desc": "The target is [charmed](Mechanics/Rules/conditions.md#Charmed) by the ettin\
    \ until the start of the ettin's next turn. The ettin chooses how the [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ target uses its actions, reactions, and movement."
  "name": "Hypnotic Gaze"
- "desc": "The target suffers the effect of the [confusion](Mechanics/spells/confusion.md)\
    \ spell without making a saving throw. The effect lasts until the start of the\
    \ ettin's next turn. The ettin doesn't need to concentrate on the spell."
  "name": "Insanity Gaze"
"source":
- "IMR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IMR/The%20Demogorgon.webp"
```
^statblock