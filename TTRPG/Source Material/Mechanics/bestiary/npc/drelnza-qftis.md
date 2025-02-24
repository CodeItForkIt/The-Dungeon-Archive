---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/15
- monster/size/medium
- monster/type/undead/vampire
statblock: inline
aliases: ["Drelnza"]
---
# [Drelnza](Mechanics\bestiary\npc/drelnza-qftis.md)
*Source: Quests from the Infinite Staircase p. 197*  

Drelnza is the vampire daughter of Iggwilv. She is the Witch Queen's greatest treasure, an immortal warrior who guards some of her mother's most precious belongings decades after the archmage's mysterious departure. The identity of Drelnza's father is unknown even to her.

Drelnza slumbers deep in the Lost Caverns of Tsojcanth, rising to dispatch those few who make it to Iggwilv's hoard. As a consequence of Drelnza's prolonged rest, she has yet to regain some of her vampiric powers.

In the years before Iggwilv's disappearance, Drelnza acted as general to a battalion of demons bound to serve the Witch Queen. Armed with her sentient longsword, Heretic, Drelnza terrorized the people of Perrenland.

```statblock
"name": "Drelnza (QftIS)"
"size": "Medium"
"type": "undead"
"subtype": "vampire"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md)"
"hp": !!int "187"
"hit_dice": "22d8 + 88"
"stats":
- !!int "18"
- !!int "18"
- !!int "18"
- !!int "17"
- !!int "15"
- !!int "18"
"speed": "30 ft., climb 30 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "9"
  "Wisdom": !!int "7"
  "Intelligence": !!int "8"
"skillsaves":
  "Deception": !!int "9"
  "Perception": !!int "7"
  "Arcana": !!int "8"
"damage_resistances": "necrotic"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Abyssal, Common, Giant"
"cr": "15"
"traits":
- "desc": "If Drelnza fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Drelnza wields Heretic."
  "name": "Special Equipment"
- "desc": "Drelnza can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "Drelnza takes 20 radiant damage when she starts her turn in sunlight. While\
    \ in sunlight, she has disadvantage on attack rolls and ability checks."
  "name": "Sunlight Hypersensitivity"
"actions":
- "desc": "Drelnza makes one Bite attack and one Heretic attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. Hit: 7\
    \ (1d6 + 4) piercing damage plus 10 (3d6) necrotic damage. The target's hit\
    \ point maximum is reduced by an amount equal to the necrotic damage taken, and\
    \ Drelnza regains hit points equal to that amount. The reduction lasts until the\
    \ target finishes a long rest. The target dies if this effect reduces its hit\
    \ point maximum to 0. A Humanoid slain in this way and then buried rises the following\
    \ night as a vampire spawn under Drelnza's control."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft. one target. Hit: 40\
    \ (6d10 + 7) slashing damage, and the target must succeed on a DC 17 Constitution\
    \ saving throw or have the [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ condition until the start of Drelnza's next turn. Celestials have disadvantage\
    \ on the saving throw."
  "name": "Heretic"
- "desc": "Drelnza targets one Humanoid she can see within 30 feet of herself. The\
    \ target must succeed on a DC 17 Wisdom saving throw or have the [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ condition. While [charmed](Mechanics/Rules/conditions.md#Charmed) in this way,\
    \ the target regards Drelnza as a trusted friend to be heeded and protected. The\
    \ target isn't under Drelnza's control, but it takes her requests and actions\
    \ in the most favorable way.\n\nEach time Drelnza or her allies do anything harmful\
    \ to the target, it can repeat the saving throw, ending the effect on itself on\
    \ a success. Otherwise, the effect lasts 24 hours or until Drelnza is destroyed,\
    \ is on a different plane of existence than the target, or takes a bonus action\
    \ to end the effect."
  "name": "Charm"
"reactions":
- "desc": "Drelnza can take up to three reactions per round but only one per turn."
  "name": ""
- "desc": "Immediately after a creature Drelnza can see ends its turn, Drelnza moves\
    \ up to her speed without provoking opportunity attacks."
  "name": "Move"
- "desc": "Drelnza adds 5 to her AC against one melee attack that would hit her. To\
    \ do so, she must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Drelnza.webp"
```
^statblock