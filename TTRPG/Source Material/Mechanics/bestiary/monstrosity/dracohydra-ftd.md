---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/11
- monster/size/huge
- monster/type/monstrosity
statblock: inline
aliases: ["Dracohydra"]
---
# [Dracohydra](Mechanics\bestiary\monstrosity/dracohydra-ftd.md)
*Source: Fizban's Treasury of Dragons p. 176*  

The dracohydra is the result of arcane experimentation dedicated to recreating Tiamat's power. Amalgamating the magic of chromatic dragons with the blood of a hydra resulted in a many-headed draconic monster with wings and multiple snakelike tails. The dracohydra's breath weapon is a multicolored mass of energy that contains the essence of a chromatic dragon's elemental power.

These gluttonous creatures' appearance heralds disaster for any region they settle in, as they feed relentlessly—with each head demanding a feast of its own. If left alone, they hunt the local fauna almost to extinction, then move on to threatening the folk of nearby settlements.

A dracohydra can sometimes be found in the service of the spellcaster who created it, kept obedient by the rituals of their creation.

```statblock
"name": "Dracohydra (FTD)"
"size": "Huge"
"type": "monstrosity"
"alignment": "typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "218"
"hit_dice": "19d12 + 95"
"stats":
- !!int "20"
- !!int "12"
- !!int "20"
- !!int "6"
- !!int "12"
- !!int "12"
"speed": "30 ft., fly 30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "9"
"senses": "darkvision 60 ft., passive Perception 19"
"languages": "understands Draconic but can't speak"
"cr": "11"
"traits":
- "desc": "The dracohydra has five heads. While it has more than one head, the dracohydra\
    \ has advantage on saving throws against being [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [charmed](Mechanics/Rules/conditions.md#Charmed), [deafened](Mechanics/Rules/conditions.md#Deafened),\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [stunned](Mechanics/Rules/conditions.md#Stunned),\
    \ and knocked [unconscious](Mechanics/Rules/conditions.md#Unconscious).\n\nWhenever\
    \ the dracohydra takes 30 or more damage in a single turn, one of its heads dies.\
    \ If all its heads die, the dracohydra dies.\n\nAt the end of its turn, the dracohydra\
    \ grows two heads for each of its heads that died since its last turn, unless\
    \ it has taken radiant damage since its last turn. The dracohydra regains 10 hit\
    \ points for each head regrown this way."
  "name": "Multiple Heads"
- "desc": "For each head the dracohydra has beyond one, it gets an extra reaction\
    \ that can be used only for opportunity attacks."
  "name": "Reactive Heads"
- "desc": "While the dracohydra sleeps, at least one of its heads is awake."
  "name": "Wakeful"
"actions":
- "desc": "The dracohydra makes as many Bite attacks as it has heads."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 10\
    \ (1d10 + 5) damage of a type chosen by the dracohydra: acid, cold, fire, lightning,\
    \ or poison."
  "name": "Bite"
- "desc": "The dracohydra's heads exhale a single breath of multicolored energy in\
    \ a 60-foot cone. Each creature in that area must make a DC 17 Dexterity saving\
    \ throw. On a failed save, the creature takes 33 (6d10) damage of a type chosen\
    \ by the dracohydra: acid, cold, fire, lightning, or poison. On a successful save,\
    \ the creature takes half as much damage."
  "name": "Prismatic Breath (Recharge 4-6)"
"source":
- "FTD"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Dracohydra.webp"
```
^statblock