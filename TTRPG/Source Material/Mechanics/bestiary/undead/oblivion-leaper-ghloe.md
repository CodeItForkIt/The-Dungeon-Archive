---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1
- monster/size/small
- monster/type/undead
statblock: inline
aliases: ["Oblivion Leaper"]
---
# [Oblivion Leaper](Mechanics\bestiary\undead/oblivion-leaper-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 27*  

> [!quote]  
> 
> If you hear the strange, low whistling in the darkness, run! They whistle before they strike, striding out of the darkness, hungry for the souls of the living.

## Salvage

There is a 25% chance that an oblivion stalker leaves behind a gemstone when it is defeated. These stones are worth between 10 and 500 gp, depending on the size of the creature. There is a 10% chance that one of these stones acts as a magnet to additional oblivion stalkers, which appear and attack the holder of the gem at midnight during a new moon. A remove curse makes the gemstone safe.

## Lore

- **DC 10 Intelligence ([History](Mechanics/Rules/skills.md#History)).** An oblivion stalker is at disadvantage in daylight.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** An oblivion stalker is vulnerable to radiant damage and resistant to nonmagical weapons.  
- **DC 20 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** If an oblivion stalker kills a mortal, it's believed that mortal joins their shadowy ranks.  

> [!note] Customizing Oblivion Stalkers
> 
> Since oblivion stalkers can drain almost any living creature's energy, they can take just about any form. Some oblivion stalkers retain the natural abilities of their original form. For instance, an oblivion stalker that was once a wolf might retain the Pack Tactics trait. Similarly, a boar could possess a version of Charge, draining its prey while adding slashing damage and the possibility of knocking their victim prone.
> 
> Keep one special ability that makes sense for a creature of the stalker's former form without affecting the Challenge of the stalker. Avoid bestowing an oblivion stalker any ability that is magical, grants the stalker a ranged attack, or expands its resistances or immunities.
^customizing-oblivion-stalkers

```statblock
"name": "Oblivion Leaper (GHLoE)"
"size": "Small"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "14"
"hit_dice": "4d6"
"stats":
- !!int "10"
- !!int "16"
- !!int "11"
- !!int "10"
- !!int "10"
- !!int "8"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "5"
"damage_vulnerabilities": "radiant"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1"
"traits":
- "desc": "Starting in an area of dim light or darkness, an oblivion leaper can teleport\
    \ to an unoccupied space also in dim light or darkness. Every foot of teleportation\
    \ costs the oblivion leaper 1 foot of movement."
  "name": "Shadow Leap"
- "desc": "While in dim light or darkness, the oblivion leaper can take the Hide action\
    \ as a bonus action."
  "name": "Shadow Stealth"
- "desc": "While in sunlight, the oblivion leaper has disadvantage on attack rolls,\
    \ ability checks, and saving throws."
  "name": "Sunlight Weakness"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 7\
    \ (2d4 + 3) necrotic damage, and the target must make a DC 11 Constitution saving\
    \ throw. On a failure, the target's available Hit Dice are reduced by 1. If this\
    \ effect reduces the target's Hit Dice to 0, the target falls [unconscious](Mechanics/Rules/conditions.md#Unconscious).\
    \ The target can repeat the saving throw at the end of each of its turns, regaining\
    \ consciousness on a success. Hit Dice lost this way return at the end of a short\
    \ rest, in time to spend them to regain hit points.\n\nIf an oblivion leaper kills\
    \ a living creature with this attack when the creature is at 0 Hit Dice, the target's\
    \ soul is lost to the realm of shadow. This lost soul can be raised from the dead\
    \ only with mighty magic, such as wish or divine intervention."
  "name": "Soul Drain"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Oblivion%20Leaper.webp"
```
^statblock