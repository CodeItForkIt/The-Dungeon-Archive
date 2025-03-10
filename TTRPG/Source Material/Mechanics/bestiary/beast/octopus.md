---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/size/small
- monster/type/beast
statblock: inline
aliases: ["Octopus"]
---
# [Octopus](Mechanics\bestiary\beast/octopus.md)
*Source: Monster Manual p. 333, Storm King's Thunder, Ghosts of Saltmarsh, Infernal Machine Rebuild, Icewind Dale: Rime of the Frostmaiden, The Wild Beyond the Witchlight. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Octopus"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"stats":
- !!int "4"
- !!int "15"
- !!int "11"
- !!int "3"
- !!int "10"
- !!int "4"
"speed": "5 ft., swim 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"senses": "darkvision 30 ft., passive Perception 12"
"languages": ""
"cr": "0"
"traits":
- "desc": "While out of water, the octopus can hold its breath for 30 minutes."
  "name": "Hold Breath"
- "desc": "The octopus has advantage on Dexterity ([Stealth](Mechanics/Rules/skills.md#Stealth))\
    \ checks made while underwater."
  "name": "Underwater Camouflage"
- "desc": "The octopus can breathe only underwater."
  "name": "Water Breathing"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 bludgeoning\
    \ damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 10). Until this grapple ends, the octopus can't use its tentacles\
    \ on another target."
  "name": "Tentacles"
- "desc": "A 5-foot-radius cloud of ink extends all around the octopus if it is underwater.\
    \ The area is heavily obscured for 1 minute, although a significant current can\
    \ disperse the ink. After releasing the ink, the octopus can use the Dash action\
    \ as a bonus action."
  "name": "Ink Cloud (Recharges after a Short or Long Rest)"
"source":
- "MM"
- "SKT"
- "GoS"
- "IMR"
- "IDRotF"
- "WBtW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Octopus.webp"
```
^statblock