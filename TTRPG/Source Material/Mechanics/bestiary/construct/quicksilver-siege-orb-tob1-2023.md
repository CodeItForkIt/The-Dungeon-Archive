---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/5
- monster/environment/farmland
- monster/environment/urban
- monster/size/small
- monster/type/construct
statblock: inline
aliases: ["Quicksilver Siege Orb"]
---
# [Quicksilver Siege Orb](Mechanics\bestiary\construct/quicksilver-siege-orb-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 297*  

*This silver sphere, polished to a mirror-like sheen bobs gently in the air for a moment before suddenly flattening out into a round, serrated blade.*

The quicksilver siege orb is an alchemical construct designed for use as a siege weapon. The orb measures 3 feet in diameter and weighs 30 pounds. When it changes to disk form, its diameter increases to 6 feet, but it is only an inch thin.

## Smart Silver

Arcanists replicated a semi-sentient quicksilver they found in the underworld and provided it to warring factions. The metal changes its disposition to match its form. As an orb, it is contemplative and observant. As a blade, it is aggressive, seeking to kill enemy combatants. Fortunately, it takes commands well and avoids inflicting collateral damage.

## Autonomous Siege Weapon

A quicksilver siege orb can fit into a catapult or other throwing siege weapon while in spherical form. When it reaches its destination, it hovers in place to assess soft targets before changing into its disk form and injuring or killing those targets.

## Customizable Alternate Form

Though the siege orb can have only one alternate form, the orb accepts instructions for several shapes beyond the standard whirling disk, such as spiked balls, borers, and other devices useful in battle.

```statblock
"name": "Quicksilver Siege Orb (ToB1-2023)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "15"
"hp": !!int "82"
"hit_dice": "15d6 + 30"
"stats":
- !!int "12"
- !!int "21"
- !!int "14"
- !!int "5"
- !!int "14"
- !!int "7"
"speed": "10 ft., fly 40 ft. (hover)"
"skillsaves":
  "Stealth": !!int "8"
  "Perception": !!int "5"
"damage_vulnerabilities": "cold"
"damage_resistances": "fire; lightning; piercing, slashing from nonmagical attacks"
"damage_immunities": "bludgeoning, poison, psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "understands one language of its creator but can't speak"
"cr": "5"
"traits":
- "desc": "Whenever the quicksilver siege orb is subjected to bludgeoning damage,\
    \ it takes no damage and instead is pushed up to 15 feet away from the source\
    \ of the bludgeoning damage. If the damage is from a critical hit, the orb is\
    \ pushed up to 30 feet."
  "name": "Bludgeoning Bounce (Orb Form Only)"
- "desc": "The quicksilver siege orb doesn't require air, food, drink, or sleep."
  "name": "Construct Nature"
- "desc": "The quicksilver siege orb doesn't provoke opportunity attacks when it flies\
    \ out of an enemy's reach."
  "name": "Flyby"
- "desc": "The quicksilver siege orb is immune to any spell or effect that would alter\
    \ its form."
  "name": "Immutable Form"
- "desc": "The quicksilver siege orb has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ and Wisdom ([Insight](Mechanics/Rules/skills.md#Insight)) checks. In addition,\
    \ if the orb observes a creature for at least 1 minute, it has advantage on the\
    \ first three attack rolls it makes against the creature."
  "name": "Observant (Orb Form Only)"
- "desc": "The quicksilver siege orb has advantage on saving throws and ability checks\
    \ made to escape a grapple."
  "name": "Slippery"
"actions":
- "desc": "The quicksilver siege orb makes three Disk Blade or Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage."
  "name": "Disk Blade (Disk Form Only)"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d4 + 5) bludgeoning damage."
  "name": "Slam (Orb Form Only)"
- "desc": "The quicksilver siege orb flies up to 20 feet in a straight line, then\
    \ it flies up to 20 feet in a straight line in a different direction. During this\
    \ move, it can move through the space of any Large or smaller creature. The first\
    \ time it enters a creature's space during this move, that creature must make\
    \ a DC 16 Dexterity saving throw, taking 35 (10d6) slashing damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Slashing Run (Recharge 4-6)"
"bonus_actions":
- "desc": "The quicksilver siege orb flattens itself into a razor-sharp, whirling\
    \ disk or back into its orb form. Its statistics are the same in each form. It\
    \ becomes a puddle of quicksilver if it dies."
  "name": "Shape Quicksilver"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Quicksilver%20Siege%20Orb.webp"
```
^statblock

## Environment

farmland, urban