---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/6
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Chaplain"]
---
# [Chaplain](Mechanics\bestiary\humanoid/chaplain-dodk.md)
*Source: Dungeons of Drakkenheim p. 218*  

Ordained with prayer beads and holy symbols, a chaplain is a faithful warrior-priest who accompanies questing knights and military regiments on campaign. During moments of peace, some will prepare continual flame, sending, speak with dead, remove curse, greater restoration, scrying, and raise dead as the need requires. Other chaplains are fiery zealots who can prepare faerie fire, burning hands, scorching ray, flaming sphere, fireball, and wall of fire.

```statblock
"name": "Chaplain (DoDk)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[chain mail](Mechanics/items/chain-mail.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "13"
- !!int "10"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "13"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "6"
"skillsaves":
  "Religion": !!int "3"
  "Insight": !!int "6"
  "Persuasion": !!int "4"
"senses": "passive Perception 13"
"languages": "Any two"
"cr": "6"
"traits":
- "desc": "The chaplain is a 9th-level spellcaster that uses Wisdom as its spellcasting\
    \ ability (spell save DC 12; +4 to hit with spell attacks). They have the following\
    \ cleric spells prepared:\n\nCantrips (at will): [light](Mechanics/spells/light.md),\
    \ [mending](Mechanics/spells/mending.md), [sacred flame](Mechanics/spells/sacred-flame.md),\
    \ [spare the dying](Mechanics/spells/spare-the-dying.md)\n\n1st level (4 slots):\
    \ [bless](Mechanics/spells/bless.md), [guiding bolt](Mechanics/spells/guiding-bolt.md),\
    \ [healing word](Mechanics/spells/healing-word.md)\n\n2nd level (3 slots):\
    \ [lesser restoration](Mechanics/spells/lesser-restoration.md), [prayer of healing](Mechanics/spells/prayer-of-healing.md),\
    \ [spiritual weapon](Mechanics/spells/spiritual-weapon.md)\n\n3rd level (3 slots):\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [purge contamination](Mechanics/spells/purge-contamination-dodk.md),\
    \ [spirit guardians](Mechanics/spells/spirit-guardians.md)\n\n4th level (3 slots):\
    \ [banishment](Mechanics/spells/banishment.md), [divination](Mechanics/spells/divination.md)\n\
    \n5th level (1 slots): [flame strike](Mechanics/spells/flame-strike.md)"
  "name": "Spellcasting"
- "desc": "The chaplain has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ or [frightened](Mechanics/Rules/conditions.md#Frightened)."
  "name": "Devotion"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d6 + 1) piercing damage or 5 (1d8 + 1) damage\
    \ when used in two hands to make a melee attack."
  "name": "Spear"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Chaplain.webp"
```
^statblock