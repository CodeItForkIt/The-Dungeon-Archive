---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/rtg
- monster/cr/5
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Rotter"]
---
# [Rotter](Mechanics\bestiary\construct/rotter-rtg.md)
*Source: Return to Glory p. 34*  

```statblock
"name": "Rotter (RtG)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor, [shield](Mechanics/items/shield.md)"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "18"
- !!int "12"
- !!int "16"
- !!int "10"
- !!int "13"
- !!int "8"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Athletics": !!int "7"
  "Stealth": !!int "4"
  "Perception": !!int "4"
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "telepathy 60 ft."
"cr": "5"
"traits":
- "desc": "In the rotter's hand, its club is magical and deals 7 (3d4) extra damage\
    \ (included in its attacks)."
  "name": "Magic Club"
- "desc": "The rotter has advantage on Dexterity ([Stealth](Mechanics/Rules/skills.md#Stealth))\
    \ checks it makes in terrain with ample obscuring plant life."
  "name": "Plant Camouflage"
- "desc": "The rotter regains 10 hit points at the start of its turn if it is in contact\
    \ with the ground. If the rotter takes fire damage, this trait doesn't function\
    \ at the start of the rotter's next turn. The rotter dies only if it starts its\
    \ turn with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
- "desc": "The rotter can see and hear what any plant within 120 ft can see and hear.\
    \ In addition, the rotter can communicate telepathically with any plant within\
    \ this range."
  "name": "Shared Senses"
- "desc": "Once on each of its turns, the rotter can use 10 feet of its movement to\
    \ step magically into one copse of mushrooms within 5 feet of it and emerge from\
    \ a second copse of mushrooms within 60 feet of it, appearing in an unoccupied\
    \ space within 5 feet of the second copse. Both copses of mushrooms must be Large\
    \ or bigger. The rotter doesn't need to be able to see the second copse to use\
    \ this ability."
  "name": "Tree Stride"
"actions":
- "desc": "The rotter makes two attacks with its club."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 14\
    \ (4d4 + 4) bludgeoning damage."
  "name": "Club"
"source":
- "RtG"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/RtG/Rotter.webp"
```
^statblock