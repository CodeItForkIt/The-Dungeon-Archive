---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1-4
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Corpsejaw"]
---
# [Corpsejaw](Mechanics\bestiary\monstrosity/corpsejaw-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 92*  

Cousins to mountain lions, corpsejaws are battlefield scavengers. Their powerful jaws allow them to tear through most armor, so they can eat carrion other scavengers leave behind. Military organizations such as the Free Swords issue bounties on corpsejaws to prevent damage to valuable salvage.

```statblock
"name": "Corpsejaw (GHLoE)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "18"
"hit_dice": "4d8"
"stats":
- !!int "15"
- !!int "14"
- !!int "10"
- !!int "3"
- !!int "13"
- !!int "7"
"speed": "40 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The corpsejaw's bite works as if made of adamantine. The bite scores a\
    \ critical hit on a roll of 19 or 20."
  "name": "Adamantine Jaws"
- "desc": "The corpsejaw has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "If the corpsejaw moves at least 20 feet straight toward a creature and\
    \ then hits it with a claw attack on the same turn, that target must succeed on\
    \ a DC 12 Strength saving throw or fall [prone](Mechanics/Rules/conditions.md#Prone).\
    \ If the target is [prone](Mechanics/Rules/conditions.md#Prone), the corpsejaw\
    \ can make one bite attack against it as a bonus action."
  "name": "Pounce"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage. If the corpsejaw scores a critical hit and the target\
    \ wears nonmagical armor, the armor takes a permanent and cumulative -1 penalty\
    \ to the AC it offers. Armor reduced to an AC of 10 is destroyed."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage."
  "name": "Claw"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Corpsejaw.webp"
```
^statblock