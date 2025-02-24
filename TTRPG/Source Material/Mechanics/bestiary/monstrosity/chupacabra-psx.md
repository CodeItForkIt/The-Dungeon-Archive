---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/3
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Chupacabra"]
---
# [Chupacabra](Mechanics\bestiary\monstrosity/chupacabra-psx.md)
*Source: Plane Shift: Ixalan p. 9*  

Indescribable creatures of nightmare lurk in the ruins and dark places of Ixalan. Many are thought to be the corrupted remnants of the life energy and brilliant light left behind in places the Sun Empire has abandoned. Such creatures include a monster that lurks in the darkness of the jungle and feeds on the blood of mammals and dinosaurs, called the chupacabra. It is stealthy and elusive, known more by the blood-drained prey it leaves behind than by actual physical sightings.

## Night Terrors

The legends of the Sun Empire are populated with the enemies of the sun—terrible monsters that threaten to devour its light and undo its work. Unfortunately for the people of Ixalan, these are not just creatures of legend but real monsters with supernatural power, lurking in the darkness of night and the shadows of ancient ruins and crypts.

```statblock
"name": "Chupacabra (PSX)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"stats":
- !!int "15"
- !!int "14"
- !!int "16"
- !!int "6"
- !!int "13"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical weapons"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": ""
"cr": "3"
"traits":
- "desc": "While in sunlight, the chupacabra has disadvantage on attack rolls, as\
    \ well as on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks\
    \ that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) piercing damage. If the target is a creature, it must succeed on a DC\
    \ 13 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature that is [prone](Mechanics/Rules/conditions.md#Prone),\
    \ [incapacitated](Mechanics/Rules/conditions.md#Incapacitated), or [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ Hit: 5 (1d6 + 2) necrotic damage. The target must succeed on a DC 13 Constitution\
    \ saving throw or its hit point maximum is reduced by an amount equal to the damage\
    \ taken, and the chupacabra regains hit points equal to that amount. The reduction\
    \ lasts until the target finishes a long rest. The target dies if this effect\
    \ reduces its hit point maximum to 0."
  "name": "Drain Blood"
"reactions":
- "desc": "If a creature within 5 feet of the chupacabra stands up, the chupacabra\
    \ can use its reaction to make a bite attack."
  "name": "Pin"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Chupacabra.webp"
```
^statblock