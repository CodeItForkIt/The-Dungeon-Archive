---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/14
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Wersten Kern"]
---
# [Wersten Kern](Mechanics\bestiary\npc/wersten-kern-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 209*  

Wersten Kern is Lord Soth's standard bearer and champion. As with many of Soth's knights, she died alongside her liege during the Cataclysm and was cursed with undeath. In battle, she wields a wicked pike that flies Soth's black rose standard, and her cries can stop mighty warriors' hearts. Wersten staunchly follows Soth's commands, and she will serve him until she faces a second doom.

```statblock
"name": "Wersten Kern (DSotDQ)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate](Mechanics/items/plate-armor.md)"
"hp": !!int "178"
"hit_dice": "21d8 + 84"
"stats":
- !!int "21"
- !!int "10"
- !!int "18"
- !!int "13"
- !!int "14"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Constitution": !!int "9"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Infernal, Solamnic"
"cr": "14"
"traits":
- "desc": "Wersten casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n1/day\
    \ each: [dispel magic](Mechanics/spells/dispel-magic.md), [wall of stone](Mechanics/spells/wall-of-stone.md)"
  "name": "Spellcasting"
- "desc": "If damage reduces Wersten to 0 hit points, she must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is bludgeoning\
    \ or from a critical hit. On a success, Wersten drops to 1 hit point instead."
  "name": "Undead Fortitude"
- "desc": "Wersten doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "Wersten makes three Banner Pike attacks and uses Terrifying Litany if it's\
    \ available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d10 + 5) piercing damage plus 13 (3d8) necrotic damage. If the target\
    \ is a Humanoid, it must succeed on a DC 16 Charisma saving throw or be cursed.\
    \ The curse lasts until it is lifted by remove curse or similar magic. Black,\
    \ thorny rose stems sprout from the creature's body while it is cursed, imposing\
    \ disadvantage on the creature's ability checks and attack rolls and halving its\
    \ speed. A creature that succeeds on the saving throw against the curse is immune\
    \ to it for 24 hours."
  "name": "Banner Pike"
- "desc": "Wersten recites names of souls slain by Soth and his company, channeling\
    \ their mortal terror. Each creature that isn't an Undead within 30 feet of her\
    \ must make a DC 16 Wisdom saving throw. On a failed save, the creature takes\
    \ 22 (4d10) psychic damage and is [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ of Wersten for 1 minute. On a successful save, the creature takes half as much\
    \ damage and isn't [frightened](Mechanics/Rules/conditions.md#Frightened). At\
    \ the end of each of its turns, a [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ creature can repeat the saving throw, ending the effect on itself on a success."
  "name": "Terrifying Litany (Recharge 5-6)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Wersten%20Kern.webp"
```
^statblock