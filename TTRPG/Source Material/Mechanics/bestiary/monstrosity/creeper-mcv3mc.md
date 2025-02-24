---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mcv3mc
- monster/cr/1-2
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Creeper"]
---
# [Creeper](Mechanics\bestiary\monstrosity/creeper-mcv3mc.md)
*Source: Monstrous Compendium Volume 3: Minecraft Creatures p. 4, Lightning Keep*  

A creeper is a green, armless creature that emerges in darkness and silently prowls the Overworld on its four short legs. Its peculiar face bears no clue of its motives, but its destructiveness makes it one of the greatest threats to both life and property in the Overworld.

A creeper quietly shuffles toward Humanoid prey. When it gets close enough, it halts and begins to hiss like a burning fuse. Unless the creeper is defeated or its target gets far enough away that the creeper defuses itself, the creeper explodes a few short moments later, leaving a crater where it once stood.

Creepers have an uncanny ability to appear when least expected, and few places are safe from their explosive nature. Yet creepers have one strange weakness: they fear cats and do all they can to avoid them.

If a creeper is struck by lightning, rather than being harmed, it becomes charged with electrical power. In this charged state, the creeper gains a bluish aura and can explode with even greater power.

```statblock
"name": "Creeper (MCV3MC)"
"size": "Medium"
"type": "monstrosity"
"alignment": "typically  Neutral Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"stats":
- !!int "10"
- !!int "11"
- !!int "14"
- !!int "6"
- !!int "8"
- !!int "3"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"damage_immunities": "lightning"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1/2"
"traits":
- "desc": "The creeper can't take actions except for [Dash](Mechanics/Rules/actions.md#Dash),\
    \ [Disengage](Mechanics/Rules/actions.md#Disengage), [Hide](Mechanics/Rules/actions.md#Hide),\
    \ and [Search](Mechanics/Rules/actions.md#Search). It can't take bonus actions\
    \ or reactions."
  "name": "Bizarre Physiology"
- "desc": "When a creeper drops to 0 hit points from a charged creeper's explosion\
    \ (see the Destruction trait), it dies and its head falls off. A creeper's fallen\
    \ head is hollow and can be worn as a mask with eye and mouth openings."
  "name": "Creeper Head"
- "desc": "When it ends its turn within 10 feet of a Humanoid that it can see, the\
    \ creeper stops moving and emits a hiss loud enough to be heard by creatures within\
    \ 30 feet of itself.\n\nIf the creeper drops to 0 hit points before the start\
    \ of its next turn, the hissing stops, and the creeper dies. Otherwise, at the\
    \ start of the creeper's next turn, one of following things happens:\n\n- If there\
    \ are no Humanoids within 10 feet of the hissing creeper, it stops hissing. It\
    \ then uses any available movement to approach the nearest Humanoid it can see.\
    \  \n- If there are one or more Humanoids within 10 feet of the hissing creeper,\
    \ the creeper explodes in a ball of energy that fills a 20-foot-radius sphere\
    \ centered on itself. This energy spreads around corners. The creeper is destroyed,\
    \ and every other creature in the explosion's area must make a DC 12 Dexterity\
    \ saving throw, taking 14 (4d6) lightning damage on a failed save, or half as\
    \ much damage on a successful one. Increase this damage by 7 (2d6) if the creeper\
    \ is charged (see \"Electrical Charge\" below). Objects in the area that aren't\
    \ being worn or carried take 14 (4d6) lightning damage, or 21 (6d6) lightning\
    \ damage if the creeper is charged.  "
  "name": "Destruction"
- "desc": "Whenever the creeper is subjected to lightning damage, it takes no damage\
    \ and instead becomes charged for 1 minute. While charged, the creeper emits dim\
    \ blue light in a 5-foot radius."
  "name": "Electrical Charge"
- "desc": "The creeper has the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition whenever it starts its turn within 60 feet of a feline creature it\
    \ can see. The condition lasts until the start of the creeper's next turn."
  "name": "Fear of Felines"
"source":
- "MCV3MC"
- "LK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV3MC/Creeper.webp"
```
^statblock