---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/15
- monster/size/gargantuan
- monster/type/monstrosity
statblock: inline
aliases: ["Eyestalk of Gzemnid"]
---
# [Eyestalk of Gzemnid](Mechanics\bestiary\monstrosity/eyestalk-of-gzemnid-tofw.md)
*Source: Turn of Fortune's Wheel p. 88*  

Gzemnid is a beholder god of deception, gases, and obscurement.

The realm of the beholder deity Gzemnid lies beneath the Outlands. Most entrances into these mysterious, gas-filled caverns are found near chaotically aligned gate-towns—like Bedlam, Sylvania, or Xaos—but Gzemnid's Realm is elusive, even by the mutable standards of the Outlands.

```statblock
"name": "Eyestalk of Gzemnid (ToFW)"
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
- "desc": "The eyestalk can burrow through solid rock at half its burrow speed and\
    \ leaves a 10-foot-diameter tunnel in its wake."
  "name": "Tunneler"
"actions":
- "desc": "The eyestalk attacks with its bite and uses Eradication Gaze."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +14 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d8 + 9) piercing damage. If the target is a Large or smaller creature, it\
    \ must succeed on a DC 19 Dexterity saving throw or be swallowed by the eyestalk.\
    \ A swallowed creature is [blinded](Mechanics/Rules/conditions.md#Blinded) and\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained), it has total cover against\
    \ attacks and other effects outside the eyestalk, and it takes 21 (6d6) acid\
    \ damage at the start of each of the eyestalk's turns.\n\nIf the eyestalk takes\
    \ 30 damage or more on a single turn from a creature inside it, the eyestalk must\
    \ succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate\
    \ all swallowed creatures, which fall [prone](Mechanics/Rules/conditions.md#Prone)\
    \ in a space within 10 feet of the eyestalk. If the eyestalk dies, a swallowed\
    \ creature is no longer [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by it and can escape from the corpse by using 20 feet of movement, exiting [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Bite"
- "desc": "The eyestalk creates an area of magical devastation in a 150-foot cone.\
    \ Any creature in that area must succeed on a DC 16 Dexterity saving throw or\
    \ take 55 (10d10) necrotic damage. If this damage reduces a creature to 0 hit\
    \ points, its body becomes a pile of fine violet dust."
  "name": "Eradication Gaze (Recharge 5-6)"
"source":
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/Eyestalk%20of%20Gzemnid.webp"
```
^statblock