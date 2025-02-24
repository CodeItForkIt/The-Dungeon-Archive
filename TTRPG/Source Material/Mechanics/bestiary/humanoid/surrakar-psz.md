---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/lizardfolk
statblock: inline
aliases: ["Surrakar"]
---
# [Surrakar](Mechanics\bestiary\humanoid/surrakar-psz.md)
*Source: Plane Shift: Zendikar p. 26*  

The surrakar are a race of hulking amphibian humanoids native to Bala Ged. They have broad shoulders and long arms that drag on the ground when they walk. Their splayed feet and hands are webbed, and long tusks protrude from their large mouths. They have little culture and no written language, and some members of other races believe they are merely animals with no true language at all.

Surrakar are similar to D&D's [lizardfolk](Mechanics/bestiary/humanoid/lizardfolk.md).

```statblock
"name": "Surrakar (PSZ)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "natural armor, [shield](Mechanics/items/shield.md)"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"stats":
- !!int "15"
- !!int "10"
- !!int "13"
- !!int "7"
- !!int "12"
- !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
  "Survival": !!int "5"
"senses": "passive Perception 13"
"languages": "Draconic"
"cr": "1/2"
"traits":
- "desc": "The surrakar can hold its breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "The surrakar makes two melee attacks, each one with a different weapon."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Heavy Club"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage."
  "name": "Javelin"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Spiked Shield"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Surrakar.webp"
```
^statblock