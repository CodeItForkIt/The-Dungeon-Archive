---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/desert
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Accursed Defiler"]
---
# [Accursed Defiler](Mechanics\bestiary\undead/accursed-defiler-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 12*  

*A gaunt figure in a tattered black mantle shrouded in a cloud of whirling sand. Thin cracks run across its papyrus-dry skin and around its hollow, black eyes.*

## Cursed to Wander and Thirst

Accursed defilers are the remnants of an ancient tribe that desecrated a sacred oasis. For their crime, the wrathful spirits cursed the tribe to forever wander the wastes attempting to quench an insatiable thirst. Each defiler carries a parched sandstorm within its lungs and in the flowing sand in its veins. Wherever they roam, they leave only desiccated husks of their victims littering the sand.

## Unceasing Hatred

The desperate or foolish sometimes try to speak with these ill-fated creatures in their archaic native tongue, to learn their secrets or to bargain for their services. But a defiler's heart is blackened with hate and despair, leaving room for naught but woe.

## Servants to Great Evil

On rare occasions, accursed defilers serve evil high priests, fext, or soulsworn warlocks as bodyguards and zealous destroyers, eager to spread the withering desert's hand to new lands.

```statblock
"name": "Accursed Defiler (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"stats":
- !!int "19"
- !!int "14"
- !!int "17"
- !!int "6"
- !!int "15"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "4"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "understands an ancient language but can't speak"
"cr": "4"
"traits":
- "desc": "When it drops to 0 hp in desert terrain, the accursed defiler's body disintegrates\
    \ into sand and a parched breeze. However, unless it was killed in a hallowed\
    \ location, with radiant damage, or by a creature under the effects of the [bless](Mechanics/spells/bless.md)\
    \ spell, the accursed defiler reforms at the next sundown 1d100 miles away from\
    \ where it died in a random direction."
  "name": "Cursed Existence"
- "desc": "A miniature sandstorm constantly whirls around the accursed defiler in\
    \ a 10-foot radius. This area is lightly obscured to creatures other than the\
    \ accursed defiler. Wisdom ([Survival](Mechanics/Rules/skills.md#Survival)) checks\
    \ made to follow tracks left by the accursed defiler or other creatures that were\
    \ traveling in its sand shroud are made with disadvantage."
  "name": "Sand Shroud"
- "desc": "The accursed defiler doesn't require air, food, drink, or sleep."
  "name": "Undead Nature"
"actions":
- "desc": "The accursed defiler makes two Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 11\
    \ (2d6 + 4) bludgeoning damage. If the accursed defiler scores a critical hit,\
    \ the target suffers one level of [exhaustion](Mechanics/Rules/conditions.md#Exhaustion)."
  "name": "Slam"
- "desc": "The accursed defiler intensifies the vortex of sand that surrounds it.\
    \ Each creature within 10 feet of the accursed defiler must make a DC 14 Dexterity\
    \ saving throw, taking 21 (6d6) slashing damage on a failed save, or half as\
    \ much damage on a successful one."
  "name": "Sandslash (Recharge 5-6)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Accursed%20Defiler.webp"
```
^statblock

## Environment

desert