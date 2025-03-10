---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/5
- monster/size/medium
- monster/type/monstrosity/shapechanger
statblock: inline
aliases: ["Dread Doppelganger"]
---
# [Dread Doppelganger](Mechanics\bestiary\monstrosity/dread-doppelganger-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 139*  

> [!quote] A quote from Doppelganger  
> 
> Let me borrow your face... You won't be needing it anymore.

The dread doppelganger is an ancient member of that race. It has lived for centuries adopting the forms of hundreds or even thousands of different creatures. The long years of impersonating others has drained these elder beings of any kind of empathy. Most dread doppelgangers work alone, though sometimes they will lead a band of younger members of their kind.

## Emotionless

Dread doppelgangers have impersonated the feelings and emotions of so many others that they find it difficult to feel emotions of their own. Because of this they make excellent spies and assassins, for they don't experience remorse for anything that they might have to do. Dread doppelgangers seek out increasingly risky and bizarre behavior in order to instill any kind of emotion. Often this means they will take on dangerous jobs that could bring about their own death.

## Unnatural Gait

In their natural form dread doppelgangers move about in a disturbing fashion. They are so used to mimicking the movements of others that their own manner of moving seems broken and chaotic. While they might seem ungainly and clumsy when they move, they can lash out at speeds that often surprise their victims.

```statblock
"name": "Dread Doppelganger (MaBJoV)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "11"
- !!int "22"
- !!int "14"
- !!int "17"
- !!int "14"
- !!int "15"
"speed": "40 ft."
"skillsaves":
  "Deception": !!int "8"
  "Stealth": !!int "9"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common"
"cr": "5"
"traits":
- "desc": "The dread doppelganger casts one of the following spells, requiring no\
    \ material components and using Intelligence as the spellcasting ability (spell\
    \ save DC 14):\n\n1/day each: [mirror image](Mechanics/spells/mirror-image.md),\
    \ [mislead](Mechanics/spells/mislead.md)\n\n2/day: [phantasmal killer](Mechanics/spells/phantasmal-killer.md)"
  "name": "Spellcasting"
- "desc": "The dread doppelganger has advantage on attack rolls against any creature\
    \ it has surprised."
  "name": "Ambusher"
- "desc": "The dread doppelganger can use its action to polymorph into a Small or\
    \ Medium Humanoid it has seen, or back into its true form. Its statistics, other\
    \ than its size, are the same in each form. Any equipment it is wearing or carrying\
    \ isn't transformed. It reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "If the dread doppelganger surprises a creature and hits it with an attack\
    \ during the first round of combat, the target takes an extra 17 (5d6) damage\
    \ from the attack."
  "name": "Surprise Attack"
"actions":
- "desc": "The dread doppelganger makes three Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, range 5 ft., one target. Hit: 10\
    \ (1d8 + 6)."
  "name": "Slam"
- "desc": "The dread doppelganger magically reads the surface thoughts of one creature\
    \ within 60 feet of it. The effect can penetrate barriers, but 3 ft. of wood or\
    \ dirt, 2 feet of stone, 2 inches of metal, or a thin sheet of lead blocks it.\
    \ While the target is in range, the dread doppelganger can continue reading its\
    \ thoughts, as long as the dread doppelganger's Concentration isn't broken (as\
    \ if concentrating on a spell). While reading the target's mind, the doppelganger\
    \ has advantage on Wisdom ([Insight](Mechanics/Rules/skills.md#Insight)) and Charisma\
    \ ([Deception](Mechanics/Rules/skills.md#Deception), [Intimidation](Mechanics/Rules/skills.md#Intimidation),\
    \ and [Persuasion](Mechanics/Rules/skills.md#Persuasion)) checks against the target."
  "name": "Read Thoughts"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Dread%20Doppelganger.webp"
```
^statblock