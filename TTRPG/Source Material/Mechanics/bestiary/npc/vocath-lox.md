---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/lox
- monster/cr/5
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Vocath"]
---
# [Vocath](Mechanics\bestiary\npc/vocath-lox.md)
*Source: Light of Xaryxis p. 42*  

```statblock
"name": "Vocath (LoX)"
"size": "Large"
"type": "celestial"
"alignment": "typically  Lawful Neutral"
"ac": !!int "13"
"ac_class": "[mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"stats":
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "18"
- !!int "16"
- !!int "15"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
"skillsaves":
  "Insight": !!int "9"
  "Perception": !!int "6"
  "Persuasion": !!int "5"
"senses": "passive Perception 16"
"languages": "Common, Giant, telepathy 60 ft. (see also Mercane telepathy)"
"cr": "5"
"traits":
- "desc": "Vocath casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\nAt\
    \ will: [detect magic](Mechanics/spells/detect-magic.md), [light](Mechanics/spells/light.md)\n\
    \n1/day each: [dimension door](Mechanics/spells/dimension-door.md), [invisibility](Mechanics/spells/invisibility.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md) (self only)"
  "name": "Spellcasting (Psionics)"
- "desc": "Vocath can communicate telepathically with any other mercane it knows,\
    \ regardless of the distance between them."
  "name": "Mercane Telepathy"
"actions":
- "desc": "Vocath makes three Psi-Imbued Blade attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage, and if the target is a creature, it must succeed\
    \ on a DC 15 Wisdom saving throw or be [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ of Vocath until the end of the target's next turn."
  "name": "Psi-Imbued Blade"
"source":
- "LoX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LoX/Vocath.webp"
```
^statblock