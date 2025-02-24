---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ai
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/elf
statblock: inline
aliases: ["Walnut Dankgrass"]
---
# [Walnut Dankgrass](Mechanics\bestiary\npc/walnut-dankgrass-ai.md)
*Source: Acquisitions Incorporated p. 204*  

> [!quote]  
> 
> The war ever rages.

Growing up in an all-female clan of druids, healers, and rangers, Walnut Dankgrass was drawn to the role of protector from her earliest years. Dedicated to Mielikki, the matriarchal clan known as the Enclave Panax Anima defended the unspoiled wild by word and blade (with the latter option more prevalent by far). But when tragedy struck the enclave, Walnut's clan was destroyed to the last-leaving her with nothing but the all-consuming desire to seek out and destroy those responsible.

As a guardian of the wild, Walnut has long held an antipathy toward civilization and anything urban. However, understanding that civilization was the source of the evil that destroyed her people, she makes the city her home now. She embraces her role as the "C" Team's documancer, knowing that the city's power-and its weaknesses-can be fully gleaned only from within.

Walnut distrusts most folk she meets, except for those whose bearing reflects the matriarchal structure she was once part of. No matter what shape her struggles take, she knows instinctively that her beliefs are right and true-and that she will follow those beliefs to the bitter end.

```statblock
"name": "Walnut Dankgrass (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Lawful Neutral"
"ac": !!int "14"
"ac_class": "[leather armor](Mechanics/items/leather-armor.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "8"
- !!int "16"
- !!int "14"
- !!int "10"
- !!int "18"
- !!int "10"
"speed": "35 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "2"
"skillsaves":
  "Athletics": !!int "1"
  "Stealth": !!int "5"
  "Insight": !!int "6"
  "Perception": !!int "6"
  "Survival": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "3"
"traits":
- "desc": "Walnut is a 7th-level spellcaster. Her spellcasting ability is Wisdom (spell\
    \ save DC 14, +6 to hit with spell attacks). She has the following druid spells\
    \ prepared:\n\nCantrips (at will): [druidcraft](Mechanics/spells/druidcraft.md),\
    \ [produce flame](Mechanics/spells/produce-flame.md), [thorn whip](Mechanics/spells/thorn-whip.md)\n\
    \n1st level (4 slots): [cure wounds](Mechanics/spells/cure-wounds.md), [entangle](Mechanics/spells/entangle.md),\
    \ [thunderwave](Mechanics/spells/thunderwave.md)\n\n2nd level (3 slots): [flame\
    \ blade](Mechanics/spells/flame-blade.md), [moonbeam](Mechanics/spells/moonbeam.md),\
    \ [pass without trace](Mechanics/spells/pass-without-trace.md)\n\n3rd level\
    \ (3 slots): [call lightning](Mechanics/spells/call-lightning.md), [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [plant growth](Mechanics/spells/plant-growth.md)\n\n4th level (1 slots):\
    \ [blight](Mechanics/spells/blight.md), [freedom of movement](Mechanics/spells/freedom-of-movement.md)"
  "name": "Spellcasting"
- "desc": "Walnut has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed),\
    \ and magic can't put her to sleep."
  "name": "Fey Ancestry"
- "desc": "Walnut can attempt to hide even when she is only lightly obscured by foliage,\
    \ heavy rain, falling snow, mist, and other natural phenomena."
  "name": "Mask of the Wild"
- "desc": "As a bonus action, Walnut can assume the shape of a dire wolf. She can\
    \ stay in this form for 3 hours or until she reverts to her normal form as a bonus\
    \ action. She automatically reverts if she falls [unconscious](Mechanics/Rules/conditions.md#Unconscious),\
    \ drops to 0 hit points, or dies.\n\nWhile transformed, Walnut's game statistics\
    \ are replaced by the statistics of the dire wolf, except she retains her alignment,\
    \ personality, and Intelligence, Wisdom, and Charisma scores.\n\nHer attacks in\
    \ beast form are magical. While in beast form, Walnut can use a bonus action to\
    \ expend one spell slot and regain 1d8 hit points per level of the spell slot\
    \ expended."
  "name": "Wild Shape (Recharges after a Short or Long rest)"
"actions":
- "desc": "Walnut makes two attacks with Foremother or her longbow."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage."
  "name": "Foremother (+1 Scimitar)"
- "desc": "Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage."
  "name": "Longbow"
"source":
- "AI"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AI/Walnut%20Dankgrass.webp"
```
^statblock