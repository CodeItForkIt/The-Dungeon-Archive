---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/2
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Shoal Serpent"]
---
# [Shoal Serpent](Mechanics\bestiary\beast/shoal-serpent-psz.md)
*Source: Plane Shift: Zendikar p. 26*  

The oceans, bays, and swamps of Zendikar are home to a variety of aquatic creatures that are at least as deadly as those on land, including monstrosities that can face the largest Eldrazi on almost equal footing. Given the dangers of Zendikar, even mundane animals such as octopuses, frogs, turtles, crabs, and crocodiles can grow to tremendous size (using the appropriate statistics from appendix A of the Monster Manual). The crabs of Ondu, the crocodiles of Guul Draz, the tortoises of Tazeem, and the octopuses of the deep sea (of which Lorthos the Tidemaker is but one giant specimen) are examples of these aquatic monstrosities. Enormous shoal serpents—sometimes compared to "a reef that runs aground on ships"—are a persistent danger to vessels along the Onduan coast. The [plesiosaurus](Mechanics/bestiary/beast/plesiosaurus.md) in the Monster Manual can represent these serpents.

```statblock
"name": "Shoal Serpent (PSZ)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d10 + 24"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "2"
- !!int "12"
- !!int "5"
"speed": "20 ft., swim 40 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "2"
"traits":
- "desc": "The serpent can hold its breath for 1 hour."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 14\
    \ (3d6 + 4) piercing damage."
  "name": "Bite"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Shoal%20Serpent.webp"
```
^statblock