---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/5
- monster/size/huge
- monster/type/beast
statblock: inline
aliases: ["Whirlwyrm"]
---
# [Whirlwyrm](Mechanics\bestiary\beast/whirlwyrm-tofw.md)
*Source: Turn of Fortune's Wheel p. 52*  

```statblock
"name": "Whirlwyrm (ToFW)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "9d12 + 27"
"stats":
- !!int "21"
- !!int "9"
- !!int "17"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "30 ft., swim 50 ft."
"skillsaves":
  "Stealth": !!int "5"
"senses": "passive Perception 10"
"languages": ""
"cr": "5"
"traits":
- "desc": "The whirlwyrm can hold its breath for 30 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "The whirlwyrm makes two attacks: one with its bite and one with its tail."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 21\
    \ (3d10 + 5) piercing damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 16). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the whirlwyrm can't bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target not [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the whirlwyrm. Hit: 14 (2d8 + 5) bludgeoning damage. If the target is\
    \ a creature, it must succeed on a DC 16 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Tail"
"source":
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/Whirlwyrm.webp"
```
^statblock