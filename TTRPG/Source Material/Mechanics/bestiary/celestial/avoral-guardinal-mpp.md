---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/9
- monster/size/medium
- monster/type/celestial
statblock: inline
aliases: ["Avoral Guardinal"]
---
# [Avoral Guardinal](Mechanics\bestiary\celestial/avoral-guardinal-mpp.md)
*Source: Morte's Planar Parade p. 32, Sigil and the Outlands*  

Avorals are eagle-like bipeds with winged arms and keen, golden eyes. Prone to wander, these avian Celestials leave Elysium more frequently than their counterparts, meandering across the Outlands to wherever the winds might take them. Solitary scouts and skirmishers, avorals are nimble aerial combatants, able to swiftly dive at foes from the heavens and tear into them with razor-sharp talons.

## Guardinals

Nomadic and peaceful, guardinals are animalistic Celestials who hail from Elysium. Guardinals resemble Humanoids with bestial traits. In their daily interactions, guardinals embody the beauty, calm, and righteousness of their home plane. Guardinals can be found throughout the Outlands, especially in Ecstasy, the gate-town to Elysium, and in Faunel, the gate-town to the Beastlands.

While guardinals are usually friendly and slow to anger, their supernatural virtue puts them at odds with the evil beings of the Lower Planes. Guardinals abhor wickedness and strike out against injustice and villainy without hesitation, determined to eradicate forces that threaten beauty and peace.

```statblock
"name": "Avoral Guardinal (MPP)"
"size": "Medium"
"type": "celestial"
"alignment": "typically  Neutral Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "172"
"hit_dice": "23d8 + 69"
"stats":
- !!int "16"
- !!int "19"
- !!int "17"
- !!int "16"
- !!int "16"
- !!int "18"
"speed": "30 ft., fly 50 ft."
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "8"
"skillsaves":
  "Religion": !!int "7"
  "Perception": !!int "11"
"damage_resistances": "radiant"
"condition_immunities": "[frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 21"
"languages": "Celestial, Common"
"cr": "9"
"traits":
- "desc": "The avoral casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n1/day\
    \ each: [command](Mechanics/spells/command.md), [hold person](Mechanics/spells/hold-person.md)"
  "name": "Spellcasting"
- "desc": "If the avoral is flying, dives at least 30 feet in a straight line toward\
    \ a Medium or smaller creature, and ends within 5 feet of it, that creature must\
    \ succeed on a DC 15 Strength saving throw or take 14 (4d6) piercing damage\
    \ and have the [prone](Mechanics/Rules/conditions.md#Prone) condition."
  "name": "Dive Attack"
- "desc": "The avoral doesn't provoke an opportunity attack when it flies out of an\
    \ enemy's reach."
  "name": "Flyby"
"actions":
- "desc": "The avoral makes two Talon attacks. It can replace one attack with a use\
    \ of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage plus 13 (2d12) radiant damage."
  "name": "Talon"
"source":
- "MPP"
- "SatO"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Avoral%20Guardinal.webp"
```
^statblock