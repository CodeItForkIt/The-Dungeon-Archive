---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/5
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Mercane"]
---
# [Mercane](Mechanics\bestiary\celestial/mercane-bam.md)
*Source: Boo's Astral Menagerie p. 37, Light of Xaryxis*  

Mercanes are the mysterious, magical creations of one or more deities whose portfolios revolve around fair commerce. Standing 12 feet tall, they are lanky blue beings who dress in elegant robes and have elongated heads and long, spindly fingers.

Mercanes conduct most of their business in Wildspace and the Astral Sea. To a mercane, commerce can take many forms, from the trading of goods and services to the trading of ideas and information. Mercanes are best known, however, for procuring and selling magic items, including artifacts and spelljamming helms. It's rare to see more than one mercane at a time, though it's common for a mercane to be accompanied by underlings or bodyguards.

Mercanes will conduct business with anyone, fairly and reliably, provided the other party has neither harmed nor swindled another mercane in the past. Mercanes have a special form of telepathy that enables them to communicate with one another across the multiverse. A mercane often uses this ability to warn another mercanes about individuals who are dangerous or unreliable. Once a mercane has been offended by someone, getting back into their good graces is next to impossible.

```statblock
"name": "Mercane (BAM)"
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
- "desc": "The mercane casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\nAt\
    \ will: [detect magic](Mechanics/spells/detect-magic.md), [light](Mechanics/spells/light.md)\n\
    \n1/day each: [dimension door](Mechanics/spells/dimension-door.md), [invisibility](Mechanics/spells/invisibility.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md) (self only)"
  "name": "Spellcasting (Psionics)"
- "desc": "The mercane can communicate telepathically with any other mercane it knows,\
    \ regardless of the distance between them."
  "name": "Mercane Telepathy"
"actions":
- "desc": "The mercane makes three Psi-Imbued Blade attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage, and if the target is a creature, it must succeed\
    \ on a DC 15 Wisdom saving throw or be [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ of the mercane until the end of the target's next turn."
  "name": "Psi-Imbued Blade"
"source":
- "BAM"
- "LoX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Mercane.webp"
```
^statblock