---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/1
- monster/size/medium
- monster/type/monstrosity
aliases: ["Harpy"]
---
# Harpy
*Source: Plane Shift: Ixalan p. 36*  

Harpies are the mortal servants of demons, and they resemble them in their general features. Their faces are like those of owls, and they have large, feathered wings that suggest their corrupt connection to the Sun Empire—or perhaps their heritage as sirens who were corrupted by the evil of the demons. Utterly nasty in temperament, harpies inhabit many of the islands in both the Stormwreck Sea and the Inner Sea, and dwell on high cliffs on the mainland of Ixalan. Their filthy bodies carry disease that they can spread through their bite.

Use the [harpy](2-Mechanics/CLI/bestiary/monstrosity/harpy.md) statistics in the "Monster Manual" for Ixalan's harpies, but replace the club attack with a bite attack.

## Night Terrors

The legends of the Sun Empire are populated with the enemies of the sun—terrible monsters that threaten to devour its light and undo its work. Unfortunately for the people of Ixalan, these are not just creatures of legend but real monsters with supernatural power, lurking in the darkness of night and the shadows of ancient ruins and crypts.

## Statblock

```ad-statblock
title: Harpy
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Harpy.webp#token)
*Medium monstrosity, Chaotic Evil*

- **Armor Class** 11
- **Hit Points** 38 (`7d8 + 7`)
- **Speed** 20 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|13 (+1)|12 (+1)| 7 (-2)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 10
- **Languages** Common
- **Challenge** 1

## Actions

***Multiattack.*** The harpy makes two attacks: one with its claws and one with its bite.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+1|noform|avg|text(6)` (`2d4 + 1`) slashing damage.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) slashing damage. If the target is a creature, it must succeed on a DC 11 Constitution saving throw or contract a disease. Until the disease is cured, the target can't regain hit points except by magical means, and the target's hit point maximum decreases by `dice:1d6|noform|avg|text(3)` (`1d6`) every 24 hours. If the target's hit point maximum drops to 0 as a result of this disease, the target dies.

***Luring Song.*** The harpy sings a magical melody. Every humanoid and giant within 300 feet of the harpy that can hear the song must succeed on a DC 11 Wisdom saving throw or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) until the song ends. The harpy must take a bonus action on its subsequent turns to continue singing. It can stop singing at any time. The song ends if the harpy is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated).

While [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the harpy, a target is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and ignores the songs of other harpies. If the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target is more than 5 feet away from the harpy, the target must move on its turn toward the harpy by the most direct route. It doesn't avoid opportunity attacks, but before moving into damaging terrain, such as lava or a pit, and whenever it takes damage from a source other than the harpy, a target can repeat the saving throw. A creature can also repeat the saving throw at the end of each of its turns. If a creature's saving throw is successful, the effect ends on it.

A target that successfully saves is immune to this harpy's song for the next 24 hours.
```
^statblock