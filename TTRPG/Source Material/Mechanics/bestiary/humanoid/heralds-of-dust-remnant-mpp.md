---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/4
- monster/size/small-or-medium
- monster/type/humanoid
statblock: inline
aliases: ["Heralds of Dust Remnant"]
---
# [Heralds of Dust Remnant](Mechanics\bestiary\humanoid/heralds-of-dust-remnant-mpp.md)
*Source: Morte's Planar Parade p. 59, Adventure Atlas: The Mortuary, Sigil and the Outlands, Turn of Fortune's Wheel*  

Remnants are Dusters who sought undeath via rituals but failed. Liaisons and spies, these agents exist in a halfway point between life and death.

```statblock
"name": "Heralds of Dust Remnant (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"stats":
- !!int "8"
- !!int "14"
- !!int "15"
- !!int "17"
- !!int "14"
- !!int "11"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "4"
  "Arcana": !!int "5"
"damage_resistances": "necrotic"
"senses": "passive Perception 14"
"languages": "Common plus three more languages"
"cr": "4"
"traits":
- "desc": "The remnant casts one of the following spells, requiring no material components\
    \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\nAt\
    \ will: [mage armor](Mechanics/spells/mage-armor.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md)\n\n1/day each:\
    \ [bane](Mechanics/spells/bane.md), [dimension door](Mechanics/spells/dimension-door.md),\
    \ [web](Mechanics/spells/web.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The remnant makes two Necrotic Surge attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 14 (2d10 + 3) necrotic damage."
  "name": "Necrotic Surge"
"bonus_actions":
- "desc": "The remnant becomes partially incorporeal for as long as it maintains [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ on the effect (as if concentrating on a spell). While partially incorporeal,\
    \ the remnant has resistance to bludgeoning, piercing, and slashing damage."
  "name": "Phase (2/Day)"
"source":
- "MPP"
- "AATM"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Heralds%20of%20Dust%20Remnant.webp"
```
^statblock