---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/rot
- monster/cr/11
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Naergoth Bladelord"]
---
# [Naergoth Bladelord](Mechanics\bestiary\npc/naergoth-bladelord-rot.md)
*Source: The Rise of Tiamat p. 90, Tyranny of Dragons p. 186*  

```statblock
"name": "Naergoth Bladelord (RoT)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md)"
"hp": !!int "135"
"hit_dice": "18d8 + 54"
"stats":
- !!int "20"
- !!int "12"
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "6"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "6"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Draconic"
"cr": "11"
"traits":
- "desc": "While in sunlight, Naergoth has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely\
    \ on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Naergoth makes three attacks, either with his longsword or longbow. He\
    \ can use Life Drain in place of one longsword attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 20\
    \ (5d6 + 3) necrotic damage. The target must succeed on a DC 15 Constitution\
    \ saving throw or its hit point maximum is reduced by an amount equal to the damage\
    \ taken. This reduction lasts until the target finishes a long rest. The target\
    \ dies if this effect reduces its hit point maximum to 0."
  "name": "Life Drain"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) slashing damage, or 10 (1d10 + 5) if used with two hands, plus 10 (3d6)\
    \ necrotic damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. Hit:\
    \ 5 (1d8 + 1) piercing damage plus 10 (3d6) necrotic damage."
  "name": "Longbow"
"source":
- "RoT"
- "ToD"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/RoT/Naergoth%20Bladelord.webp"
```
^statblock