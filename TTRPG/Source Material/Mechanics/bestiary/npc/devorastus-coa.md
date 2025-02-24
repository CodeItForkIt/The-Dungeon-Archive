---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/20
- monster/size/huge
- monster/type/fiend/demon
statblock: inline
aliases: ["Devorastus"]
---
# [Devorastus](Mechanics\bestiary\npc/devorastus-coa.md)
*Source: Chains of Asmodeus p. 198*  

```statblock
"name": "Devorastus (CoA)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "275"
"hit_dice": "22d12 + 132"
"stats":
- !!int "24"
- !!int "14"
- !!int "22"
- !!int "8"
- !!int "6"
- !!int "10"
"speed": "30 ft."
"damage_resistances": "cold; fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "acid"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [deafened](Mechanics/Rules/conditions.md#Deafened), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [prone](Mechanics/Rules/conditions.md#Prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": "telepathy 120 ft."
"cr": "20"
"traits":
- "desc": "If Devorastus fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Devorastus takes up its entire space. Other creatures can enter the space,\
    \ but a creature that does so is subjected to Engulf and has disadvantage on the\
    \ saving throw. Creatures inside the cube can be seen but have total cover. A\
    \ creature within 5 feet of the cube can take an action to pull a creature or\
    \ object out of the cube. Doing so requires a successful DC 21 Strength check,\
    \ and the creature making the attempt takes 35 (10d6) acid damage. The cube\
    \ can hold only one Huge creature or up to six Large or smaller creatures inside\
    \ it at a time."
  "name": "Ooze Cube"
- "desc": "Devorastus can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Sticky"
- "desc": "Even when Devorastus is in plain sight, it takes a successful DC 15 Wisdom\
    \ ([Perception](Mechanics/Rules/skills.md#Perception)) check to spot Devorastus\
    \ if it has neither moved nor attacked. A creature that tries to enter Devorastus'\
    \ space while unaware of Devorastus is surprised by it."
  "name": "Transparent"
"actions":
- "desc": "Devorastus makes four attacks using its Pseudopod, Spit, or a combination\
    \ of the two."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 20 ft., one target. Hit: 42\
    \ (12d6) acid damage."
  "name": "Pseudopod"
- "desc": "Ranged Weapon Attack: +8 to hit, range 100/200 ft., one target. Hit:\
    \ 28 (8d6) acid damage. A target hit by this attack must make a DC 21 Constitution\
    \ saving throw. On a failed save, the target has the [prone](Mechanics/Rules/conditions.md#Prone)\
    \ condition."
  "name": "Spit"
- "desc": "Devorastus moves up to its speed. While doing so, it can enter Large or\
    \ smaller creatures' spaces. Whenever Devorastus enters a creature's space, the\
    \ creature must make a DC 21 Dexterity saving throw. On a successful save, the\
    \ creature can choose to be pushed 5 feet back or to the side of Devorastus. A\
    \ creature that chooses not to be pushed suffers the consequences of a failed\
    \ saving throw. On a failed save, Devorastus enters the creature's space, the\
    \ creature takes 35 (10d6) acid damage, and is engulfed. The engulfed creature\
    \ can't breathe, has the [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ condition, and takes 42 (12d6) acid damage at the start of each of Devorastus'\
    \ turns. When Devorastus moves, the engulfed creature moves with it. An engulfed\
    \ creature can try to escape by making a DC 21 Strength check as an action. On\
    \ a success, the creature escapes and enters a space of its choice within 5 feet\
    \ of Devorastus."
  "name": "Engulf"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Devorastus.webp"
```
^statblock