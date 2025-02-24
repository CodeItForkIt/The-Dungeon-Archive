---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
aliases: ["Vitebriate"]
---
# Vitebriate
*Source: Grim Hollow: Lairs of Etharis p. 21*  

> [!quote]  
> 
> I swear I've seen that kid before, years ago, when I was just a kid myself! But she hasn't aged a day.

## Salvage

When a vitebriate dies, it crumbles into a swarm of harmless crawling roaches.

If these roaches are mixed with seawater, a *potion of false life* results. The creation of this potion can be completed with a successful DC 10 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check by someone proficient with an herbalism kit. This process takes 1 hour.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** A vitebriate can only have a single thrall at a time and can transfer some of its damage to its thrall.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Vitebriates are immune to poison and disease, and they require a thrall to stay alive.  

## Statblock

```ad-statblock
title: Vitebriate
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Vitebriate.webp#token)
*Medium monstrosity, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 52 (`7d8 + 21`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|14 (+2)|16 (+3)|12 (+1)|12 (+1)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 20
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** languages it knew previously
- **Challenge** 2

## Traits

***Unnatural Life.*** Vitebriates are immune to the effects of old age and death by natural causes.

***Vitebriance.*** While on the same plane of existence as a person [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the vitebriate's Dominate Person action, the vitebriate may leech 1 hp per day permanently from the thrall. When a thrall is reduced to 0 hp through this process, it is killed. Drained hit points are regained after 7 days of rest.

## Actions

***Multiattack.*** The vitebriate makes two melee attacks.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft. or range 20/60 ft., one creature. *Hit:* `dice:1d4+2|noform|avg|text(4)` (`1d4 + 2`) piercing damage.

***Dominate Person.*** A vitebriate can target a single humanoid with dominate person as the spell, with the following differences: once the vitebriate has chosen the target, it can use this ability only on the chosen target (until the next day when it can choose a different target and drop the focus on the current target). The spell does not require [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) but is broken if the vitebriate is knocked [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) involuntarily or killed (though not if it trances or sleeps). If the person has been [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) for at least an hour, damage does not force a new saving throw.

## Reactions

***Life Shield (1/Day).*** The vitebriate uses its psychic link with its thrall to transfer all damage it would take to its thrall. Damage that goes beyond what would kill the thrall is dealt to the vitebriate.
```
^statblock