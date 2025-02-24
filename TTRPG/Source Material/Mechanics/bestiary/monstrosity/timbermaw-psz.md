---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Timbermaw"]
---
# [Timbermaw](Mechanics\bestiary\monstrosity/timbermaw-psz.md)
*Source: Plane Shift: Zendikar p. 34*  

Timbermaws dwell in the hollow trunks of strange floating trees, emerging with deadly speed when prey wanders near. (The [grick](Mechanics/bestiary/monstrosity/grick.md) statistics can represent a timbermaw, adjusting its stone camouflage trait to hide it in the woodlands.)

```statblock
"name": "Timbermaw (PSZ)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "6d8"
"stats":
- !!int "14"
- !!int "14"
- !!int "11"
- !!int "3"
- !!int "14"
- !!int "5"
"speed": "30 ft., climb 30 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": ""
"cr": "2"
"traits":
- "desc": "The timbermaw has advantage on Dexterity ([Stealth](Mechanics/Rules/skills.md#Stealth))\
    \ checks made to hide in rocky terrain."
  "name": "Stone Camouflage"
"actions":
- "desc": "The timbermaw makes one attack with its tentacles. If that attack hits,\
    \ the timbermaw can make one beak attack against the same target."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) slashing damage."
  "name": "Tentacles"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage."
  "name": "Beak"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Timbermaw.webp"
```
^statblock