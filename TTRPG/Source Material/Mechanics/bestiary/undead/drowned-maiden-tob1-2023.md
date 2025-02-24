---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/coastal
- monster/environment/underwater
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Drowned Maiden"]
---
# [Drowned Maiden](Mechanics\bestiary\undead/drowned-maiden-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 149*  

*A drowned woman floating in the water, her long hair drifting around her, suddenly rises! Her hair strikes out like dozens of watery snakes.*

## Raging Romantics

Drowned maidens are piteous, but terrifying, undead. They are created when a woman dies in water due to a doomed romance, often from unrequited love or drowned by a philandering partner. Either way, the drowned maiden awakens from death, seeking vengeance. Even as she dishes out retribution, a drowned maiden anguishes over her tragic fate.

## Beckoning for Help

The maiden lurks in the silent depths where she died—usually deserted docks, bridges, or coastal cliffs. She waits to pull the living to the same watery grave in which she is now condemned. Using her ability to disguise herself as a living person, she silently beckons victims from afar, acting as if in danger of drowning. When a victim is within range, the maiden uses her hair to pull her victim close enough to drain its strength with a magical kiss. Victims soon weaken and drown. The victim's final vision is the drowned maiden's tearful lament over the loss of life.

## Death to Betrayers

Desperate individuals may bargain with drowned maidens. Sometimes maidens release pleading victims who promise to return to her lair with the person who caused the maiden's death. Embracing and drowning her betrayer releases the maiden from undeath.

```statblock
"name": "Drowned Maiden (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "20d8"
"stats":
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "12"
- !!int "18"
"speed": "30 ft., swim 40 ft."
"saves":
  "Charisma": !!int "7"
  "Dexterity": !!int "6"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common"
"cr": "5"
"actions":
- "desc": "The drowned maiden makes three Hair attacks. She can replace one attack\
    \ with a use of Draining Kiss."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 20 ft., one target. Hit: 12\
    \ (2d8 + 3) slashing damage, and the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 16) if it is a Large or smaller creature. She can grapple up to three\
    \ creatures at a time. The hair holding a creature can be attacked and destroyed\
    \ (AC 15; 15 hp; immunity to necrotic, poison, and psychic damage)."
  "name": "Hair"
- "desc": "One creature within 5 feet of the maiden and that she is grappling must\
    \ make a DC 15 Charisma saving throw. On a failure, the target takes 10 (3d6)\
    \ psychic damage, and its Strength is reduced by 1d6. On a success, the target\
    \ takes half the damage, and its Strength isn't reduced. This reduction lasts\
    \ until the target finishes a long rest. The target dies if its Strength is reduced\
    \ to 0."
  "name": "Draining Kiss"
- "desc": "The maiden covers herself and anything she is wearing or carrying with\
    \ a magical illusion that makes her look like another creature of her general\
    \ size and Humanoid shape. The illusion ends if the maiden takes a bonus action\
    \ to end it or if she dies. The changes wrought by this effect fail to hold up\
    \ to physical inspection. Otherwise, a creature must take an action to visually\
    \ inspect the illusion and succeed on a DC 15 Intelligence ([Investigation](Mechanics/Rules/skills.md#Investigation))\
    \ check to discern that the maiden is disguised."
  "name": "Illusory Appearance"
"bonus_actions":
- "desc": "The drowned maiden pulls each creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by her up to 15 feet straight toward her."
  "name": "Reel"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Drowned%20Maiden.webp"
```
^statblock

## Environment

coastal, underwater