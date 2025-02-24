---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/5
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Android Duelist"]
---
# [Android Duelist](Mechanics\bestiary\construct/android-duelist-qftis.md)
*Source: Quests from the Infinite Staircase p. 194*  

```statblock
"name": "Android Duelist (QftIS)"
"size": "Medium"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "18"
- !!int "18"
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "10"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Perception": !!int "7"
  "History": !!int "4"
"damage_resistances": "acid, fire"
"damage_immunities": "cold, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Common plus the languages spoken by its creator"
"cr": "5"
"traits":
- "desc": "When the android takes lightning damage, it must succeed on a DC 10 Constitution\
    \ saving throw or have the [stunned](Mechanics/Rules/conditions.md#Stunned) condition\
    \ until the start of its next turn."
  "name": "Lightning Overload"
"actions":
- "desc": "The android makes two Force Strike attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 40/120\
    \ ft., one target. Hit: 15 (2d10 + 4) force damage. If the target is a Medium\
    \ or smaller creature, it must succeed on a DC 15 Strength saving throw or have\
    \ the [prone](Mechanics/Rules/conditions.md#Prone) condition."
  "name": "Force Strike"
"reactions":
- "desc": "The android adds 3 to its AC against one melee attack roll that would hit\
    \ it. To do so, the android must see the attacker."
  "name": "Parry"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Android%20Duelist.webp"
```
^statblock