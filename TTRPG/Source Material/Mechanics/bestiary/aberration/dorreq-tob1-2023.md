---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/badlands
- monster/environment/planar
- monster/size/medium
- monster/type/aberration
statblock: inline
aliases: ["Dorreq"]
---
# [Dorreq](Mechanics\bestiary\aberration/dorreq-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 110*  

*These twitching balls of tentacles surround an inhuman face dominated by a squid-like beak.*

## Servants of the Void

The dorreq are servants to ancient horrors of the Void and realms beyond human understanding. They are guardians and sentries for such creatures, and they swarm and attack any creatures approaching too close to the elder aberrations they serve.

## Death from Above

Dorreq prefer to drop on their victims from above, pinning them with their many tentacles and biting them with their large, chitinous beaks.

> [!note] Dorreq of the Wasted West
> 
> Mages who study the Wasted West disagree whether the dorreq are something that slipped through with the Great Old Ones during the Mage Wars, or if they are creatures twisted and warped by the alien radiations of the Walkers. Regardless, they are most commonly found swarming on and around the enormous Walkers of the Wastes, tootling strange, alien harmonies through their beaks.
^dorreq-of-the-wasted-west

```statblock
"name": "Dorreq (ToB1-2023)"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "17d8 + 17"
"stats":
- !!int "19"
- !!int "19"
- !!int "13"
- !!int "11"
- !!int "8"
- !!int "10"
"speed": "20 ft., climb 15 ft."
"saves":
  "Dexterity": !!int "6"
"skillsaves":
  "Intimidation": !!int "2"
  "Stealth": !!int "8"
  "Perception": !!int "1"
"damage_resistances": "acid, cold, lightning"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Void Speech"
"cr": "4"
"traits":
- "desc": "The area around the dorreq is warped by its connection to the Void. A creature\
    \ that starts its turn within 20 feet of the dorreq must succeed on a DC 14 Strength\
    \ saving throw or its speed is halved until the start of its next turn."
  "name": "Void Warping"
"actions":
- "desc": "The dorreq makes one Bite attack and two Tentacles attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 8\
    \ (1d8 + 4) bludgeoning damage, and if the target is a Medium or smaller creature,\
    \ it is [grappled](Mechanics/Rules/conditions.md#Grappled) (escape DC 14) and\
    \ pulled up to 5 feet closer to the dorreq. Until this grapple ends, the target\
    \ is [restrained](Mechanics/Rules/conditions.md#Restrained). The dorreq can grapple\
    \ up to two creatures at a time."
  "name": "Tentacles"
- "desc": "The dorreq emits a barely audible, vibrating thrum laced with Void energy.\
    \ Each creature within 20 feet of the dorreq must make a DC 14 Constitution saving\
    \ throw, taking 10 (3d6) thunder damage and 10 (3d6) necrotic damage on a\
    \ failed save, or half as much damage on a successful one."
  "name": "Void Thrum (Recharge 5-6)"
"bonus_actions":
- "desc": "The dorreq teleports, along with any equipment it is wearing or carrying,\
    \ up to 30 feet to an unoccupied space it can see. The origin and destination\
    \ spaces must contain a stone or rocky surface, such as a cliff face or rocky\
    \ terrain."
  "name": "Stone Step"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dorreq.webp"
```
^statblock

## Environment

badlands, planar