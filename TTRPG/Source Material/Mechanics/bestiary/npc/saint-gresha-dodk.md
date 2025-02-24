---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/6
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Saint Gresha"]
---
# [Saint Gresha](Mechanics\bestiary\npc/saint-gresha-dodk.md)
*Source: Dungeons of Drakkenheim p. 124*  

Gresha was called back in spirit by Lucretia Mathias to tend her namesake chapel. If Saint Gresha is destroyed, Lucretia Mathias calls her spirit back again as soon as possible.

```statblock
"name": "Saint Gresha (DoDk)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Good"
"ac": !!int "13"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "6"
- !!int "16"
- !!int "16"
- !!int "12"
- !!int "14"
- !!int "15"
"speed": "0 ft., fly 60 ft."
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks that aren't silvered"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [grappled](Mechanics/Rules/conditions.md#Grappled), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [restrained](Mechanics/Rules/conditions.md#Restrained)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "The languages it knew in life"
"cr": "6"
"traits":
- "desc": "Saint Gresha is an 8th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 13, +5 to hit with spell attacks). Saint Gresha knows the following\
    \ sorcerer spells:\n\nAt will: [guidance](Mechanics/spells/guidance.md), [light](Mechanics/spells/light.md),\
    \ [sacred flame](Mechanics/spells/sacred-flame.md), [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\
    \n1/day each: [divine word](Mechanics/spells/divine-word.md), [harm](Mechanics/spells/harm.md),\
    \ [heal](Mechanics/spells/heal.md), [holy aura](Mechanics/spells/holy-aura.md),\
    \ [sacrament of the falling fire](Mechanics/spells/sacrament-of-the-falling-fire-dodk.md)\n\
    \n3/day each: [bless](Mechanics/spells/bless.md), [flame strike](Mechanics/spells/flame-strike.md),\
    \ [guiding bolt](Mechanics/spells/guiding-bolt.md), [healing word](Mechanics/spells/healing-word.md),\
    \ [prayer of healing](Mechanics/spells/prayer-of-healing.md), [spirit guardians](Mechanics/spells/spirit-guardians.md)\n\
    \nnew spell described in Appendix D of Dungeons of Drakkenheim."
  "name": "Spellcasting"
- "desc": "Saint Gresha can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "While in sunlight, Saint Gresha has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception)) checks that\
    \ rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 21\
    \ (4d8 + 3) necrotic damage. The target must succeed on a DC 14 Constitution\
    \ saving throw or its hit point maximum is reduced by an amount equal to the damage\
    \ taken. This reduction lasts until the target finishes a long rest. The target\
    \ dies if this effect reduces its hit point maximum to 0."
  "name": "Life Drain"
- "desc": "Saint Gresha targets a humanoid within 10 feet of it that has been dead\
    \ for no longer than 1 minute and died violently. The target's spirit rises as\
    \ a specter in the space of its corpse or in the nearest unoccupied space. The\
    \ specter is under Saint Gresha's control. Saint Gresha can have no more than\
    \ seven specters under its control at one time."
  "name": "Create Specter"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Saint%20Gresha.webp"
```
^statblock