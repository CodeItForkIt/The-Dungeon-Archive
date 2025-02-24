---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/desert
- monster/environment/underdark
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Night Scorpion"]
---
# [Night Scorpion](Mechanics\bestiary\beast/night-scorpion-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 320*  

*These midnight-black scorpions have a bright-red stripe on their tails, signaling the crippling poison within.*

## Blinding Poison

This aptly named arachnid hunter blinds victims with a dose of its crippling poison. It feeds on whole camels when given the chance, but it more commonly devours goats, sheep, and people. It hunts by night, when its senses are most effective.

## Underdark Giants

The species is common in deep caves and underworld realms. They are eight feet long with a seven-foot tail and daggerlike stinger. They weigh up to 200 pounds.

## Valuable Venom

Night scorpion venom is highly prized and can command upwards of 400 gp per dose.

```statblock
"name": "Night Scorpion (ToB1-2023)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"stats":
- !!int "15"
- !!int "14"
- !!int "14"
- !!int "1"
- !!int "9"
- !!int "3"
"speed": "40 ft."
"senses": "blindsight 60 ft., passive Perception 9"
"languages": ""
"cr": "3"
"actions":
- "desc": "The scorpion makes two Claw attacks and one Sting attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 6\
    \ (1d8 + 2) bludgeoning damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 12). The scorpion has two claws, each of which can grapple only one\
    \ target."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 7\
    \ (1d10 + 2) piercing damage, and the target must make a DC 12 Constitution\
    \ saving throw. On a failure, the target takes 7 (2d6) poison damage and is\
    \ [blinded](Mechanics/Rules/conditions.md#Blinded) for 1 hour. On a success, a\
    \ creature takes half the damage and isn't [blinded](Mechanics/Rules/conditions.md#Blinded).\
    \ If the target fails the saving throw by 5 or more, it is also [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ for 1 minute, and it is [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ while [poisoned](Mechanics/Rules/conditions.md#Poisoned) in this way. A [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ creature can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success."
  "name": "Sting"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Night%20Scorpion.webp"
```
^statblock

## Environment

desert, underdark