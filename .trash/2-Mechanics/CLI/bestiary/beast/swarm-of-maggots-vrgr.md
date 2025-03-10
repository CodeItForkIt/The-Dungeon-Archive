---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/vrgr
- monster/cr/2
- monster/size/medium
- monster/type/beast
aliases: ["Swarm of Maggots"]
---
# Swarm of Maggots
*Source: Van Richten's Guide to Ravenloft p. 247*  

Base creatures are among the first to respond to sinister forces at work in a land. As nefarious powers grip an area, populations of maggots, scarabs, and similar scavenging insects explode and become aggressive predators. Roll on the Swarm Behavior table to see how such swarms might manifest.

**Swarm Behavior**

`dice: [](swarm-of-maggots-vrgr.md#^swarm-behavior)`

| dice: d4 | Behavior |
|----------|----------|
| 1 | Crawls on walls in a vaguely bipedal shape |
| 2 | Makes skittering noises that sound like whispered chanting |
| 3 | Skeletal visages, giant eyes, or the faces of nearby creatures appear in relief amid its mass |
| 4 | Occupies and animates a corpse or other debris as if it were alive |
^swarm-behavior

```ad-statblock
title: Swarm of Maggots
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Swarm%20of%20Maggots.webp#token)
*Medium beast, Unaligned*

- **Armor Class** 11
- **Hit Points** 22 (`5d8`)
- **Speed** 20 ft., swim 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 3 (-4)|12 (+1)|10 (+0)| 1 (-5)| 7 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 10 ft., passive Perception 8
- **Damage Resistances** bludgeoning, piercing, slashing
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 2

## Traits

***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny maggot. The swarm can't regain hit points or gain temporary hit points.

## Actions

***Infestation.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 0 ft., one target in the swarm's space. *Hit:* `dice:4d4|noform|avg|text(10)` (`4d4`) piercing damage, or `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage if the swarm has half of its hit points or fewer. A creature damaged by the swarm must succeed on a DC 12 Constitution saving throw or contract a disease.

Each time the diseased creature finishes a long rest, roll a `dice:d6|noform|avg` (`d6`) to determine the disease's effect:

- **1-2.** The creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until it finishes a long rest.  
- **3-4.** The creature's hit point maximum decreases by `dice:2d4|noform|avg|text(5)` (`2d4`), and the reduction can't be removed until the disease ends. The creature dies if its hit point maximum drops to 0.  
- **5-6.** The creature has disadvantage on ability checks and attack rolls until it finishes its next long rest.  

    The disease lasts until it's removed by magic or until the creature rolls the same random effect for the disease two long rests in a row.  
```
^statblock