---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/7
- monster/size/medium
- monster/type/construct/warforged
statblock: inline
aliases: ["Crunch"]
---
# [Crunch](Mechanics\bestiary\npc/crunch-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Crunch (VEoR)"
"size": "Medium"
"type": "construct"
"subtype": "warforged"
"alignment": "typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"stats":
- !!int "14"
- !!int "20"
- !!int "16"
- !!int "10"
- !!int "19"
- !!int "10"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "7"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "7"
  "Acrobatics": !!int "8"
"damage_resistances": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "passive Perception 17"
"languages": "Common"
"cr": "7"
"traits":
- "desc": "Crunch has advantage on an attack roll against a creature if at least one\
    \ of Crunch's allies is within 5 feet of the creature and the ally doesn't have\
    \ the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated) condition."
  "name": "Pack Tactics"
"actions":
- "desc": "Crunch makes three Armblade or Bolt Launcher attacks. It can replace one\
    \ of the attacks with a use of Snare Trap."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage."
  "name": "Armblade"
- "desc": "Ranged Weapon Attack: +8 to hit, range 80/320 ft., one target. Hit:\
    \ 9 (1d8 + 5) piercing damage."
  "name": "Bolt Launcher"
- "desc": "Crunch deploys a Tiny mechanical trap on a solid surface within 5 feet\
    \ of itself. The trap is hidden, requiring a successful DC 17 Intelligence ([Investigation](Mechanics/Rules/skills.md#Investigation))\
    \ check to find. The trap lasts for 1 minute. Whenever an enemy enters a space\
    \ within 10 feet of the trap or starts its turn there, it must succeed on a DC\
    \ 16 Dexterity saving throw or take 21 (6d6) piercing damage and have the [prone](Mechanics/Rules/conditions.md#Prone)\
    \ condition. A creature makes this saving throw only once per turn."
  "name": "Snare Trap (1/Day)"
"bonus_actions":
- "desc": "Crunch moves up to its speed without provoking opportunity attacks."
  "name": "Dash"
"source":
- "VEoR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Crunch.webp"
```
^statblock