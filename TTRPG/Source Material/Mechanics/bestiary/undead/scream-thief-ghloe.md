---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/3
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Scream Thief"]
---
# [Scream Thief](Mechanics\bestiary\undead/scream-thief-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 14*  

> [!quote]  
> 
> It appeared from the darkness: a faceless wraith whose outstretched arms sought purchase on my mortal frame. In desperation, I cried to my companions for aid, but my voice was silent. When it stole my words, I knew my doom was at hand.

## Salvage

The bones of a mortal transformed into a scream thief remain imbued with its undead aura. A skilled magic item crafter using 200 gp of magical regents, and spending at least 5 days of effort, can create a [wand of silence](Mechanics/items/wand-of-silence-ghloe.md) (see Appendix A of Lairs of Etharis) if they succeed on a DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)) check.

A spellcaster can capture a psychic fragment's essence before it dissipates after death. The spellcaster requires a container worth at least 100 gp. Anyone who succeeds on a DC 13 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)) check can capture a portion of the defeated psychic fragment. The container can store up to 10 hit die worth of undead essence for 8 hours before they dissipate.

As an action, a container holding this spiritual essence can be thrown up to 20 feet, shattering on impact. All creatures within 5 feet of the broken container must make a DC 12 Constitution saving throw. A failed saving throw results in `1d4` necrotic damage per hit die of essence stored, while a success deals half as much damage.

## Lore

- **DC 10 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** The scream thief is immune to necrotic and poison. The incorporeal nature of psychic fragments makes them resistant to nonmagical weapons.  
- **DC 15 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** The touch of a scream thief drains life that magic cannot heal; only time and rest can.  

A scream thief remains trapped in its place of death, often accompanied by spirit fragments of the creatures it has killed.

```statblock
"name": "Scream Thief (GHLoE)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "6"
- !!int "15"
- !!int "14"
- !!int "10"
- !!int "12"
- !!int "12"
"speed": "0 ft., fly 60 ft. (hover)"
"damage_resistances": "acid; cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [restrained](Mechanics/Rules/conditions.md#Restrained),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "languages it knew in life"
"cr": "3"
"traits":
- "desc": "The scream thief can move through other creatures and objects as if they\
    \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn\
    \ inside an object."
  "name": "Incorporeal Movement"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 18\
    \ (4d8) necrotic damage. The target must succeed on a DC 12 Constitution saving\
    \ throw or its hit point maximum is reduced by an amount equal to the damage taken.\
    \ This reduction lasts until the target finishes a long rest. The target dies\
    \ if this effect reduces its hit point maximum to 0."
  "name": "Life Drain"
- "desc": "The scream thief forces a humanoid within 30 feet of it to make a DC13\
    \ Wisdom saving throw. On a failure, the target takes 19 (3d12) psychic damage,\
    \ is [frightened](Mechanics/Rules/conditions.md#Frightened), and is unable to\
    \ vocalize a sound of any kind. The target may repeat the saving throw at the\
    \ end of its turns to end these effects. On a success the creature takes half\
    \ as much damage and is not [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ or silenced."
  "name": "Silence the Living (Recharge 5-6)"
"reactions":
- "desc": "The scream thief targets a creature that died from one of its attacks.\
    \ The target's spirit rises as 3 (1d6) psychic fragments in the space of its\
    \ corpse or in the nearest unoccupied space. The psychic fragments are under the\
    \ scream thief's control."
  "name": "Fragment the Spirit"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Scream%20Thief.webp"
```
^statblock