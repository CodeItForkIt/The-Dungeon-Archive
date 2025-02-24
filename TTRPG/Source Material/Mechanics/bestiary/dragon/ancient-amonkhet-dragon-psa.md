---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/24
- monster/size/gargantuan
- monster/type/dragon
statblock: inline
aliases: ["Ancient Amonkhet Dragon"]
---
# [Ancient Amonkhet Dragon](Mechanics\bestiary\dragon/ancient-amonkhet-dragon-psa.md)
*Source: Plane Shift: Amonkhet p. 33*  

Dragons are fierce monsters with heavy reptilian bodies, crocodilian heads, and leathery wings, and are dis-tinguished by their ability to breathe fire. Though Nicol Bolas is also a dragon, he feels no kinship for these savage, dim-witted beasts. They live mostly in the remote reaches of the desert, soaring in lazy circles through the sky as they search for prey. Sometimes they are captured and brought inside the Hekma, where they are put to use within the trials of the five gods—especially in the climactic battles of the final Trial of Zeal.

The dragons of Amonkhet are **red dragons**, though they lack the high Intelligence of the red dragons in the "Monster Manual".

```statblock
"name": "Ancient Amonkhet Dragon (PSA)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "546"
"hit_dice": "28d20 + 252"
"stats":
- !!int "30"
- !!int "10"
- !!int "29"
- !!int "10"
- !!int "15"
- !!int "23"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  "Charisma": !!int "13"
  "Dexterity": !!int "7"
  "Wisdom": !!int "9"
  "Constitution": !!int "16"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "16"
"damage_immunities": "fire"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 26"
"languages": "Common, Draconic"
"cr": "24"
"traits":
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
"actions":
- "desc": "The dragon can use its Frightful Presence. It then makes three attacks:\
    \ one with its bite and two with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 15 ft., one target. Hit: 21\
    \ (2d10 + 10) piercing damage plus 14 (4d6) fire damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 17\
    \ (2d6 + 10) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +17 to hit, reach 20 ft., one target. Hit: 19\
    \ (2d8 + 10) bludgeoning damage."
  "name": "Tail"
- "desc": "Each creature of the dragon's choice that is within 120 feet of the dragon\
    \ and aware of it must succeed on a DC 21 Wisdom saving throw or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success. If a creature's saving throw\
    \ is successful or the effect ends for it, the creature is immune to the dragon's\
    \ Frightful Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "The dragon exhales fire in a 90-foot cone. Each creature in that area must\
    \ make a DC 24 Dexterity saving throw, taking 91 (26d6) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon makes a Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The dragon makes a tail attack."
  "name": "Tail Attack"
- "desc": "The dragon beats its wings. Each creature within 15 feet of the dragon\
    \ must succeed on a DC 25 Dexterity saving throw or take 17 (2d6 + 10) bludgeoning\
    \ damage and be knocked [prone](Mechanics/Rules/conditions.md#Prone). The dragon\
    \ can then fly up to half its flying speed."
  "name": "Wing Attack (Costs 2 Actions)"
"source":
- "PSA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Ancient%20Amonkhet%20Dragon.webp"
```
^statblock