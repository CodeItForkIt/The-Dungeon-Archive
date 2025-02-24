---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Firefist"]
---
# [Firefist](Mechanics\bestiary\humanoid/firefist-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros firefists combine potent magic with peerless fighting ability, inspiring all who serve alongside them. They often act as the point of contact between the Boros Legion and the angelic leaders.

```statblock
"name": "Firefist (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "4"
  "Religion": !!int "3"
"senses": "passive Perception 13"
"languages": "any one language (usually Common)"
"cr": "7"
"traits":
- "desc": "The firefist is a 9th-level Boros spellcaster. Its spellcasting ability\
    \ is Wisdom (spell save DC 14, +6 to hit with spell attacks). It has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [fire bolt](Mechanics/spells/fire-bolt.md),\
    \ [light](Mechanics/spells/light.md), [sacred flame](Mechanics/spells/sacred-flame.md),\
    \ [spare the dying](Mechanics/spells/spare-the-dying.md)\n\n1st level (4 slots):\
    \ [guiding bolt](Mechanics/spells/guiding-bolt.md), [healing word](Mechanics/spells/healing-word.md),\
    \ [heroism](Mechanics/spells/heroism.md), [shield of faith](Mechanics/spells/shield-of-faith.md)\n\
    \n2nd level (3 slots): [lesser restoration](Mechanics/spells/lesser-restoration.md),\
    \ [scorching ray](Mechanics/spells/scorching-ray.md)\n\n3rd level (3 slots):\
    \ [blinding smite](Mechanics/spells/blinding-smite.md), [crusader's mantle](Mechanics/spells/crusaders-mantle.md),\
    \ [revivify](Mechanics/spells/revivify.md)\n\n4th level (3 slots): [banishment](Mechanics/spells/banishment.md),\
    \ [wall of fire](Mechanics/spells/wall-of-fire.md)\n\n5th level (1 slots):\
    \ [flame strike](Mechanics/spells/flame-strike.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The firefist makes two greatsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage."
  "name": "Greatsword"
"reactions":
- "desc": "When the firefist or one creature it can see within 30 feet of it makes\
    \ an attack roll, the firefist grants a +10 bonus to that roll."
  "name": "Guided Attack (Recharges after a Short or Long Rest)"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Firefist.webp"
```
^statblock