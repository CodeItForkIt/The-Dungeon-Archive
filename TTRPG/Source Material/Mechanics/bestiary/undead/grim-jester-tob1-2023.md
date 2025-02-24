---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/11
- monster/environment/any
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Grim Jester"]
---
# [Grim Jester](Mechanics\bestiary\undead/grim-jester-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 224*  

*A skeletal cadaver bedecked in the motley attire of a fool capers about while making jokes that mock mortality.*

## Amusing Death

When a jester on its deathbed moves an evil death god to laughter, the fool sometimes gains a reprieve as a grim jester. Their purpose is to bring an end to mortal lives in a gruesome, comic, and absurd manner. As long as such jesters keep the death god amused, their continued unlife is assured.

## Grisly Humor

A grim jester's jokes are not funny to their victims, but they offer a grim finality in combat. A killing joke might be absurd or sheer braggadocio, while others might be high-flown. Grim jesters are famous for grim, bitter mockery, but such humor rarely entertains mortals.

## Randomness

Grim jesters enjoy randomness and often get their hands on wands of wonder and scrolls of chaos magic. Beware the grim jester with a deck of many things—they are quite talented in pulling cards whose magic then applies to foes and spectators.

```statblock
"name": "Grim Jester (ToB1-2023)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"stats":
- !!int "14"
- !!int "22"
- !!int "18"
- !!int "16"
- !!int "16"
- !!int "20"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "10"
  "Constitution": !!int "8"
"skillsaves":
  "Sleight of Hand": !!int "10"
  "Deception": !!int "9"
  "Stealth": !!int "10"
  "Perception": !!int "7"
  "Performance": !!int "9"
  "Acrobatics": !!int "10"
"damage_resistances": "cold"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Abyssal, Celestial, Common, Gnomish, telepathy 120 ft."
"cr": "11"
"traits":
- "desc": "The grim jester casts one of the following spells, requiring no components\
    \ and using Charisma as the spellcasting ability (spell save DC 17):\n\nAt will:\
    \ [disguise self](Mechanics/spells/disguise-self.md), [grease](Mechanics/spells/grease.md)\n\
    \n1/day each: [mislead](Mechanics/spells/mislead.md), [seeming](Mechanics/spells/seeming.md)\n\
    \n3/day each: [magic mouth](Mechanics/spells/magic-mouth.md) (as an action),\
    \ [mirror image](Mechanics/spells/mirror-image.md)"
  "name": "Spellcasting"
- "desc": "Unless it is destroyed in a manner amusing to the god of death that created\
    \ it, the grim jester gains a new body in  days, regaining all its hp and becoming\
    \ active again. The new body appears in a place of the god's choosing."
  "name": "Last Laugh"
- "desc": "Death saving throws made within 60 feet of the grim jester have disadvantage."
  "name": "Mock the Dying"
- "desc": "The grim jester has advantage on saving throws against any effect that\
    \ turns undead."
  "name": "Turn Resistance"
- "desc": "The grim jester doesn't require air, food, drink, or sleep."
  "name": "Undead Nature"
"actions":
- "desc": "The grim jester can use its Killing Joke. It then makes two Necrotic Claw\
    \ attacks. It can replace one attack with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +9 to hit, range 5 ft., one target. Hit: 14 (2d8\
    \ + 5) slashing damage plus 14 (4d6) necrotic damage."
  "name": "Necrotic Claw"
- "desc": "The grim jester tells an ancient, nihilistic joke to one creature it can\
    \ see within 60 feet of it. The target must succeed on a DC 17 Wisdom saving throw\
    \ or fall [prone](Mechanics/Rules/conditions.md#Prone) in a fit of laughter, becoming\
    \ [incapacitated](Mechanics/Rules/conditions.md#Incapacitated) and unable to stand\
    \ up for 1 minute. A creature that fails this saving throw by 5 or more is reduced\
    \ to 0 hp instead. The [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ target can repeat the saving throw at the end of each of its turns, taking 14\
    \ (4d6) necrotic damage on a failed save or ending the effect on itself on a\
    \ success."
  "name": "Killing Joke"
"bonus_actions":
- "desc": "The grim jester exchanges locations with a Medium or smaller creature it\
    \ can see within 60 feet of it. The jester and target each teleport to the other's\
    \ space, and each becomes covered in a magical illusion to look and sound like\
    \ the other. A creature must take an action to visually inspect an illusion and\
    \ succeed on a DC 19 Intelligence ([Investigation](Mechanics/Rules/skills.md#Investigation))\
    \ check to discern that the jester and target are disguised. The illusions last\
    \ for 1 minute, until the jester dies, or until the jester dismisses them as a\
    \ bonus action."
  "name": "Joker's Shuffle (Recharge 6)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Grim%20Jester.webp"
```
^statblock

## Environment

any