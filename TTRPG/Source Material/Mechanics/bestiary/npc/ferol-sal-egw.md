---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/egw
- monster/cr/3
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Ferol Sal"]
---
# [Ferol Sal](Mechanics\bestiary\npc/ferol-sal-egw.md)
*Source: Explorer's Guide to Wildemount p. 249*  

```statblock
"name": "Ferol Sal (EGW)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[studded leather](Mechanics/items/studded-leather-armor.md)"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"stats":
- !!int "15"
- !!int "14"
- !!int "16"
- !!int "16"
- !!int "13"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
- "desc": "While in sunlight, Ferol has disadvantage on attack rolls, as well as on\
    \ Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Ferol makes two longsword attacks or two longbow attacks. It can use its\
    \ Life Drain in place of one longsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 5\
    \ (1d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution\
    \ saving throw or its hit point maximum is reduced by an amount equal to the damage\
    \ taken. This reduction lasts until the target finishes a long rest. The target\
    \ dies if this effect reduces its hit point maximum to 0.\n\nA humanoid slain\
    \ by this attack rises 24 hours later as a [zombie](Mechanics/bestiary/undead/zombie.md)\
    \ under Ferol's control, unless the humanoid is restored to life or its body is\
    \ destroyed. Ferol can have no more than twelve zombies under its control at one\
    \ time."
  "name": "Life Drain"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow"
"source":
- "EGW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/EGW/Ferol%20Sal.webp"
```
^statblock