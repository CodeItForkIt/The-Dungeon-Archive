---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/15
- monster/size/gargantuan
- monster/type/monstrosity
statblock: inline
aliases: ["Crater Wurm"]
---
# [Crater Wurm](Mechanics\bestiary\monstrosity/crater-wurm-dodk.md)
*Source: Dungeons of Drakkenheim p. 197*  

Found only in the Crater Basin, these massive burrowing monsters have petal-like mouths lined with razor-sharp teeth. Their thick hides of midnight purple are covered in spines and octarine slime. Those who have survived an encounter with one have spoken of the earth shaking moments before the beast emerges from below, devouring helpless victims caught in its path.

```statblock
"name": "Crater Wurm (DoDk)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "247"
"hit_dice": "15d20 + 90"
"stats":
- !!int "28"
- !!int "7"
- !!int "22"
- !!int "1"
- !!int "8"
- !!int "4"
"speed": "50 ft., burrow 30 ft."
"saves":
  "Wisdom": !!int "4"
  "Constitution": !!int "11"
"senses": "blindsight 30 ft., tremorsense 60 ft., passive Perception 9"
"languages": ""
"cr": "15"
"traits":
- "desc": "The wurm can burrow through solid rock at half its burrow speed and leaves\
    \ a 10-foot-diameter tunnel in its wake."
  "name": "Tunneler"
"actions":
- "desc": "The crater wurm utilises its full movement. While doing so, it can enter\
    \ large or smaller creatures' spaces. Whenever the wurm enters a creature's space,\
    \ the creature must succeed on a DC 19 Strength saving throw. On a successful\
    \ save, the creature can choose to be pushed to the side of the wurm's space.\
    \ A creature that chooses not to be pushed suffers the consequences of a failed\
    \ saving throw. On a failed save, the creature takes 35 (10d6) bludgeoning damage,\
    \ and is pushed 10 feet and knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ After finishing its move, the wurm can make one bite attack against a [prone](Mechanics/Rules/conditions.md#Prone)\
    \ target as a bonus action."
  "name": "Breach"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d8 + 9) piercing damage. If the target is a Large or smaller creature, it\
    \ must succeed on a DC 19 Dexterity saving throw or be swallowed by the wurm.\
    \ A swallowed creature is [blinded](Mechanics/Rules/conditions.md#Blinded) and\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained), it has total cover against\
    \ attacks and other effects outside the wurm, and it takes 21 (6d6) acid damage\
    \ at the start of each of the wurm's turns.\n\nIf the wurm takes 30 damage or\
    \ more on a single turn from a creature inside it, the wurm must succeed on a\
    \ DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed\
    \ creatures, which fall [prone](Mechanics/Rules/conditions.md#Prone) in a space\
    \ within 10 feet of the wurm. If the wurm dies, a swallowed creature is no longer\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained) by it and can escape\
    \ from the corpse by using 20 feet of movement, exiting [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Bite"
- "desc": "A creature swallowed by a crater wurm gains one level of contamination\
    \ each time it takes acid damage while inside the wurm."
  "name": "Contaminated Gullet"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Crater%20Wurm.webp"
```
^statblock