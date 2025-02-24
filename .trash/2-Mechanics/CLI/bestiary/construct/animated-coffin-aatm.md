---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aatm
- monster/cr/3
- monster/size/large
- monster/type/construct
aliases: ["Animated Coffin"]
---
# Animated Coffin
*Source: Adventure Atlas: The Mortuary*  

Animated coffins are heavy, macabre Constructs designed to ferry the dead to places of rest. They waddle the Mortuary's halls unbothered, scooping up corpses and carrying them to the next stage of the funerary process.

An animated coffin has an array of spidery metal legs it uses to skitter along steep inclines, walls, and ceilings, and the coffin's spacious interior bristles with retractable spikes. Like their inanimate counterparts, animated coffins range from plain wooden boxes with simple fittings to elaborate, gilded sarcophagi and reverent, fabric-lined caskets.

Beyond the City of Doors, animated coffins serve similar—albeit less industrial—roles. Natural ambushers and tireless sentries, animated coffins guard ancient necropolises, family crypts, and the lairs of powerful Undead. A cautious vampire might sleep in an animated coffin to evade hunters during the day, while a necromancer might enlist animated coffins to conscript corpses from faraway settlements into an Undead army.

Animated coffins are rarely empty. The Animated Coffin Contents table presents some contents an animated coffin might contain when encountered.

`dice: [](animated-coffin-aatm.md#^contents)`

| dice: d6 | Contents |
|----------|----------|
| 1 | `dice:1d4\\|noform\\|avg` (`1d4`) swarm of bats |
| 2 | `dice:1d4\\|noform\\|avg` (`1d4`) skeletons packed like sardines |
| 3 | A groaning mummy |
| 4 | A patch of yellow mold (see the Dungeon Master's Guide) |
| 5 | A slumbering vampire spawn |
| 6 | A portal to the Path of Graves (detailed in Adventure Atlas: The Mortuary) |
^contents

```ad-statblock
title: Animated Coffin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AATM/Animated%20Coffin.webp#token)
*Large construct, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 60 (`8d10 + 16`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|15 (+2)| 3 (-4)|11 (+0)| 3 (-4)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (can't see beyond this radius), passive Perception 10
- **Damage Immunities** poison, psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 3

## Traits

***False Appearance.*** If the animated coffin is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the coffin move or act, that creature must succeed on a DC 18 Intelligence ([Investigation](2-Mechanics/CLI/rules/skills.md#Investigation)) check to discern that the coffin is animate.

***Spider Climb.*** The animated coffin can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The animated coffin makes two Slam attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) bludgeoning damage.

***Entrap.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one Large or smaller creature. *Hit:* The target has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 13). Until this grapple ends, if the target is not an Undead, the target has the [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) condition and takes `dice:4d6|noform|avg|text(14)` (`4d6`) piercing damage at the start of each of its turns. The animated coffin can grapple only one creature at a time.
```
^statblock