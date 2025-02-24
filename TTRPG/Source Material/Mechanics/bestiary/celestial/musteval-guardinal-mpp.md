---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/2
- monster/size/small
- monster/type/celestial
statblock: inline
aliases: ["Musteval Guardinal"]
---
# [Musteval Guardinal](Mechanics\bestiary\celestial/musteval-guardinal-mpp.md)
*Source: Morte's Planar Parade p. 33, Sigil and the Outlands, Turn of Fortune's Wheel*  

Mustevals are small, mousy guardinals skilled at evading danger. Their speed, stealthy nature, and illusion magic make them adept spies, scurrying through the multiverse to serve greater forces of good.

## Guardinals

Nomadic and peaceful, guardinals are animalistic Celestials who hail from Elysium. Guardinals resemble Humanoids with bestial traits. In their daily interactions, guardinals embody the beauty, calm, and righteousness of their home plane. Guardinals can be found throughout the Outlands, especially in Ecstasy, the gate-town to Elysium, and in Faunel, the gate-town to the Beastlands.

While guardinals are usually friendly and slow to anger, their supernatural virtue puts them at odds with the evil beings of the Lower Planes. Guardinals abhor wickedness and strike out against injustice and villainy without hesitation, determined to eradicate forces that threaten beauty and peace.

```statblock
"name": "Musteval Guardinal (MPP)"
"size": "Small"
"type": "celestial"
"alignment": "typically  Neutral Good"
"ac": !!int "13"
"hp": !!int "38"
"hit_dice": "11d6"
"stats":
- !!int "12"
- !!int "16"
- !!int "11"
- !!int "14"
- !!int "15"
- !!int "14"
"speed": "35 ft."
"saves":
  "Charisma": !!int "4"
  "Dexterity": !!int "5"
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "6"
"damage_resistances": "radiant"
"condition_immunities": "[frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "passive Perception 16"
"languages": "Celestial, Common"
"cr": "2"
"traits":
- "desc": "The musteval casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability:\n\nAt will: [dancing lights](Mechanics/spells/dancing-lights.md)\n\
    \n1/day each: [disguise self](Mechanics/spells/disguise-self.md), [invisibility](Mechanics/spells/invisibility.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The musteval makes two Bone Blade attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage plus 3 (1d6) radiant damage."
  "name": "Bone Blade"
"reactions":
- "desc": "When a creature ends its turn within 5 feet of the musteval, the musteval\
    \ can move up to half its speed. This movement doesn't provoke opportunity attacks."
  "name": "Skirmish Movement"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Musteval%20Guardinal.webp"
```
^statblock