---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/2
- monster/size/medium
- monster/type/dragon
statblock: inline
aliases: ["Lunar Dragon Wyrmling"]
---
# [Lunar Dragon Wyrmling](Mechanics\bestiary\dragon/lunar-dragon-wyrmling-bam.md)
*Source: Boo's Astral Menagerie p. 35*  

Lunar dragons (also known as moon dragons or phase dragons) are capricious, xenophobic creatures that make their lairs inside desolate moons by burrowing through the rock.

Before laying eggs, a female lunar dragon stocks her lair with food; she won't leave the lair again until the eggs hatch and the offspring are old enough to fend for themselves. Lunar dragon eggs have stony shells that are pale white to light gray in color. Lunar dragons are alabaster white when they hatch and gradually turn darker as they age. Ancient moon dragons are the color of slate.

Lunar dragons enjoy depriving other creatures of treasure more than acquiring the treasure themselves. Often found among the treasures in a lunar dragon's hoard are one or more spelljamming helms (see the *Astral Adventurer's Guide*) taken from vessels that dared to invade the dragon's territory.

A lunar dragon can become incorporeal, but not to the extent that it can pass through other creatures or solid objects. In this semi-incorporeal state, roughly half of the dragon's body has a dark, indistinctly spectral form.

```statblock
"name": "Lunar Dragon Wyrmling (BAM)"
"size": "Medium"
"type": "dragon"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "15"
- !!int "12"
- !!int "16"
- !!int "6"
- !!int "10"
- !!int "9"
"speed": "40 ft., burrow 10 ft., fly 40 ft."
"saves":
  "Wisdom": !!int "2"
  "Constitution": !!int "5"
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "4"
"damage_immunities": "cold"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Draconic"
"cr": "2"
"traits":
- "desc": "The dragon can burrow through solid rock at half its burrowing speed and\
    \ leaves a 5-foot-diameter tunnel in its wake."
  "name": "Tunneler"
- "desc": "The dragon doesn't require air."
  "name": "Unusual Nature"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 3 (1d6) cold damage."
  "name": "Bite"
- "desc": "The dragon exhales a blast of frost in a 15-foot cone. Each creature in\
    \ the cone must make a DC 13 Constitution saving throw. On a failed save, the\
    \ creature takes 13 (3d8) cold damage, and its speed is halved until the end\
    \ of its next turn. On a successful save, the creature takes half as much damage,\
    \ and its speed isn't reduced."
  "name": "Cold Breath (Recharge 5-6)"
"bonus_actions":
- "desc": "The dragon becomes partially incorporeal for as long as it maintains [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ on the effect (as if concentrating on a spell). While partially incorporeal,\
    \ the dragon has resistance to bludgeoning, piercing, and slashing damage."
  "name": "Phase (2/Day)"
"source":
- "BAM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Lunar%20Dragon%20Wyrmling.webp"
```
^statblock