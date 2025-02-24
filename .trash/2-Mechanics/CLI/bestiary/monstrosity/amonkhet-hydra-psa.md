---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
aliases: ["Amonkhet Hydra"]
---
# Amonkhet Hydra
*Source: Plane Shift: Amonkhet p. 35*  

The hydras of Amonkhet have heads like those of a cobra. A successful bite attack from one of these heads deals `dice:1d4+5|noform|avg|text(7)` (`1d4 + 5`) piercing damage, and the target must make a DC 16 Constitution saving throw, taking `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage on a failed save, or half as much damage on a successful one.

## The Desert Lands

The desolate wilderness beyond the protection of the Hekma is largely uncharted. Immediately beyond the protective veil is a chaotic dune sea called Shefet, the Scouring Sands. The desert wears away at the edges of the fertile lands surrounding Naktamun, serving as a constant reminder that only the bounty and protection of the God-Pharaoh stand between the people of the city-state and a grisly death in the sands beyond. Beyond Shefet are parched, cracked expanses called Ramunap, the Broken Lands. The ruins of ancient civilizations are said to lie in the Broken Lands, though no one has ever explored such ruins and returned to Naktamun to tell of them.

## Statblock

```ad-statblock
title: Amonkhet Hydra
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Amonkhet%20Hydra.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 172 (`15d12 + 75`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|20 (+5)| 2 (-4)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6
- **Senses** darkvision 60 ft., passive Perception 16
- **Languages** —
- **Challenge** 8

## Traits

***Hold Breath.*** The hydra can hold its breath for 1 hour.

***Multiple Heads.*** The hydra has five heads. While it has more than one head, the hydra has advantage on saving throws against being [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), and knocked [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious).

Whenever the hydra takes 25 or more damage in a single turn, one of its heads dies. If all its heads die, the hydra dies.

At the end of its turn, it grows two heads for each of its heads that died since its last turn, unless it has taken fire damage since its last turn. The hydra regains 10 hit points for each head regrown in this way.

***Reactive Heads.*** For each head the hydra has beyond one, it gets an extra reaction that can be used only for opportunity attacks.

***Wakeful.*** While the hydra sleeps, at least one of its heads is awake.

## Actions

***Multiattack.*** The hydra makes as many bite attacks as it has heads.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d4+5|noform|avg|text(7)` (`1d4 + 5`) piercing damage, and the target must make on a DC 16 Constitution saving throw, taking `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock