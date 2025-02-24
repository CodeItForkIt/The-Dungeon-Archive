---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/0
- monster/size/tiny
- monster/type/beast
statblock: inline
aliases: ["Parrot"]
---
# [Parrot](Mechanics\bestiary\beast/parrot-psx.md)
*Source: Plane Shift: Ixalan p. 39*  

A wide variety of native birds are found throughout Ixalan, singing complex songs that contribute to the chorus of sounds within the jungle. Hummingbirds are sometimes poetically described as embodiments of freedom and the pursuit of pleasure. Large macaws and parrots (with statistics like those of [ravens](Mechanics/bestiary/beast/raven.md)) make their homes in the trees and can often be found gathering over clay licks along riverbeds and the sea coast. The wily birds enjoy toying with people from the trees, with many of them calling out in imitation of humanoid voices to lead pirates and other explorers astray.

```statblock
"name": "Parrot (PSX)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "2"
- !!int "14"
- !!int "8"
- !!int "2"
- !!int "12"
- !!int "6"
"speed": "10 ft., fly 50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The parrot can mimic simple sounds it has heard, such as a person whispering,\
    \ a baby crying, or an animal chittering. A creature that hears the sounds can\
    \ tell they are imitations with a successful DC 10 Wisdom ([Insight](Mechanics/Rules/skills.md#Insight))\
    \ check."
  "name": "Mimicry"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 piercing\
    \ damage."
  "name": "Beak"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Parrot.webp"
```
^statblock