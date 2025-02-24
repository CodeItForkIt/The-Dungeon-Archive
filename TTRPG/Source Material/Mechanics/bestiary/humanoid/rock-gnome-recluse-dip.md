---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dip
- monster/cr/1-4
- monster/size/small
- monster/type/humanoid/gnome
statblock: inline
aliases: ["Rock Gnome Recluse"]
---
# [Rock Gnome Recluse](Mechanics\bestiary\humanoid/rock-gnome-recluse-dip.md)
*Source: Dragon of Icespire Peak p. 62*  

Rock gnome recluses are skilled in the arcane arts. They use their magical talents to create all kinds of wondrous inventions, very few of which work as intended.

```statblock
"name": "Rock Gnome Recluse (DIP)"
"size": "Small"
"type": "humanoid"
"subtype": "gnome"
"alignment": "Chaotic Neutral"
"ac": !!int "10"
"ac_class": "13 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "7"
"hit_dice": "2d6"
"stats":
- !!int "6"
- !!int "11"
- !!int "10"
- !!int "15"
- !!int "10"
- !!int "13"
"speed": "25 ft."
"skillsaves":
  "History": !!int "4"
  "Arcana": !!int "4"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Gnomish"
"cr": "1/4"
"traits":
- "desc": "The gnome is a 2nd-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 12, +4 to hit with spell attacks). It has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [mage hand](Mechanics/spells/mage-hand.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md), [ray of frost](Mechanics/spells/ray-of-frost.md)\
    \ (see \"Actions\" below)\n\n1st level (3 slots): [detect magic](Mechanics/spells/detect-magic.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md), [magic missile](Mechanics/spells/magic-missile.md)\
    \ (see \"Actions\" below), [shield](Mechanics/spells/shield.md)"
  "name": "Spellcasting"
- "desc": "The gnome has advantage on Intelligence, Wisdom, and Charisma saving throws\
    \ against magic."
  "name": "Gnome Cunning"
"actions":
- "desc": "The gnome creates three magical darts. Each dart hits a creature the gnome\
    \ chooses within 120 feet of it and deals 3 (1d4 + 1) force damage."
  "name": "Magic Missile (Expends a 1st-Level Spell Slot)"
- "desc": "Ranged Spell Attack: +4 to hit, range 60 ft., one creature. Hit:\
    \ 4 (1d8) cold damage, and the target's speed is reduced by 10 feet until the\
    \ start of the gnome's next turn."
  "name": "Ray of Frost"
"source":
- "DIP"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DIP/Rock%20Gnome%20Recluse.webp"
```
^statblock