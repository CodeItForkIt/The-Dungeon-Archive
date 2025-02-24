---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/4
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
aliases: ["Hands of Havoc Fire Starter"]
---
# [Hands of Havoc Fire Starter](Mechanics\bestiary\humanoid/hands-of-havoc-fire-starter-mpp.md)
*Source: Morte's Planar Parade p. 58, Sigil and the Outlands, Turn of Fortune's Wheel*  

The pyromaniacal agents known as fire starters burn away oppressive systems through chaos and flame. They wield hammers that emit magical flames—perfect for smashing and burning.

```statblock
"name": "Hands of Havoc Fire Starter (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](Mechanics/items/breastplate.md)"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"stats":
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "10"
- !!int "16"
- !!int "11"
"speed": "30 ft."
"saves":
  "Strength": !!int "5"
  "Constitution": !!int "4"
"damage_resistances": "fire"
"senses": "passive Perception 13"
"languages": "Common plus one more language"
"cr": "4"
"actions":
- "desc": "The fire starter makes two Havoc Hammer or Havoc Flask attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage plus 9 (2d8) fire damage. If the target is a creature,\
    \ magical flames cling to it, causing it to take 3 (1d6) fire damage at the\
    \ start of each of its turns. Immediately after taking this damage on its turn,\
    \ the target can make a DC 13 Dexterity saving throw, ending the effect on itself\
    \ on a successful save."
  "name": "Havoc Hammer"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/90 ft., one target. Hit:\
    \ 13 (2d12) fire damage. If the target is a creature, magical flames cling to\
    \ it, causing it to take 3 (1d6) fire damage at the start of each of its turns.\
    \ Immediately after taking this damage on its turn, the target can make a DC 13\
    \ Dexterity saving throw, ending the effect on itself on a successful save.\n\n\
    After the fire starter throws the flask, roll a d6; on a 3 or lower, the fire\
    \ starter has no more flasks to throw."
  "name": "Havoc Flask"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Hands%20of%20Havoc%20Fire%20Starter.webp"
```
^statblock