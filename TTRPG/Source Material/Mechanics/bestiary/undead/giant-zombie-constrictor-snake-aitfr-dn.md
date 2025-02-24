---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aitfr-dn
- monster/cr/8
- monster/size/huge
- monster/type/undead
statblock: inline
aliases: ["Giant Zombie Constrictor Snake"]
---
# [Giant Zombie Constrictor Snake](Mechanics\bestiary\undead/giant-zombie-constrictor-snake-aitfr-dn.md)
*Source: Adventures in the Forgotten Realms: Deepest Night p. 11*  

These enormous, rotten husks were living, Medium-sized constrictors when the yuan-ti brought them to honor and entice Kyrilla to share her knowledge and powers. They grew to their full, Huge size on a diet of supplicants and prisoners, many of whose bones can be found elsewhere in the lair. When the yuan-ti turned against Kyrilla, they fought and slew these snakes—only to find them slithering again through cursed, ambient magic in Kyrilla's lair.

The constrictors die if they leave the lair.

```statblock
"name": "Giant Zombie Constrictor Snake (AitFR-DN)"
"size": "Huge"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "187"
"hit_dice": "22d12 + 44"
"stats":
- !!int "19"
- !!int "16"
- !!int "14"
- !!int "1"
- !!int "15"
- !!int "4"
"speed": "30 ft., climb 20 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "5"
"damage_vulnerabilities": "poison"
"senses": "blindsight 15 ft., darkvision 60 ft., passive Perception 15"
"languages": ""
"cr": "8"
"traits":
- "desc": "While in sunlight, the snake has disadvantage on attack rolls and on Wisdom\
    \ ([Perception](Mechanics/Rules/skills.md#Perception)) checks that rely on sight.\
    \ When the snake begins its turn in sunlight, it immediately suffers 10 radiant\
    \ damage."
  "name": "Sunlight Vulnerability"
- "desc": "If damage reduces the snake to 0 hit points, it must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
    \ or from a critical hit. On a success, the snake drops to 1 hit point instead."
  "name": "Undead Fortitude"
"actions":
- "desc": "The snake makes two attacks: one with its bite and one with a constrict\
    \ attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 17\
    \ (3d8 + 4) piercing damage, and the target must make a DC 15 Constitution saving\
    \ throw, taking 17 (5d6) poison damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 17\
    \ (3d8 + 4) bludgeoning damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 16). Until this grapple ends, the creature is [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ and the snake cannot constrict another target."
  "name": "Constrict"
"source":
- "AitFR-DN"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AitFR-DN/Giant%20Zombie%20Constrictor%20Snake.webp"
```
^statblock