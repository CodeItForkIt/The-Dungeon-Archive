---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/5
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Android"]
---
# [Android](Mechanics\bestiary\construct/android-qftis.md)
*Source: Quests from the Infinite Staircase p. 194*  

Androids are synthetic humanoids built to assist their creators with highly specialized tasks. They are designed to be compliant and typically have friendly demeanors.

Every android has one or more upgrades to help it excel at its intended functions, but all androids are capable of defending themselves with concentrated bolts of force up close or from a distance.

Despite an android's sophisticated construction, electrical surges can temporarily disrupt its finely tuned components. Similarly, damage to its core processing functions or long stretches of isolation can wear down an android's critical faculties, causing it to behave erratically.

```statblock
"name": "Android (QftIS)"
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
"speed": "30 ft., fly 30 ft. (hover; aerialist only), swim 30 ft. (diver only)"
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Perception": !!int "7"
  "History": !!int "4"
"damage_resistances": "acid, fire"
"damage_immunities": "cold, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (sentry only), darkvision 60 ft., passive Perception\
  \ 17"
"languages": "Common plus the languages spoken by its creator"
"cr": "5"
"traits":
- "desc": "The android casts one of the following spells, requiring no material components\
    \ and using Intelligence as the spellcasting ability:\n\n2/day each: [Cure\
    \ Wounds](Mechanics/spells/cure-wounds.md) (as a 3rd-level spell; medic only),\
    \ [Identify](Mechanics/spells/identify.md), [Tongues](Mechanics/spells/tongues.md)\
    \ (diplomat only)"
  "name": "Spellcasting (Diplomat and Medic Only)"
- "desc": "When the android is created, it gains one of six possible designs suited\
    \ for its role (choose or roll a d6): 1, aerialist; 2, diplomat; 3, diver; 4,\
    \ duelist; 5, medic; 6, sentry. This design determines certain traits in this\
    \ stat block."
  "name": "Design Specialization"
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
  "name": "Parry (Duelist Only)"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Android.webp"
```
^statblock