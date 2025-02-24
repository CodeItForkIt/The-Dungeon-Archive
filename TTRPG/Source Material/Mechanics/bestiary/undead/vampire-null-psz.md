---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/1-4
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Vampire Null"]
---
# [Vampire Null](Mechanics\bestiary\undead/vampire-null-psz.md)
*Source: Plane Shift: Zendikar p. 28*  

The various forms of undead ghosts are the incorporeal remnants of life and personality left after the death of a mortal body. But sometimes the reverse is true: a body retains its animation and hunger while losing any trace of its soul, becoming a zombie. When a vampire who is not a bloodchief drains the blood from a living humanoid, that creature undergoes a horrible transformation, becoming a stronger, faster version of a [zombie](Mechanics/bestiary/undead/zombie.md) called a null. Nulls' heads are featureless except for a gaping mouth filled with jagged teeth. Their bodies are shriveled and distorted, but preternaturally strong. They are mindlessly loyal servants to the vampire nobility, and the number of nulls under a vampire's control is a mark of status and power among the vampire houses of Guul Draz.

```statblock
"name": "Vampire Null (PSZ)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"stats":
- !!int "13"
- !!int "6"
- !!int "16"
- !!int "3"
- !!int "6"
- !!int "5"
"speed": "20 ft."
"saves":
  "Wisdom": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands all languages it spoke in life but can't speak"
"cr": "1/4"
"traits":
- "desc": "If damage reduces the null to 0 hit points, it must make a Constitution\
    \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
    \ or from a critical hit. On a success, the null drops to 1 hit point instead."
  "name": "Undead Fortitude"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage."
  "name": "Slam"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Vampire%20Null.webp"
```
^statblock