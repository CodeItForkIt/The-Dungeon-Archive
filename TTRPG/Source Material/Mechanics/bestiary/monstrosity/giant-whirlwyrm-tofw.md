---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
statblock: inline
aliases: ["Giant Whirlwyrm"]
---
# [Giant Whirlwyrm](Mechanics\bestiary\monstrosity/giant-whirlwyrm-tofw.md)
*Source: Turn of Fortune's Wheel p. 55*  

```statblock
"name": "Giant Whirlwyrm (ToFW)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d12 + 64"
"stats":
- !!int "23"
- !!int "16"
- !!int "18"
- !!int "7"
- !!int "14"
- !!int "12"
"speed": "50 ft., swim 60 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "6"
"damage_immunities": "lightning"
"senses": "darkvision 90 ft., passive Perception 16"
"languages": "Draconic"
"cr": "11"
"actions":
- "desc": "The whirlwyrm makes two attacks: one with its bite and one to constrict."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d10 + 6) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one Large or smaller\
    \ creature. Hit: 17 (2d10 + 6) bludgeoning damage plus 17 (2d10 + 6) slashing\
    \ damage. The target is [grappled](Mechanics/Rules/conditions.md#Grappled) (escape\
    \ DC 16) if the whirlwyrm isn't already constricting a creature, and the target\
    \ is [restrained](Mechanics/Rules/conditions.md#Restrained) until this grapple\
    \ ends."
  "name": "Constrict"
- "desc": "The whirlwyrm exhales a line of thunder that is 20 feet long and 5 feet\
    \ wide. Each creature in that line must make a DC 16 Dexterity saving throw, taking\
    \ 66 (12d10) thunder damage on a failed save, or half as much damage on a successful\
    \ one."
  "name": "Thunder Breath (Recharge 5-6)"
- "desc": "The whirlwyrm makes one bite attack against a Medium or smaller target\
    \ it is grappling. If the attack hits, the target is also swallowed, and the grapple\
    \ ends. While swallowed, the target is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ and [restrained](Mechanics/Rules/conditions.md#Restrained), it has total cover\
    \ against attacks and other effects outside the whirlwyrm, and it takes 21 (6d6)\
    \ acid damage at the start of each of the whirlwyrm's turns. A whirlwyrm can have\
    \ only one creature swallowed at a time.\n\nIf the whirlwyrm takes 30 damage or\
    \ more on a single turn from the swallowed creature, the whirlwyrm must succeed\
    \ on a DC 14 Constitution saving throw at the end of that turn or regurgitate\
    \ the creature, which falls [prone](Mechanics/Rules/conditions.md#Prone) in a\
    \ space within 10 feet of the whirlwyrm. If the whirlwyrm dies, a swallowed creature\
    \ is no longer [restrained](Mechanics/Rules/conditions.md#Restrained) by it and\
    \ can escape from the corpse by using 15 feet of movement, exiting [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Swallow"
"source":
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/Giant%20Whirlwyrm.webp"
```
^statblock