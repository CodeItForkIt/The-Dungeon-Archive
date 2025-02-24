---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/arctic
- monster/environment/underwater
- monster/size/large
- monster/type/dragon
statblock: inline
aliases: ["Lindwurm"]
---
# [Lindwurm](Mechanics\bestiary\dragon/lindwurm-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 255*  

*Coiling like a living corkscrew and moving with a scraping hiss, this serpentine creature skates nimbly across ice on long curving claws, maw agape and stinking of a hundred graves.*

## Swift and Smooth as Ice

Lindwurms have long bodies and crocodilian jaws, but they skitter overland on spindly limbs. Their talons are long and curved, acting as skates or short skis when moving over ice. Few things are swifter on the ice.

## Sea Hunters

In the wild, lindwurms hunt in groups, looking for breaching whales, seals, or incautious fishermen. They enjoy surrounding and surprising foes. With their considerable cunning, they may skate by their prey at speed, snapping a bite as they pass or snatching up prey with their constricting tails.

```statblock
"name": "Lindwurm (ToB1-2023)"
"size": "Large"
"type": "dragon"
"alignment": "Neutral Evil"
"ac": !!int "15"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "18"
- !!int "20"
- !!int "16"
- !!int "6"
- !!int "12"
- !!int "8"
"speed": "40 ft., swim 20 ft."
"saves":
  "Dexterity": !!int "8"
  "Strength": !!int "7"
  "Constitution": !!int "6"
"skillsaves":
  "Athletics": !!int "7"
  "Stealth": !!int "8"
  "Perception": !!int "4"
  "Acrobatics": !!int "8"
"damage_vulnerabilities": "fire"
"damage_immunities": "cold"
"condition_immunities": "[paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., tremorsense 120 ft., passive Perception 14"
"languages": "Draconic"
"cr": "6"
"traits":
- "desc": "The lindwurm can move across icy surfaces without needing to make an ability\
    \ check. Additionally, difficult terrain composed of ice or snow doesn't cost\
    \ it extra movement."
  "name": "Ice Walk"
- "desc": "While the lindwurm is on snow or ice, it has advantage on Strength and\
    \ Dexterity saving throws made against effects that would knock it [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Sure-Footed Skater"
"actions":
- "desc": "The lindwurm makes one Bite attack and two Claw attacks. It can replace\
    \ its Bite attack with one Constrict attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 16\
    \ (2d10 + 5) piercing damage. If the target is a creature, it must succeed on\
    \ a DC 15 Constitution saving throw or contract a disease and be [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ until the disease is cured. At the end of each long rest, the diseased creature\
    \ must repeat the saving throw. On a failure, the creature suffers one level of\
    \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion) and doesn't regain expended\
    \ Hit Dice from the rest. On a success, the creature's [exhaustion](Mechanics/Rules/conditions.md#Exhaustion)\
    \ level decreases by one, and it regains expended Hit Dice as normal from the\
    \ rest. If a successful saving throw reduces the diseased creature's level of\
    \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion) below 1, the creature\
    \ recovers from the disease, ending it."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d8 + 5) bludgeoning damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 15). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the lindwurm can't Constrict another target."
  "name": "Constrict"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Lindwurm.webp"
```
^statblock

## Environment

arctic, underwater