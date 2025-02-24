---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
statblock: inline
aliases: ["Manticore, Heart-Piercer"]
---
# [Manticore, Heart-Piercer](Mechanics\bestiary\monstrosity/manticore-heart-piercer-psa.md)
*Source: Plane Shift: Amonkhet p. 36*  

Manticores are catlike creatures with feline bodies, tails like those of [scorpions](Mechanics/bestiary/beast/scorpion.md), and chitinous plates on their lower legs and feet. The venom of their tail stingers is the most virulent poison known on Amonkhet, and they can sting with lightning speed even while tearing at a foe with claws and teeth. Their deadliness makes them prized for use in the Trial of Zeal, where they grant glorified deaths to many initiates.

## The Desert Lands

The desolate wilderness beyond the protection of the Hekma is largely uncharted. Immediately beyond the protective veil is a chaotic dune sea called Shefet, the Scouring Sands. The desert wears away at the edges of the fertile lands surrounding Naktamun, serving as a constant reminder that only the bounty and protection of the God-Pharaoh stand between the people of the city-state and a grisly death in the sands beyond. Beyond Shefet are parched, cracked expanses called Ramunap, the Broken Lands. The ruins of ancient civilizations are said to lie in the Broken Lands, though no one has ever explored such ruins and returned to Naktamun to tell of them.

```statblock
"name": "Manticore, Heart-Piercer (PSA)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "19"
- !!int "14"
- !!int "16"
- !!int "5"
- !!int "12"
- !!int "6"
"speed": "50 ft."
"skillsaves":
  "Perception": !!int "4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "5"
"actions":
- "desc": "The manticore makes two attacks, one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) slashing damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 11\
    \ (2d6 + 4) piercing damage. The target must make a DC 14 Constitution saving\
    \ throw, taking 24 (7d6) poison damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Stinger"
"source":
- "PSA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Manticore%2C%20Heart-Piercer.webp"
```
^statblock