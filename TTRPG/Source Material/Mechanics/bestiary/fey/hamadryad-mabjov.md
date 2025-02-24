---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/2
- monster/size/medium
- monster/type/fey
statblock: inline
aliases: ["Hamadryad"]
---
# [Hamadryad](Mechanics\bestiary\fey/hamadryad-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 143*  

> [!quote] A quote from Hamadryad  
> 
> I cannot drink the water. My roots grow black and rotten. I cannot drink the water. My leaves wither and die. I cannot drink...

> [!quote] A quote from Volo  
> 
> It is a sad thing when one of nature's most beautiful fey is corrupted into a hamadryad. Be careful about feeling too much sympathy for them, for they are fearsome when someone trespasses into their territory.

These fey come into being when the home tree of a dryad is destroyed or becomes corrupted by foul magic. If the dryad isn't killed she slowly wastes away and over the course of several months becomes a hamadryad. Hamadryads are mad creatures that seek vengeance against any non-fey that wanders into the deep places of the wood that is their home.

## Beauty Lost

Hamadryads do not retain the beauty that they had before whatever tragedy befell them. Their mouths have vanished and their laughter is forever gone. The beautiful feminine forms dryads are famed for have become twisted. Their emerald skin is grey and sickly and their very touch is corrupt and poisonous.

## Madness

Hamadryads rarely behave in a manner that seems rational. They might viciously attack an intruder and then vanish, only to return later when their mood changes. Sometimes they might help a group of adventurers against evil creatures only to turn on the adventurers once their mutual foe is vanquished.

```statblock
"name": "Hamadryad (MaBJoV)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "16 with [barkskin](Mechanics/spells/barkskin.md)"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"stats":
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "10"
- !!int "15"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "2"
"senses": "darkvision 60ft., passive Perception 12"
"languages": "Sylvan"
"cr": "2"
"traits":
- "desc": "The hamadryad casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 12):\n\
    \n1/day each: [barkskin](Mechanics/spells/barkskin.md), [grasping vine](Mechanics/spells/grasping-vine.md),\
    \ [pass without trace](Mechanics/spells/pass-without-trace.md)\n\n2/day: [entangle](Mechanics/spells/entangle.md)"
  "name": "Spellcasting"
- "desc": "The hamadryad has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The hamadryad can communicate with Beasts and Plants as if they shared\
    \ a language."
  "name": "Speak with Beasts and Plants"
- "desc": "Once on her turn, the hamadryad can use 10 feet of her movement to step\
    \ magically into one living tree within her reach and emerge from a second living\
    \ tree within 60 feet of the first tree, appearing in an unoccupied space within\
    \ 5 feet of the second tree. Both trees must be Large in size or bigger."
  "name": "Tree Stride"
"actions":
- "desc": "The hamadryad makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, range 5 ft., one target. Hit: 5 (1d4\
    \ + 3) plus 10 (3d6) poison damage."
  "name": "Claw"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Hamadryad.webp"
```
^statblock