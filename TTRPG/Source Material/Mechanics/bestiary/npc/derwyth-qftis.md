---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/elf
statblock: inline
aliases: ["Derwyth"]
---
# [Derwyth](Mechanics\bestiary\npc/derwyth-qftis.md)
*Source: Quests from the Infinite Staircase p. 52*  

Derwyth lives in Cernant Valley—a forested basin at the foot of the Tegefed Mountains—along with many animals, most of which are small woodland creatures. These animals act as Derwyth's eyes and ears, quickly bringing her news of events in the wood, particularly the arrival and actions of strangers. The creatures also carry messages to more powerful Beasts in the valley that sometimes come to Derwyth's aid.

```statblock
"name": "Derwyth (QftIS)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Neutral Good"
"ac": !!int "11"
"ac_class": "16 with [barkskin](Mechanics/spells/barkskin.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "12"
- !!int "15"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Medicine": !!int "4"
  "Nature": !!int "3"
  "Perception": !!int "4"
"senses": "darkvision 60, passive Perception 14"
"languages": "Common, Elvish"
"cr": "2"
"traits":
- "desc": "Derwyth is a 4th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (spell save DC 12, +4 to hit with spell attacks). She has the following druid\
    \ spells prepared:\n\nCantrips (at will): [druidcraft](Mechanics/spells/druidcraft.md),\
    \ [produce flame](Mechanics/spells/produce-flame.md), [shillelagh](Mechanics/spells/shillelagh.md)\n\
    \n1st level (4 slots): [entangle](Mechanics/spells/entangle.md), [longstrider](Mechanics/spells/longstrider.md),\
    \ [speak with animals](Mechanics/spells/speak-with-animals.md), [thunderwave](Mechanics/spells/thunderwave.md)\n\
    \n2nd level (3 slots): [animal messenger](Mechanics/spells/animal-messenger.md),\
    \ [barkskin](Mechanics/spells/barkskin.md)"
  "name": "Spellcasting"
- "desc": "Over the course of 1 minute, Derwyth can magically transform into a Huge\
    \ or smaller tree and remain in that form for 24 hours or until she ends this\
    \ transformation early (no action required). Her equipment melds into her new\
    \ form. While in this form, her Armor Class is 16, she has the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition, and she can't move or speak."
  "name": "Tree Shape (2/Day)"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit (+4 to hit with shillelagh), reach\
    \ 5 ft., one target. Hit: 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning\
    \ damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with shillelagh."
  "name": "Quarterstaff"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Derwyth.webp"
```
^statblock