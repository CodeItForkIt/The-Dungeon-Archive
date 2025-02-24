---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/0
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Living Demiplane"]
---
# [Living Demiplane](Mechanics\bestiary\construct/living-demiplane-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 299*  

A living demiplane is a [demiplane](Mechanics/spells/demiplane.md) spell that has become vaguely self-aware. It is a shadowy rectangle, 5 feet wide and 10 feet high, which creeps along flat, solid surfaces and groans softly when it moves.

When a living demiplane encounters a creature small enough to fit through its doorway, it tries to pull that creature into itself, then deposits the victim in an extradimensional chamber.

Areas of wild magic and sites that have been ravaged by powerful eldritch forces can give rise to spell effects that become living beings. These so-called living spells haunt the places where they were created, subsisting on ambient magical energy.

```statblock
"name": "Living Demiplane (IDRotF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "31"
"hit_dice": "7d8"
"stats":
- !!int "1"
- !!int "10"
- !!int "10"
- !!int "1"
- !!int "10"
- !!int "1"
"speed": "30 ft., climb 30 ft."
"damage_immunities": "poison"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [deafened](Mechanics/Rules/conditions.md#Deafened), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [grappled](Mechanics/Rules/conditions.md#Grappled),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone),\
  \ [restrained](Mechanics/Rules/conditions.md#Restrained), [stunned](Mechanics/Rules/conditions.md#Stunned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "0"
"traits":
- "desc": "The living spell can enter another creature's space and vice versa, and\
    \ it can move through a space as narrow as 1 inch wide without squeezing. The\
    \ living spell can't detach from a solid surface, such as a wall, ceiling, or\
    \ floor. If it has no surface to attach to, the living spell is destroyed (see\
    \ \"Planar Destruction\" below)."
  "name": "Dimensional Form"
- "desc": "When the living spell enters another creature's space (or vice versa) for\
    \ the first time on a turn, the other creature must succeed on a DC 10 Dexterity\
    \ saving throw or be pulled into the living spell's extradimensional space, an\
    \ unfurnished stone chamber 30 feet in every dimension. A creature too big to\
    \ fit in this space succeeds on the saving throw automatically. Creatures in the\
    \ chamber never run out of breathable air. Magic that enables transit between\
    \ planes, such as plane shift, can be used to escape the chamber, which has no\
    \ exits otherwise. Creatures trapped inside the extradimensional chamber can't\
    \ see, target, or deal damage to the living spell; however, they can damage the\
    \ room around them. Each 5-foot-square section of ceiling, wall, and floor in\
    \ the chamber has AC 17, 50 hit points, immunity to poison and psychic damage,\
    \ and immunity to bludgeoning, piercing, and slashing damage that is nonmagical.\
    \ If any section is reduced to 0 hit points, the living spell and its chamber\
    \ are destroyed (see \"Planar Destruction\" below)."
  "name": "Extradimensional Chamber"
- "desc": "The living spell has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "The living spell is destroyed when it or a 5-foot-square section of its\
    \ extradimensional chamber is reduced to 0 hit points, or when the living spell\
    \ has no surface to attach to. When the living spell is destroyed, the contents\
    \ of its extradimensional chamber are expelled, appearing as close to the living\
    \ spell's previous location as possible. Each expelled creature appears in a randomly\
    \ determined unoccupied space, along with whatever it is wearing or carrying."
  "name": "Planar Destruction"
- "desc": "The living spell doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Living%20Demiplane.webp"
```
^statblock