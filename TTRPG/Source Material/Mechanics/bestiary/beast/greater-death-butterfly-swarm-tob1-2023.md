---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/farmland
- monster/environment/forest
- monster/environment/urban
- monster/size/huge
- monster/type/beast
statblock: inline
aliases: ["Greater Death Butterfly Swarm"]
---
# [Greater Death Butterfly Swarm](Mechanics\bestiary\beast/greater-death-butterfly-swarm-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 70*  

*Enormous clouds of orange and green butterflies add a reek of putrefaction to the air, stirred by the flapping of delicate wings.*

## Demon-Haunted

A death butterfly swarm results when a rare breed of carrion-eating butterfly, drawn en masse to the stench of decay, feeds on the corpse of a fiend, demon, or similar creature.

## Dizzying and Poisonous

The colorful, chaotic flapping of the insects' wings blinds and staggers those in its path, allowing the swarm to necrotize flesh from those it overruns. Attracted to rotting material, the swarm spreads a fast-acting, poison on its victims, creating carrion it can feed on immediately.

## Devour the Undead

Undead creatures are not immune to a death butterfly swarm's poison. A swarm can rot an undead creature's animating energies as easily as those of the living. Given the choice between an undead and living creature, a death butterfly swarm always attacks the undead, finding ghouls and vampires particularly appealing. Some good-aligned forces regard summoning these swarms as a necessary evil.

```statblock
"name": "Greater Death Butterfly Swarm (ToB1-2023)"
"size": "Huge"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "84"
"hit_dice": "13d12"
"stats":
- !!int "1"
- !!int "18"
- !!int "10"
- !!int "1"
- !!int "15"
- !!int "12"
"speed": "5 ft., fly 40 ft. (hover)"
"damage_vulnerabilities": "cold, fire"
"damage_resistances": "bludgeoning, piercing, slashing"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [restrained](Mechanics/Rules/conditions.md#Restrained),\
  \ [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": ""
"cr": "6"
"traits":
- "desc": "Undead with resistance or immunity to poison damage or the [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ condition can be affected by the swarm's poison."
  "name": "Potent Poison"
- "desc": "The swarm can occupy another creature's space and vice versa, and the swarm\
    \ can move through any opening large enough for a Tiny insect. The swarm can't\
    \ regain hp or gain temporary hp."
  "name": "Swarm"
- "desc": "A creature that starts its turn in the swarm's space has its speed halved\
    \ and must succeed on a DC 15 Dexterity saving throw or become [blinded](Mechanics/Rules/conditions.md#Blinded).\
    \ Both effects end when the creature ends its turn outside the swarm's space.\
    \ On a successful saving throw, the creature is immune to the blinding effect\
    \ of Weight of Wings for the next 24 hours."
  "name": "Weight of Wings"
"actions":
- "desc": "The swarm makes two Bites attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 0 ft., one creature in the swarm's\
    \ space. Hit: 21 (6d6) piercing damage, or 10 (3d6) piercing damage if the\
    \ swarm has half of its hp or fewer. The target must make a DC 15 Constitution\
    \ saving throw. On a failure, it takes 10 (3d6) poison damage and is [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ for 1 minute. On a success, it takes half the damage and isn't [poisoned](Mechanics/Rules/conditions.md#Poisoned).\
    \ A [poisoned](Mechanics/Rules/conditions.md#Poisoned) creature can repeat the\
    \ saving throw at the end of each of its turns, ending the effect on itself on\
    \ a success."
  "name": "Bites"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Greater%20Death%20Butterfly%20Swarm.webp"
```
^statblock

## Environment

farmland, forest, urban