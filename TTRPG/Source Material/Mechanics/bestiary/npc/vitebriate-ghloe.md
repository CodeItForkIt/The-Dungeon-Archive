---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Vitebriate"]
---
# [Vitebriate](Mechanics\bestiary\npc/vitebriate-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 21*  

> [!quote]  
> 
> I swear I've seen that kid before, years ago, when I was just a kid myself! But she hasn't aged a day.

## Salvage

When a vitebriate dies, it crumbles into a swarm of harmless crawling roaches.

If these roaches are mixed with seawater, a *potion of false life* results. The creation of this potion can be completed with a successful DC 10 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)) check by someone proficient with an herbalism kit. This process takes 1 hour.

## Lore

- **DC 10 Intelligence ([History](Mechanics/Rules/skills.md#History)).** A vitebriate can only have a single thrall at a time and can transfer some of its damage to its thrall.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** Vitebriates are immune to poison and disease, and they require a thrall to stay alive.  

```statblock
"name": "Vitebriate (GHLoE)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"stats":
- !!int "11"
- !!int "14"
- !!int "16"
- !!int "12"
- !!int "12"
- !!int "16"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [petrified](Mechanics/Rules/conditions.md#Petrified),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 20"
"languages": "languages it knew previously"
"cr": "2"
"traits":
- "desc": "Vitebriates are immune to the effects of old age and death by natural causes."
  "name": "Unnatural Life"
- "desc": "While on the same plane of existence as a person [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ by the vitebriate's Dominate Person action, the vitebriate may leech 1 hp per\
    \ day permanently from the thrall. When a thrall is reduced to 0 hp through this\
    \ process, it is killed. Drained hit points are regained after 7 days of rest."
  "name": "Vitebriance"
"actions":
- "desc": "The vitebriate makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one creature. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "A vitebriate can target a single humanoid with dominate person as the spell,\
    \ with the following differences: once the vitebriate has chosen the target, it\
    \ can use this ability only on the chosen target (until the next day when it can\
    \ choose a different target and drop the focus on the current target). The spell\
    \ does not require [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ but is broken if the vitebriate is knocked [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ involuntarily or killed (though not if it trances or sleeps). If the person\
    \ has been [charmed](Mechanics/Rules/conditions.md#Charmed) for at least an hour,\
    \ damage does not force a new saving throw."
  "name": "Dominate Person"
"reactions":
- "desc": "The vitebriate uses its psychic link with its thrall to transfer all damage\
    \ it would take to its thrall. Damage that goes beyond what would kill the thrall\
    \ is dealt to the vitebriate."
  "name": "Life Shield (1/Day)"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Vitebriate.webp"
```
^statblock