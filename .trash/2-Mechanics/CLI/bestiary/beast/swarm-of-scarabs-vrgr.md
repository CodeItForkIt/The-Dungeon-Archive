---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/vrgr
- monster/cr/3
- monster/size/medium
- monster/type/beast
aliases: ["Swarm of Scarabs"]
---
# Swarm of Scarabs
*Source: Van Richten's Guide to Ravenloft p. 247*  

Base creatures are among the first to respond to sinister forces at work in a land. As nefarious powers grip an area, populations of maggots, scarabs, and similar scavenging insects explode and become aggressive predators. Roll on the Swarm Behavior table to see how such swarms might manifest.

**Swarm Behavior**

`dice: [](swarm-of-scarabs-vrgr.md#^swarm-behavior)`

| dice: d4 | Behavior |
|----------|----------|
| 1 | Crawls on walls in a vaguely bipedal shape |
| 2 | Makes skittering noises that sound like whispered chanting |
| 3 | Skeletal visages, giant eyes, or the faces of nearby creatures appear in relief amid its mass |
| 4 | Occupies and animates a corpse or other debris as if it were alive |
^swarm-behavior

```ad-statblock
title: Swarm of Scarabs
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Swarm%20of%20Scarabs.webp#token)
*Medium beast, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 27 (`5d8 + 5`)
- **Speed** 30 ft., burrow 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 3 (-4)|14 (+2)|13 (+1)| 1 (-5)|12 (+1)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** tremorsense 60 ft., passive Perception 11
- **Damage Resistances** bludgeoning, piercing, slashing
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** —
- **Challenge** 3

## Traits

***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny scarab. The swarm can't regain hit points or gain temporary hit points.

***Skeletonize.*** If the swarm starts its turn in the same space as a dead creature that is Large or smaller, the corpse is destroyed, leaving behind only equipment and bones (or exoskeleton).

***Spider Climb.*** The swarm can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Ravenous Bites.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 0 ft., one target in the swarm's space. *Hit:* `dice:4d6|noform|avg|text(14)` (`4d6`) piercing damage, or `dice:2d6|noform|avg|text(7)` (`2d6`) piercing damage if the swarm has half of its hit points or fewer. If the target is a creature, scarabs burrow into its body, and the creature takes `dice:1d6|noform|avg|text(3)` (`1d6`) piercing damage at the start of each of its turns. Any creature can use an action to kill or remove the scarabs with fire or a weapon that deals piercing damage, causing 1 damage of the appropriate type to the target. A creature reduced to 0 hit points by the swarm's piercing damage dies.
```
^statblock