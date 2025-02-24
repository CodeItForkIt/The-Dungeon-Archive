---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/4
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Spirit"]
---
# [Spirit](Mechanics\bestiary\undead/spirit-psz.md)
*Source: Plane Shift: Zendikar p. 28*  

Magic fueled by black mana can alter the natural cycle of life and death. Whether wielded by mortal wizards or demons, or simply an environmental manifestation of black mana's flow through the land, such magic can trap spirits between the realm of the living and the mysterious fate of the dead. These ghostly undead are as destructive and hateful as the magic that calls them into being. Zendikar's shades and wraiths can be represented by the [shadows](Mechanics/bestiary/undead/shadow.md) and [wraiths](Mechanics/bestiary/undead/wraith.md) in the Monster Manual.

Not all spirits are created with black mana, however, and not all are malevolent. The spirits of the dead sometimes linger in the world to protect their kin or communities, or to stand guard over sacred or important sites. These spirits can be dangerous, but they are not usually malicious. Both the kor and the Mul Daya elves remain in communion with the spirits of their dead kindred, entreating them for wisdom and protection. Such spirits are best described as the [ghosts](Mechanics/bestiary/undead/ghost.md) in the Monster Manual.

```statblock
"name": "Spirit (PSZ)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
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
"speed": "0 ft., fly 40 ft. (hover)"
"damage_resistances": "acid; fire; lightning; thunder; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "cold, necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "any languages it knew in life"
"cr": "4"
"traits":
- "desc": "The spirit can see 60 feet into the Ethereal Plane when it is on the Material\
    \ Plane, and vice versa."
  "name": "Ethereal Sight"
- "desc": "The spirit can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 17\
    \ (4d6 + 3) necrotic damage."
  "name": "Withering Touch"
- "desc": "The spirit enters the Ethereal Plane from the Material Plane, or vice versa.\
    \ It is visible on the Material Plane while it is in the Border Ethereal, and\
    \ vice versa, yet it can't affect or be affected by anything on the other plane."
  "name": "Etherealness"
- "desc": "Each non-undead creature within 60 feet of the spirit that can see it must\
    \ succeed on a DC 13 Wisdom saving throw or be [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. If the save fails by 5 or more, the target also ages 1d4 × 10\
    \ years. A [frightened](Mechanics/Rules/conditions.md#Frightened) target can repeat\
    \ the saving throw at the end of each of its turns, ending the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition on itself on a success. If a target's saving throw is successful or\
    \ the effect ends for it, the target is immune to this spirit's Horrifying Visage\
    \ for the next 24 hours. The aging effect can be reversed with a  [greater restoration](Mechanics/spells/greater-restoration.md)\
    \ spell, but only within 24 hours of it occurring."
  "name": "Horrifying Visage"
- "desc": "One humanoid that the spirit can see within 5 feet of it must succeed on\
    \ a DC 13 Charisma saving throw or be possessed by the spirit; the spirit then\
    \ disappears, and the target is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ and loses control of its body. The spirit now controls the body but doesn't\
    \ deprive the target of awareness. The spirit can't be targeted by any attack,\
    \ spell, or other effect, except ones that turn undead, and it retains its alignment,\
    \ Intelligence, Wisdom, Charisma, and immunity to being [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ and [frightened](Mechanics/Rules/conditions.md#Frightened). It otherwise uses\
    \ the possessed target's statistics, but doesn't gain access to the target's knowledge,\
    \ class features, or proficiencies.\n\nThe possession lasts until the body drops\
    \ to 0 hit points, the spirit ends it as a bonus action, or the spirit is turned\
    \ or forced out by an effect like the [dispel evil and good](Mechanics/spells/dispel-evil-and-good.md)\
    \ spell. When the possession ends, the spirit reappears in an unoccupied space\
    \ within 5 feet of the body. The target is immune to this spirit's Possession\
    \ for 24 hours after succeeding on the saving throw or after the possession ends."
  "name": "Possession (Recharge 6)"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Spirit.webp"
```
^statblock