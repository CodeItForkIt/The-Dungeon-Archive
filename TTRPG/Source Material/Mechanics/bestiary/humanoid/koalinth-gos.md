---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/gos
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/goblinoid
statblock: inline
aliases: ["Koalinth"]
---
# [Koalinth](Mechanics\bestiary\humanoid/koalinth-gos.md)
*Source: Ghosts of Saltmarsh p. 239*  

The koalinth, found in Danger at Dunwater, are martial and aggressive aquatic hobgoblins, with brightly colored faces and functional gills. They are known for their ferocity, and for their hatred of elves.

```statblock
"name": "Koalinth (GoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "[scale mail](Mechanics/items/scale-mail.md)"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "13"
- !!int "11"
- !!int "12"
- !!int "11"
- !!int "10"
- !!int "11"
"speed": "30 ft., swim 20 ft."
"saves":
  "Dexterity": !!int "2"
"skillsaves":
  "Athletics": !!int "3"
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Goblin"
"cr": "1/2"
"traits":
- "desc": "The koalinth can breathe air and water."
  "name": "Amphibious"
- "desc": "Once per turn, the koalinth can deal an extra 7 (2d6) damage to a creature\
    \ it hits with a weapon attack if that creature is within 5 feet of an ally of\
    \ the koalinth that isn't [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Martial Advantage"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Trident"
"source":
- "GoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Koalinth.webp"
```
^statblock