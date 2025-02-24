---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/6
- monster/size/large
- monster/type/elemental
statblock: inline
aliases: ["Mjork Asher"]
---
# [Mjork Asher](Mechanics\bestiary\elemental/mjork-asher-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 71*  

> [!quote]  
> 
> Is it just me, or does the darkness seem thicker? And did it just get really warm in here?

## Salvage

Within every mjork is a heart of ash hardened into smoky crystal. This crystal might already be broken in the remains of a slain mjork, making it useless. An intact crystal can be broken or hurled at a point up to 60 feet away as an action. When it breaks, which it does upon landing if hurled, the crystal releases a 20-foot-radius sphere of sooty smoke, centered on a point in the breaker's space or on the point where the crystal landed. The smoke spreads around corners, and its area is heavily obscured. It lasts for 1 minute, but a moderate wind (at least 10 miles per hour) disperses it in 4 rounds. A strong wind (20 or more miles per hour) disperses the smoke in 1 round. These crystals sell for 15 gp or more each.

The smaller crystals from sootlings or broken mjork crystals are like smoky quartz. These gems can be worth from 1 sp to 1 gp each, or more to collectors who believe they are mjork crystals. Someone who polishes them using jeweler's tools can increase their value as semiprecious stones.

## Lore

- **DC 10 Intelligence ([Nature](Mechanics/Rules/skills.md#Nature)).** Mjorks are made from earth and fire clashing together. These elementals often dwell near volcanoes.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** Mjorks are vulnerable to thunder damage, which cracks their rocky skin. They can also sense through smoke as if the haze provided them blindsight.  

```statblock
"name": "Mjork Asher (GHLoE)"
"size": "Large"
"type": "elemental"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"stats":
- !!int "15"
- !!int "15"
- !!int "16"
- !!int "7"
- !!int "13"
- !!int "7"
"speed": "30 ft."
"damage_vulnerabilities": "thunder"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Ignan, Terran"
"cr": "6"
"traits":
- "desc": "A creature that takes fire damage from a mjork asher's attacks must make\
    \ a DC 14 Constitution saving throw or be [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ until the end of the mjork's next turn."
  "name": "Blinding Soot"
- "desc": "A creature that touches the mjork asher or hits it with a melee attack\
    \ while within 5 feet of it takes 7 (2d6) fire damage."
  "name": "Fiery Body"
- "desc": "A mjork asher in contact with smoke has blindsight in that smoke's area\
    \ in a radius of up to 120 feet."
  "name": "Smoke Sense"
- "desc": "While the mjork asher has 41 or more hit points, smoke renders a sphere\
    \ within 20 feet of it heavily obscured. This smoke goes around corners. Even\
    \ while the mjork has 40 or fewer hit points, tendrils of this smoke extend to\
    \ 60 feet from the mjork, providing smoke for the Smoke Sense of all mjorks. However,\
    \ the whole shroud dissipates during any round the mjork is exposed to moderate\
    \ (at least 10 miles per hour) or stronger wind."
  "name": "Smoke Shroud"
- "desc": "For every 5 feet the mjork asher moves in water, or for every gallon of\
    \ water splashed on it, it takes 1 cold damage."
  "name": "Water Susceptibility"
"actions":
- "desc": "The mjork asher makes two attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) bludgeoning damage and 7 (2d6) fire damage and Blinding Soot."
  "name": "Slam"
- "desc": "Ranged Spell Attack: +5 to hit, ranged 30/60 ft., one target. Hit:\
    \ 12 (3d6 + 2) fire damage and Blinding Soot."
  "name": "Hurl Soot"
- "desc": "The mjork asher chooses a point within 60 feet of it that it can sense.\
    \ Smoke fills a 20-foot radius sphere centered on that point. The sphere spreads\
    \ around corners, and its area is heavily obscured. This smoke lasts until the\
    \ start of the mjork's next turn or until a wind of moderate or greater speed\
    \ (at least 10 miles per hour) disperses it. Unless dispersed before the start\
    \ of the mjork's next turn, a sootling swarm forms in a space in the area, favoring\
    \ a space a creature hostile to the mjork occupies. The swarm takes its turn just\
    \ after the mjork and obeys the mjork's verbal commands (no action for the mjork).\
    \ If issued no commands, the swarm acts independently, often attacking a creature\
    \ that isn't its ally. The swarm can survive indefinitely after being created."
  "name": "Create Sootlings (1/Day)"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Mjork%20Asher.webp"
```
^statblock