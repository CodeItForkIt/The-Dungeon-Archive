---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Eldritch Herald"]
---
# [Eldritch Herald](Mechanics\bestiary\humanoid/eldritch-herald-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 41*  

> [!quote]  
> 
> First she spoke of a power greater than the gods. Then there was this ringing in my ears. I don't remember what happened after that, but the nightmares were terrible.

## Salvage

The touch of an Aether Kindred's dreams can taint objects with an unstable nature, particularly potions. Any potion found on the servants of these beings has a 50 percent chance to be tainted, making the potion's effects unpredictable. Someone inspecting such a potion must succeed on a DC 17 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)) check to identify the instability. Otherwise, the potion appears to be a normal potion of its type.

When an unstable potion is consumed, roll on the Eldritch Effects table to determine the effect of the instability, which is in addition to the potion's normal effects and can last as long as the potion does or 1 minute, whichever is longer. However, a creature can attempt a DC 13 Wisdom saving throw at the end of each of its turns, ending the instability effect on itself on a success.

## Lore

- **DC 10 Intelligence ([History](Mechanics/Rules/skills.md#History)).** In the wake of the gods' disappearance, some turned to other ancient entities for power. Those that succeed are known as eldritch priests.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** These priests draw their power from maddening entities known as the Aether Kindred, which some arcane scholars point to as the cause of the gods' disappearance. The power granted by such creatures can produce bizarre and unpredictable effects.  
- **DC 20 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** Some eldritch priests seek to awaken their new "gods" by spreading the story of the demise of members the Etharis pantheon. As more people tap into the dreams of the slumbering Kindred, the creatures begin to rouse. If they wake, the world is doomed.  

## Eldritch Effects

`dice: [](eldritch-herald-ghloe.md#^effect)`

| dice: d8 | Effect |
|----------|--------|
| 1 | The creature can't speak. |
| 2 | The creature takes 4 (`1d8`) psychic damage at the start of each of its turns. |
| 3 | The creature is disoriented. It falls prone and does so again at the end of each turn it moves 5 feet or more. |
| 4 | The creature is distracted by visions and voices and has disadvantage on attack rolls and Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks. |
| 5 | The creature is unsure of itself. It can move or take an action on its turn, but not both, and it can't use reactions. |
| 6 | The creature is reckless. It has advantage on attack rolls and attack rolls against it have advantage. |
| 7 | The creature is deafened and can't see more than 30 feet away. |
| 8 | The creature is frightened of the source of this effect. If that source can't be sensed, the creature is frightened of one other random creature it can sense. |
^effect

```statblock
"name": "Eldritch Herald (GHLoE)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "16"
"ac_class": "[breastplate](Mechanics/items/breastplate.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "14"
- !!int "11"
- !!int "15"
- !!int "10"
- !!int "17"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Religion": !!int "3"
  "Perception": !!int "6"
"damage_resistances": "psychic"
"senses": "passive Perception 16"
"languages": "any two languages"
"cr": "5"
"traits":
- "desc": "The herald is a 12th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 14, +6 to hit with spell attacks). It has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [light](Mechanics/spells/light.md),\
    \ [sacred flame](Mechanics/spells/sacred-flame.md), [thaumaturgy](Mechanics/spells/thaumaturgy.md),\
    \ [vicious mockery](Mechanics/spells/vicious-mockery.md)\n\n1st level (4 slots):\
    \ [bane](Mechanics/spells/bane.md), [Tasha's hideous laughter](Mechanics/spells/tashas-hideous-laughter.md),\
    \ [inflict wounds](Mechanics/spells/inflict-wounds.md), [sleep](Mechanics/spells/sleep.md)\n\
    \n2nd level (3 slots): [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [hold person](Mechanics/spells/hold-person.md), [see invisibility](Mechanics/spells/see-invisibility.md),\
    \ [wrack](Mechanics/spells/wrack-ghloe.md) \n\n3rd level (3 slots): [bestow\
    \ curse](Mechanics/spells/bestow-curse.md), [fear](Mechanics/spells/fear.md),\
    \ [spirit guardians](Mechanics/spells/spirit-guardians.md), [tongues](Mechanics/spells/tongues.md)\n\
    \n4th level (3 slots): [confusion](Mechanics/spells/confusion.md), [death\
    \ ward](Mechanics/spells/death-ward.md), [phantasmal killer](Mechanics/spells/phantasmal-killer.md)\n\
    \n5th level (2 slots): [contact other plane](Mechanics/spells/contact-other-plane.md),\
    \ [contagion](Mechanics/spells/contagion.md), [dream](Mechanics/spells/dream.md)\n\
    \n6th level (1 slots): [true seeing](Mechanics/spells/true-seeing.md)"
  "name": "Spellcasting"
- "desc": "The eldritch herald has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ or [frightened](Mechanics/Rules/conditions.md#Frightened). Also, attempts to\
    \ read the herald's thoughts fail. The creature making the attempt must succeed\
    \ on a DC 14 Wisdom saving throw or take 10 (3d6) psychic damage."
  "name": "Otherworldly Calm"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit:* 5 (1d6\
    \ + 2) slashing damage."
  "name": "Handaxe"
- "desc": "The eldritch herald chooses a point it can see within 120 feet of it and\
    \ rolls on the Eldritch Effects table. Each creature within 15 feet of that point\
    \ must succeed on a DC 14 Wisdom saving throw or be subjected to an eldritch effect\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Prophecy of Doom (Recharges after a Short or Long Rest)"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Eldritch%20Herald.webp"
```
^statblock