---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
statblock: inline
aliases: ["Hydra"]
---
# [Hydra](Mechanics\bestiary\monstrosity/hydra-psk.md)
*Source: Plane Shift: Kaladesh p. 30*  

Hydras are giant lizards resembling iguanas, with multiple heads set atop long, snakelike necks. Aether traces whorling patterns through their scales, shapes the crests running down their necks and tails, and glows blue within the skin under their chins. Most hydras have five or six heads, but small hydras with as few as three heads—as well as enormous specimens with eight or more—have been seen in the deep forests far from Ghirapur.

Hydras are fierce predators, favoring prey that has absorbed large quantities of aether from the environment. This taste for aether also leads them to devour aether-powered machines whenever they encounter such devices, from thopters to automatons. In the remote wilderness near Peema where hydras are plentiful, such altercations are rarely an issue. But in the rare event of a hydra coming too close to civilization—or even wandering into one of Ghirapur's greenbelts—they can cause widespread destruction in their hunt for aether.

Use the [hydra](Mechanics/bestiary/monstrosity/hydra.md) statistics in the "Monster Manual".

```statblock
"name": "Hydra (PSK)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"stats":
- !!int "20"
- !!int "12"
- !!int "20"
- !!int "2"
- !!int "10"
- !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  "Perception": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "8"
"traits":
- "desc": "The hydra can hold its breath for 1 hour."
  "name": "Hold Breath"
- "desc": "The hydra has five heads. While it has more than one head, the hydra has\
    \ advantage on saving throws against being [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [charmed](Mechanics/Rules/conditions.md#Charmed), [deafened](Mechanics/Rules/conditions.md#Deafened),\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [stunned](Mechanics/Rules/conditions.md#Stunned),\
    \ and knocked [unconscious](Mechanics/Rules/conditions.md#Unconscious).\n\nWhenever\
    \ the hydra takes 25 or more damage in a single turn, one of its heads dies. If\
    \ all its heads die, the hydra dies.\n\nAt the end of its turn, it grows two heads\
    \ for each of its heads that died since its last turn, unless it has taken fire\
    \ damage since its last turn. The hydra regains 10 hit points for each head regrown\
    \ in this way."
  "name": "Multiple Heads"
- "desc": "For each head the hydra has beyond one, it gets an extra reaction that\
    \ can be used only for opportunity attacks."
  "name": "Reactive Heads"
- "desc": "While the hydra sleeps, at least one of its heads is awake."
  "name": "Wakeful"
"actions":
- "desc": "The hydra makes as many bite attacks as it has heads."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 10\
    \ (1d10 + 5) piercing damage."
  "name": "Bite"
"source":
- "PSK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Hydra.webp"
```
^statblock