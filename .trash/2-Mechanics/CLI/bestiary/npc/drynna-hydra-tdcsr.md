---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
aliases: ["Drynna Hydra"]
---
# Drynna Hydra
*Source: Tal'Dorei Campaign Setting Reborn p. 66*  

> [!note]
> This Hyrda lives in "Mooren Lake" and has gained intelligence by living for so long in the [residuum](2-Mechanics/CLI/items/residuum-tdcsr.md)-infused waters. It has an Intelligence score of 12 (+1), can speak Common, and commands a tribe of [lizardfolk](2-Mechanics/CLI/bestiary/humanoid/lizardfolk.md).

> [!note]
> See "Unfriendly Waters", a mid-level adventure hook, for more information.

---

The hydra is a reptilian horror with a crocodilian body and multiple heads on long, serpentine necks. Although its heads can be severed, the hydra magically regrows them in short order. A typical specimen has five heads. At the dawn of time, Tiamat, the Queen of Evil Dragons, slew a rival dragon god named Lernaea and cast her blood across the multiverse. Each drop that fell upon a world spawned a multi-headed hydra consumed by a hunger as great as the fallen god's hatred. Great champions are known to test their mettle against these fearsome creatures.

## Everlasting Hunger

A rapacious and gluttonous monster, a hydra snatches and tears apart its prey in a frenzy of feeding. When a hydra has cleared a territory of food and driven off any creatures smart enough to avoid it, it moves on to seek its meals elsewhere. A hydra's hunger is so great that if it can't feed, it might turn against itself, its heads attacking each other as the creature eats itself alive.

## Hardy Water Dwellers

Hydras are natural swimmers, dwelling in rivers, along lakeshores, in ocean shallows, and in wetland bogs. A hydra rarely requires shelter from the elements, so it doesn't normally have a lair. Only in colder climes are hydras drawn to the protection of sheltered caverns and ruins. When a hydra sleeps, at least one of its heads remains awake and alert, making the creature difficult to catch by surprise.

## Statblock

```ad-statblock
title: Drynna Hydra
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Drynna%20Hydra.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 172 (`15d12 + 75`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|20 (+5)|12 (+1)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6
- **Senses** darkvision 60 ft., passive Perception 16
- **Languages** Common
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

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) piercing damage.
```
^statblock