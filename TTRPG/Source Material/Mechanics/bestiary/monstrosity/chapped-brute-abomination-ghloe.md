---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/9
- monster/size/huge
- monster/type/monstrosity
statblock: inline
aliases: ["Chapped Brute Abomination"]
---
# [Chapped Brute Abomination](Mechanics\bestiary\monstrosity/chapped-brute-abomination-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 68*  

> [!quote]  
> 
> The callused skin of the merchant's hulking bodyguard ripples as if something beneath is trying to wriggle free.

## Salvage

Chapped brutes rarely carry treasure or equipment unless doing so as instructed by their master. An accomplished leatherworker can fashion the callused skin of a chapped brute into+1 armor—leather, studded leather, or hide—that grants the wearer resistance to necrotic damage and doesn't require attunement. This armor takes 10 extra days of work to fashion, and magical components worth 100 gp must be expended in its creation.

## Lore

- **DC 10 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** The magical and alchemical process that creates these brutes leaves them resistant to necrotic damage.  
- **DC 15 Intelligence ([Nature](Mechanics/Rules/skills.md#Nature)).** These beings are so volatile because of their creation process that when they are killed, they have a chance to transform into larger, deadlier forms.  
- **DC 20 Wisdom ([Medicine](Mechanics/Rules/skills.md#Medicine)).** The final form of the chapped brute has a life force that fluctuates, so that it randomly gains and loses life force every few seconds.  

> [!note] GM Advice
> 
> You can use any chapped brute form as part of an encounter. You can also build encounters in which one chapped brute transforms into one or both of its larger forms. To do so, treat each form as a separate monster. Transformation can take up to 1 minute, allowing you to stagger the encounters, but it can occur as quickly as you need it to for your game.
^gm-advice

```statblock
"name": "Chapped Brute Abomination (GHLoE)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "161"
"hit_dice": "14d12 + 70"
"stats":
- !!int "23"
- !!int "10"
- !!int "20"
- !!int "3"
- !!int "10"
- !!int "5"
"speed": "40 ft."
"skillsaves":
  "Athletics": !!int "10"
"damage_resistances": "necrotic"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [prone](Mechanics/Rules/conditions.md#Prone)"
"senses": "blindsight 90 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "9"
"traits":
- "desc": "After taking damage, the chapped brute abomination gains resistance to\
    \ that type of damage until it takes another type of damage."
  "name": "Adaptive Hide"
- "desc": "The chapped brute abomination has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on hearing or smell. While [deafened](Mechanics/Rules/conditions.md#Deafened)\
    \ and unable to smell, the brute can't use its blindsight."
  "name": "Keen Hearing and Smell"
- "desc": "At the start of the chapped brute abomination's turn, roll . The abomination\
    \ regains hit points equal to any even result and loses hit points equal to any\
    \ odd result. The abomination can neither exceed its hit point maximum with a\
    \ gain nor fall below 1 hit point with a loss."
  "name": "Unstable Life"
"actions":
- "desc": "The chapped brute abomination makes two tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 20 ft., one target. Hit: 22\
    \ (3d10 + 6) bludgeoning damage. If the target is Medium or smaller, it is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 18). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the brute can't use the tentacle against another target. The chapped brute\
    \ abomination has four tentacles."
  "name": "Tentacle"
- "desc": "Each creature [grappled](Mechanics/Rules/conditions.md#Grappled) by the\
    \ chapped brute abomination must succeed on a DC 18 Strength saving throw or be\
    \ pulled into the brute's body. An engulfed target is [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [restrained](Mechanics/Rules/conditions.md#Restrained), unable to breathe, and\
    \ has total cover from effects that originate outside the brute. At the start\
    \ of each of the brute's turns, each engulfed creature takes 14 (4d6) acid damage.\
    \ The brute can hold only one Large creature or up to four Medium or smaller creatures\
    \ inside it at a time.\n\nAn engulfed creature can try to escape by taking an\
    \ action to make its choice of a DC 18 Strength ([Athletics](Mechanics/Rules/skills.md#Athletics))\
    \ or Dexterity ([Acrobatics](Mechanics/Rules/skills.md#Acrobatics)) check. On\
    \ a success, the creature escapes and uses 10 feet of movement to enter a space\
    \ of its choice within 5 feet of the brute.\n\nIf the brute dies, an engulfed\
    \ creature is no longer [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ by it and can escape from the corpse by using 10 feet of movement.\n\nIf a creature\
    \ dies inside the brute, the brute doesn't roll for Unstable Life at the start\
    \ of its next turn and instead regains 20 hit points. The creature's body breaks\
    \ up inside the brute, and the brute expels anything the creature wore or carried."
  "name": "Engulf"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Chapped%20Brute%20Abomination.webp"
```
^statblock