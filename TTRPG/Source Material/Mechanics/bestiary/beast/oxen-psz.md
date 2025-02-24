---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1-2
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Oxen"]
---
# [Oxen](Mechanics\bestiary\beast/oxen-psz.md)
*Source: Plane Shift: Zendikar p. 34*  

The oxen (use the [giant goat](Mechanics/bestiary/beast/giant-goat.md) statistics) of Murasa's Pillar Plains are renowned for their stubbornness, but are still used as pack animals thanks to their tremendous strength.

```statblock
"name": "Oxen (PSZ)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "19"
"hit_dice": "3d10 + 3"
"stats":
- !!int "17"
- !!int "11"
- !!int "12"
- !!int "3"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "If the oxen moves at least 20 feet straight toward a target and then hits\
    \ it with a ram attack on the same turn, the target takes an extra 5 (2d4) bludgeoning\
    \ damage. If the target is a creature, it must succeed on a DC 13 Strength saving\
    \ throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Charge"
- "desc": "The oxen has advantage on Strength and Dexterity saving throws made against\
    \ effects that would knock it [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Sure-Footed"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (2d4\
    \ + 3) bludgeoning damage."
  "name": "Ram"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Oxen.webp"
```
^statblock