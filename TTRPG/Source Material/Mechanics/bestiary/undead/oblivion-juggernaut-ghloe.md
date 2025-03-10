---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/8
- monster/size/huge
- monster/type/undead
statblock: inline
aliases: ["Oblivion Juggernaut"]
---
# [Oblivion Juggernaut](Mechanics\bestiary\undead/oblivion-juggernaut-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 28*  

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
"name": "Oblivion Juggernaut (GHLoE)"
"size": "Huge"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "85"
"hit_dice": "10d12 + 20"
"stats":
- !!int "18"
- !!int "14"
- !!int "15"
- !!int "10"
- !!int "10"
- !!int "8"
"speed": "40 ft."
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
"cr": "8"
"traits":
- "desc": "While in dim light or darkness, the oblivion juggernaut can take the Hide\
    \ action as a bonus action."
  "name": "Shadow Stealth"
- "desc": "While in sunlight, the oblivion juggernaut has disadvantage on attack rolls,\
    \ ability checks, and saving throws."
  "name": "Sunlight Weakness"
"actions":
- "desc": "The oblivion juggernaut uses unbearable roar and then uses soul drain."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 26\
    \ (4d10 + 4) necrotic damage, and the target must make a DC 13 Constitution\
    \ saving throw. On a failure, the target's available Hit Dice are reduced by 2.\
    \ If this effect reduces the target's Hit Dice to 0, the target falls [unconscious](Mechanics/Rules/conditions.md#Unconscious).\
    \ The target can repeat the saving throw at the end of each of its turns, regaining\
    \ consciousness on a success. Hit Dice lost this way return at the end of a short\
    \ rest, in time to spend them to regain hit points.\n\nIf an oblivion juggernaut\
    \ kills a living creature with this attack when the creature is at 0 Hit Dice,\
    \ the target's soul is lost to the realm of shadow. This lost soul can be raised\
    \ from the dead only with mighty magic, such as wish or divine intervention."
  "name": "Soul Drain"
- "desc": "Each creature of the oblivion juggernaut's choice that isn't [deafened](Mechanics/Rules/conditions.md#Deafened)\
    \ and is within 120 feet of the juggernaut must succeed on a DC 18 Wisdom saving\
    \ throw or become [frightened](Mechanics/Rules/conditions.md#Frightened) for 1\
    \ minute. A creature can repeat the saving throw at the end of each of its turns,\
    \ ending the effect on itself on a success. If a creature's saving throw is successful\
    \ or the effect ends for it, the creature is immune to any oblivion juggernaut's\
    \ Unbearable Roar for 24 hours."
  "name": "Unbearable Roar"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Oblivion%20Juggernaut.webp"
```
^statblock