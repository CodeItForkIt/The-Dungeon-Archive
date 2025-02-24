---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/farmland
- monster/environment/urban
- monster/size/large
- monster/type/dragon/shapechanger
statblock: inline
aliases: ["Naina"]
---
# [Naina](Mechanics\bestiary\dragon/naina-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 282*  

*This draconic creature is plumed and scaled in glittering, multicolored hues.*

## Dragons in Human Form

These minor dragons can take the shape of wise, old, human women. They retain full use of their sorcerous powers in their humanoid forms, and they can retain that form indefinitely.

## Difficult to Spot

A naina shapeshifted into human form is nearly impossible to spot as anything but human unless she makes a mistake that gives away her true nature. This seldom happens. Draconic roars, a flash of scales, a fondness for raw meat, and a flash of wrathful dragon breath are the most common tells.

## Hunted by Rumor

When rumors of a naina circulate, any woman who is a stranger may be persecuted, ostracized, or even tortured unless she can prove that she's entirely human.

```statblock
"name": "Naina (ToB1-2023)"
"size": "Large"
"type": "dragon"
"subtype": "shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "231"
"hit_dice": "22d10 + 110"
"stats":
- !!int "20"
- !!int "16"
- !!int "21"
- !!int "15"
- !!int "18"
- !!int "18"
"speed": "40 ft., fly 120 ft."
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "7"
  "Wisdom": !!int "8"
  "Constitution": !!int "9"
"skillsaves":
  "Deception": !!int "8"
  "Insight": !!int "8"
  "Perception": !!int "8"
  "Persuasion": !!int "8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "magic. the naina senses magic within 120 feet of her at will. this trait\
  \ otherwise works like the detect magic spell but isn't itself magical., passive\
  \ Perception 18"
"languages": "Common, Draconic, Sylvan"
"cr": "11"
"traits":
- "desc": "The naina casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ [charm person](Mechanics/spells/charm-person.md), [dancing lights](Mechanics/spells/dancing-lights.md),\
    \ [silent image](Mechanics/spells/silent-image.md)\n\n1/day each: [dimension\
    \ door](Mechanics/spells/dimension-door.md), [dominate person](Mechanics/spells/dominate-person.md)\n\
    \n3/day each: [dispel magic](Mechanics/spells/dispel-magic.md), [hypnotic\
    \ pattern](Mechanics/spells/hypnotic-pattern.md), [invisibility](Mechanics/spells/invisibility.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The naina makes one Bite attack and two Claw attacks, or she makes three\
    \ Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 24\
    \ (3d12 + 5) piercing damage."
  "name": "Bite (True Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 24\
    \ (3d12 + 5) slashing damage."
  "name": "Claw (True Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 23\
    \ (4d8 + 5) bludgeoning damage."
  "name": "Slam (Humanoid Form Only)"
- "desc": "The naina uses one of the following breath weapons:\n\n- Poison Breath.\
    \ The naina exhales poison breath in a 60-foot cone. Each creature in the area\
    \ must make a DC 17 Constitution saving throw. On a failure, a creature takes\
    \ 40 (9d8) poison damage and is [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ for 1 minute. On a success, a creature takes half the damage and isn't [poisoned](Mechanics/Rules/conditions.md#Poisoned).\
    \ The creature can repeat the saving throw at the end of each of its turns, ending\
    \ the effect on itself on a success.  \n- Paralysis Breath. The naina exhales\
    \ paralyzing breath in a 30-foot cone. Each creature in that area must succeed\
    \ on a DC 17 Constitution saving throw or be [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ for 1 minute. The creature can repeat the saving throw at the end of each of\
    \ its turns, ending the effect on itself on a success.  \n- Sleep Breath.\
    \ The naina exhales sleep gas around it. Each creature within 20 feet of the naina\
    \ must succeed on a DC 17 Constitution saving throw or fall [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ for 10 minutes. This effect ends for a creature if the creature takes damage\
    \ or another creature uses an action to wake it.  "
  "name": "Breath Weapons (Recharge 5-6)"
"bonus_actions":
- "desc": "The naina transforms into a Medium Humanoid or back into her true form,\
    \ which is a Dragon. Her statistics, other than her size, are the same in each\
    \ form. Any equipment she is wearing or carrying isn't transformed. It reverts\
    \ to its true from if she dies."
  "name": "Change Shape"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Naina.webp"
```
^statblock

## Environment

farmland, urban