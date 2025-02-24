---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/2
- monster/environment/desert
- monster/size/medium
- monster/type/elemental
statblock: inline
aliases: ["Anubian"]
---
# [Anubian](Mechanics\bestiary\elemental/anubian-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 23*  

*Swirling sand comes together to form a snarling, canine-faced humanoid whose eyes shine with an eerie, blue glow.*

Anubians are elementals summoned to guard tombs or protect treasures.

## Piles of Dust

An anubian at rest resembles a pile of sand or dust, often strewn about an already dusty location. When active, it rises up to form a muscular humanoid with the head of a jackal. A destroyed anubian collapses into an inert pile of sand.

## Death to the Unarmored

In combat, anubians prefer to fight unarmored foes rather than creatures wearing armor. They associate unarmored creatures with spellcasters, and their latent resentment over centuries of being summoned as servants drives them to attack such figures when they aren't shackled by magical bondage.

## Sandstorm Tag Teams

Anubians fight effectively as teams, using their haboob attacks to corner and isolate the most vulnerable targets.

```statblock
"name": "Anubian (ToB1-2023)"
"size": "Medium"
"type": "elemental"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "12"
- !!int "16"
- !!int "12"
- !!int "10"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "5"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., tremorsense 30 ft., passive Perception 11"
"languages": "Primordial"
"cr": "2"
"traits":
- "desc": "The anubian doesn't require air, food, drink, or sleep."
  "name": "Elemental Nature"
- "desc": "The anubian has advantage on Dexterity ([Stealth](Mechanics/Rules/skills.md#Stealth))\
    \ checks made to hide in sandy terrain."
  "name": "Sand Camouflage"
- "desc": "The anubian can enter a hostile creature's space and stop there. It can\
    \ move through a space as narrow as 1 inch wide without squeezing."
  "name": "Sand Form"
- "desc": "For every 5 feet the anubian moves in water, or for every gallon of water\
    \ splashed on it, it takes 2 (1d4) cold damage. An anubian completely immersed\
    \ in water takes 10 (4d4) cold damage at the start of its turn."
  "name": "Vulnerability to Water"
"actions":
- "desc": "The anubian makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Claw"
- "desc": "A 30-foot-tall cylinder of sand forms in the anubian's space and moves\
    \ with it for 10 minutes, until the anubian ends the storm as a bonus action,\
    \ or until its [concentration](Mechanics/Rules/conditions.md#Concentration) ends\
    \ (as if concentrating on a spell). The area within 5 feet of the anubian is heavily\
    \ obscured. A creature that starts its turn in that area or enters the area for\
    \ the first time on a turn must succeed on a DC 13 Strength saving throw or be\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained) by the storm. While [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ the creature takes 3 (1d6) slashing damage at the start of each of its turns,\
    \ and moves with the anubian when the anubian moves. A creature, including the\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained) creature, can use its\
    \ action to free the [restrained](Mechanics/Rules/conditions.md#Restrained) creature\
    \ by succeeding on a DC 13 Strength check."
  "name": "Haboob (1/Day)"
"bonus_actions":
- "desc": "The anubian collapses into loose sand and teleports up to 30 feet to an\
    \ unoccupied space it can see, reforming in that space. If the destination space\
    \ contains sand, the anubian can immediately Hide. The anubian can't use Sand\
    \ Step while Haboob is active."
  "name": "Sand Step"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Anubian.webp"
```
^statblock

## Environment

desert