---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/4
- monster/size/medium
- monster/type/undead/elf
statblock: inline
aliases: ["Leedara"]
---
# [Leedara](Mechanics\bestiary\npc/leedara-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 58*  

Leedara died during the Cataclysm over three hundred years ago. Once an elven priest, Leedara witnessed her companion and fellow priest, Isolde, drawn into the grim fate of the wicked Knight of Solamnia, Lord Loren Soth. When Soth failed his gods-given quest to prevent the Cataclysm, he became cursed to exist forever as a death knight. As part of his curse, Leedara and several of her companions returned as deathless spirits devoted to ensuring Soth never finds peace.

```statblock
"name": "Leedara (DSotDQ)"
"size": "Medium"
"type": "undead"
"subtype": "elf"
"alignment": "Neutral"
"ac": !!int "11"
"hp": !!int "45"
"hit_dice": "10d8"
"stats":
- !!int "7"
- !!int "13"
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "17"
"speed": "0 ft., fly 40 ft."
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Any languages she knew in life"
"cr": "4"
"traits":
- "desc": "Leedara can see 60 feet into the Ethereal Plane when she is on the Material\
    \ Plane, and vice versa."
  "name": "Ethereal Sight"
- "desc": "Leedara can move through other creatures and objects as if they were difficult\
    \ terrain. She takes 5 (1d10) force damage if she ends her turn inside an object."
  "name": "Incorporeal Movement"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 17\
    \ (4d6 + 3) necrotic damage."
  "name": "Withering Touch"
- "desc": "Leedara enters the Ethereal Plane from the Material Plane, or vice versa.\
    \ She is visible on the Material Plane while she is in the Border Ethereal, and\
    \ vice versa, yet she can't affect or be affected by anything on the other plane."
  "name": "Etherealness"
- "desc": "Each non-undead creature within 60 feet of Leedara that can see her must\
    \ succeed on a DC 13 Wisdom saving throw or be [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. If the save fails by 5 or more, the target also ages 1d4 × 10\
    \ years. A [frightened](Mechanics/Rules/conditions.md#Frightened) target can repeat\
    \ the saving throw at the end of each of its turns, ending the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition on itself on a success. If a target's saving throw is successful or\
    \ the effect ends for it, the target is immune to Leedara's Horrifying Visage\
    \ for the next 24 hours. The aging effect can be reversed with a [greater restoration](Mechanics/spells/greater-restoration.md)\
    \ spell, but only within 24 hours of it occurring."
  "name": "Horrifying Visage"
- "desc": "One humanoid that the ghost can see within 5 feet of it must succeed on\
    \ a DC 13 Charisma saving throw or be possessed by Leedara; Leedara then disappears,\
    \ and the target is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ and loses control of its body. Leedara now controls the body but doesn't deprive\
    \ the target of awareness. Leedara can't be targeted by any attack, spell, or\
    \ other effect, except ones that turn undead, and she retains her alignment, Intelligence,\
    \ Wisdom, Charisma, and immunity to being [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ and [frightened](Mechanics/Rules/conditions.md#Frightened). She otherwise uses\
    \ the possessed target's statistics, but doesn't gain access to the target's knowledge,\
    \ class features, or proficiencies.\n\nThe possession lasts until the body drops\
    \ to 0 hit points, Leedara ends it as a bonus action, or Leedara is turned or\
    \ forced out by an effect like the [dispel evil and good](Mechanics/spells/dispel-evil-and-good.md)\
    \ spell. When the possession ends, Leedara reappears in an unoccupied space within\
    \ 5 feet of the body. The target is immune to Leedara's Possession for 24 hours\
    \ after succeeding on the saving throw or after the possession ends."
  "name": "Possession (Recharge 6)"
- "desc": "Leedara magically assumes the appearance she had in life, and her creature\
    \ type changes to Humanoid, while retaining her other game statistics. This transformation\
    \ ends if Leedara is reduced to 0 hit points or uses an action to end it."
  "name": "Change Shape"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Leedara.webp"
```
^statblock