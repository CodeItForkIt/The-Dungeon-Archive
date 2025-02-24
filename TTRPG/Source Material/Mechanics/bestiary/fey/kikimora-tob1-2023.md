---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/urban
- monster/size/medium
- monster/type/fey
statblock: inline
aliases: ["Kikimora"]
---
# [Kikimora](Mechanics\bestiary\fey/kikimora-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 243*  

*This strange-looking humanoid combines the features of an old crone and some manner of bird. A shawl covers her head but cannot contain her prominent beak and clawed hands. Her skirt reveals bird-like feet*.

## Filthy Illusions

Kikimoras are devious house spirits who torment those in their domain. They delight in harassing homeowners with their illusions, making a house look much filthier than it actually is. Their favored illusions include mold, filth, and scuttling vermin. They love secretly breaking things and making destruction seem like an accident. They then convince the house's residents to leave gifts as enticement for making repairs in the night.

## Brownie Hunters

Kikimoras hate brownies (see*Tome of Beasts 3*). While brownies can be mischievous, kikimoras bring pain and frustration on their housemates instead of remaining hidden and helping chores along. Some brownies seek out kikimora-infested homes with the intention of evicting them.

## Pest Control

If homeowners refuse to appease the kikimora (or cannot rid themselves of its devious presence), the kikimora sends a swarm of spiders, rats, or bats to torment the inhabitants. Inhabitants in a home plagued by a kikimora often believe it is haunted.

```statblock
"name": "Kikimora (ToB1-2023)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "13"
- !!int "18"
- !!int "15"
- !!int "12"
- !!int "16"
- !!int "21"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "8"
  "Stealth": !!int "7"
  "Persuasion": !!int "8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Sylvan"
"cr": "5"
"traits":
- "desc": "The kikimora can spend 1 minute scribing a magical symbol on a wall, baseboard,\
    \ cupboard, or other semi‑permanent object within a structure. The symbol remains\
    \ until the kikimora inscribes another symbol elsewhere. While within 5 feet of\
    \ the surface where the symbol is inscribed, the kikimora can use an action to\
    \ touch the symbol and be transported to an extradimensional space just large\
    \ enough to hold the kikimora and up to 50 pounds of nonmagical objects. Only\
    \ the kikimora can enter this space, along with any nonmagical objects it is wearing\
    \ or carrying, up to the extradimensional space's limits. While inside the extradimensional\
    \ space, the kikimora can see out as if through a 2-foot-by-2-foot window centered\
    \ on the symbol and can exit the space as an action, appearing in an unoccupied\
    \ space within 10 feet of the surface where the symbol is inscribed.\n\nIf the\
    \ kikimora is killed or if it creates a second symbol while objects remain within\
    \ the extradimensional space, the objects are safely ejected to an unoccupied\
    \ space nearest the surface where the first symbol was inscribed."
  "name": "Hidden Home"
- "desc": "The kikimora has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The kikimora makes three Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claw"
- "desc": "The kikimora can cast the [mending](Mechanics/spells/mending.md), minor\
    \ illusion, and [prestidigitation](Mechanics/spells/prestidigitation.md) cantrips\
    \ at will, requiring no material components and using Charisma as the spellcasting\
    \ ability."
  "name": "Domestic Magic"
- "desc": "The kikimora magically turns [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ until it attacks or casts a spell, or until its [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ ends (as if concentrating on a spell). Any equipment the kikimora wears or carries\
    \ is [invisible](Mechanics/Rules/conditions.md#Invisible) with it."
  "name": "Invisibility"
- "desc": "The kikimora magically calls 1 swarm of bats, insects, or rats. The called\
    \ creatures arrive in 1d4 rounds, acting as allies of the kikimora and obeying\
    \ its spoken commands. The Beasts remain for 1 hour, until the kikimora dies,\
    \ or until the kikimora dismisses them as a bonus action."
  "name": "House Pests (1/Day)"
"bonus_actions":
- "desc": "While within a structure containing its hidden home (see the Hidden Home\
    \ trait), the kikimora magically teleports, along with any equipment it is wearing\
    \ or carrying, to an unoccupied space within 15 feet of the hidden home's symbol."
  "name": "Homeward Step"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Kikimora.webp"
```
^statblock

## Environment

urban