---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/1-4
- monster/size/small
- monster/type/plant
statblock: inline
aliases: ["Thornlamm"]
---
# [Thornlamm](Mechanics\bestiary\plant/thornlamm-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 90*  

> [!quote]  
> 
> The temptation to aid a lost lamb should be tamped down when a thornlamm appears. Where there is one, there are many. And all lead back to a creature far more terrifying than any big, bad wolf.

## Salvage

The sphere of annihilation a caprathorn leaves behind can be controlled and taken. At the start of each day there is a 2% chance the sphere disappears forever.

## Lore

- **DC 10 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** A caprathorn can detach a thornlamm to fight as its ally or consume one to heal.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** The caprathorn can entomb a fallen foe and unleash a field of disintegrating force. This annihilation field recharges if a creature the caprathorn has entombed dies.  
- **DC 20 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** When a caprathorn dies, it implodes into a sphere of annihilation, which pulls nearby creatures toward it.  

```statblock
"name": "Thornlamm (GHLoE)"
"size": "Small"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "21"
"hit_dice": "6d6"
"stats":
- !!int "11"
- !!int "14"
- !!int "11"
- !!int "3"
- !!int "8"
- !!int "3"
"speed": "30 ft."
"damage_resistances": "cold, fire, lightning, poison"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened),\
  \ [exhaustion](Mechanics/Rules/conditions.md#Exhaustion)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 9"
"languages": ""
"cr": "1/4"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4\
    \ + 2) bludgeoning damage."
  "name": "Hooves"
- "desc": "Ranged Weapon Attack: +4 to hit, range 30/60 ft., one target. Hit:\
    \ 7 (2d4 + 2) piercing damage."
  "name": "Needles"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Thornlamm.webp"
```
^statblock