---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/12
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Stone Juggernaut"]
---
# [Stone Juggernaut](Mechanics\bestiary\construct/stone-juggernaut-toa.md)
*Source: Tomb of Annihilation p. 231*  

A stone juggernaut is a rolling construct imbued with enough awareness to avoid obvious dangers such as open pits and chasms. It trundles across open battlefields or rolls down dungeon corridors, crushing anyone in its path. Every stone juggernaut has a unique shape and appearance. One might resemble an elephant with bejeweled tusks, while another might look like a scowling demon with flaming eyes and obsidian teeth.

A stone juggernaut is fast, but it lacks maneuverability and can move in only one direction on its turn. It poses little danger to creatures it can't crush beneath its rollers. Its best tactic is to slam into a creature, knock it [prone](Mechanics/Rules/conditions.md#Prone), and then roll over it.

```statblock
"name": "Stone Juggernaut (ToA)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "157"
"hit_dice": "15d10 + 75"
"stats":
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "14"
- !!int "14"
- !!int "16"
"speed": "50 ft. (in one direction chosen at the start of its turn)"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks\
  \ not made with adamantine weapons"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [deafened](Mechanics/Rules/conditions.md#Deafened), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone)"
"senses": "blindsight 120 ft., passive Perception 10"
"languages": ""
"cr": "12"
"traits":
- "desc": "The juggernaut can move through the space of a [prone](Mechanics/Rules/conditions.md#Prone)\
    \ creature. A creature whose space the juggernaut enters for the first time on\
    \ a turn must make a DC 17 Dexterity saving throw, taking 55 (10d10) bludgeoning\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Devastating Roll"
- "desc": "The juggernaut is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "As long as it has 1 hit point left, the juggernaut magically regains all\
    \ its hit points daily at dawn. The juggernaut is destroyed and doesn't regenerate\
    \ if it drops to 0 hit points."
  "name": "Regeneration"
- "desc": "The juggernaut deals double damage to objects and structures."
  "name": "Siege Monster"
"actions":
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 25\
    \ (3d12 + 6) bludgeoning damage. If the target is a Large or smaller creature,\
    \ it must succeed on a DC 17 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Slam"
"source":
- "ToA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Stone%20Juggernaut.webp"
```
^statblock