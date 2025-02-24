---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/3
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Flitterstep Eidolon"]
---
# [Flitterstep Eidolon](Mechanics\bestiary\undead/flitterstep-eidolon-mot.md)
*Source: Mythic Odysseys of Theros p. 222*  

When a mortal soul traumatically sacrifices its identity in order to escape the Underworld as a Returned, its identity manifests as a spirit-like eidolon. While eidolons possess many of the skills and details related to their past lives, they're disconnected from those experiences, choosing to wander the world or brood in haunts they're drawn to in death. They care nothing for morbid reunions with their lost bodies or Returned remnants.

Of the various types of eidolons, flitterstep eidolons are the most common and wander without purpose.

```statblock
"name": "Flitterstep Eidolon (MOT)"
"size": "Medium"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"stats":
- !!int "8"
- !!int "18"
- !!int "13"
- !!int "11"
- !!int "12"
- !!int "10"
"speed": "40 ft."
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "3"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "passive Perception 13"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
- "desc": "Attack rolls against the eidolon are made with disadvantage unless the\
    \ eidolon is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Blurred Form"
- "desc": "If the eidolon is subjected to an effect that allows it to make a Dexterity\
    \ saving throw to take only half damage, the eidolon instead takes no damage if\
    \ it succeeds on the saving throw, and only half damage if it fails. It can't\
    \ use this trait if it's [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Evasion"
- "desc": "The eidolon can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "The eidolon has advantage on saving throws against any effect that turns\
    \ undead."
  "name": "Turn Resistance"
"actions":
- "desc": "The eidolon makes two melee attacks. Immediately before or after one of\
    \ its attacks, it can use Flitterstep if it is available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4\
    \ + 4) piercing damage plus 3 (1d6) psychic damage."
  "name": "Flickering Dagger"
- "desc": "The eidolon magically teleports to an unoccupied space it can see within\
    \ 30 feet of it. If it makes an attack immediately after teleporting, it has advantage\
    \ on the attack roll."
  "name": "Flitterstep (Recharge 5-6)"
"source":
- "MOT"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Flitterstep%20Eidolon.webp"
```
^statblock