---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/4
- monster/size/medium
- monster/type/dragon
statblock: inline
aliases: ["Amonkhet Dragon Wyrmling"]
---
# [Amonkhet Dragon Wyrmling](Mechanics\bestiary\dragon/amonkhet-dragon-wyrmling-psa.md)
*Source: Plane Shift: Amonkhet p. 33*  

Dragons are fierce monsters with heavy reptilian bodies, crocodilian heads, and leathery wings, and are dis-tinguished by their ability to breathe fire. Though Nicol Bolas is also a dragon, he feels no kinship for these savage, dim-witted beasts. They live mostly in the remote reaches of the desert, soaring in lazy circles through the sky as they search for prey. Sometimes they are captured and brought inside the Hekma, where they are put to use within the trials of the five gods—especially in the climactic battles of the final Trial of Zeal.

The dragons of Amonkhet are **red dragons**, though they lack the high Intelligence of the red dragons in the "Monster Manual".

```statblock
"name": "Amonkhet Dragon Wyrmling (PSA)"
"size": "Medium"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "19"
- !!int "10"
- !!int "17"
- !!int "5"
- !!int "11"
- !!int "15"
"speed": "30 ft., climb 30 ft., fly 60 ft."
"saves":
  "Charisma": !!int "4"
  "Dexterity": !!int "2"
  "Wisdom": !!int "2"
  "Constitution": !!int "5"
"skillsaves":
  "Stealth": !!int "2"
  "Perception": !!int "4"
"damage_immunities": "fire"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 14"
"languages": "Draconic"
"cr": "4"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (1d10\
    \ + 4) piercing damage plus 3 (1d6) fire damage."
  "name": "Bite"
- "desc": "The dragon exhales fire in a 15-foot cone. Each creature in that area must\
    \ make a DC 13 Dexterity saving throw, taking 24 (7d6) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
"source":
- "PSA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Amonkhet%20Dragon%20Wyrmling.webp"
```
^statblock