---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Eldritch Priest"]
---
# Eldritch Priest
*Source: Grim Hollow: Lairs of Etharis p. 41*  

> [!quote]  
> 
> First she spoke of a power greater than the gods. Then there was this ringing in my ears. I don't remember what happened after that, but the nightmares were terrible.

## Salvage

The touch of an Aether Kindred's dreams can taint objects with an unstable nature, particularly potions. Any potion found on the servants of these beings has a 50 percent chance to be tainted, making the potion's effects unpredictable. Someone inspecting such a potion must succeed on a DC 17 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check to identify the instability. Otherwise, the potion appears to be a normal potion of its type.

When an unstable potion is consumed, roll on the Eldritch Effects table to determine the effect of the instability, which is in addition to the potion's normal effects and can last as long as the potion does or 1 minute, whichever is longer. However, a creature can attempt a DC 13 Wisdom saving throw at the end of each of its turns, ending the instability effect on itself on a success.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** In the wake of the gods' disappearance, some turned to other ancient entities for power. Those that succeed are known as eldritch priests.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** These priests draw their power from maddening entities known as the Aether Kindred, which some arcane scholars point to as the cause of the gods' disappearance. The power granted by such creatures can produce bizarre and unpredictable effects.  
- **DC 20 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Some eldritch priests seek to awaken their new "gods" by spreading the story of the demise of members the Etharis pantheon. As more people tap into the dreams of the slumbering Kindred, the creatures begin to rouse. If they wake, the world is doomed.  

## Eldritch Effects

`dice: [](eldritch-priest-ghloe.md#^effect)`

| dice: d8 | Effect |
|----------|--------|
| 1 | The creature can't speak. |
| 2 | The creature takes `dice:1d8\|noform\|avg\|text(4)` (`1d8`) psychic damage at the start of each of its turns. |
| 3 | The creature is disoriented. It falls prone and does so again at the end of each turn it moves 5 feet or more. |
| 4 | The creature is distracted by visions and voices and has disadvantage on attack rolls and Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks. |
| 5 | The creature is unsure of itself. It can move or take an action on its turn, but not both, and it can't use reactions. |
| 6 | The creature is reckless. It has advantage on attack rolls and attack rolls against it have advantage. |
| 7 | The creature is deafened and can't see more than 30 feet away. |
| 8 | The creature is frightened of the source of this effect. If that source can't be sensed, the creature is frightened of one other random creature it can sense. |
^effect

## Statblock

```ad-statblock
title: Eldritch Priest
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Eldritch%20Priest.webp#token)
*Medium humanoid (any race), Any Non-Good alignment*

- **Armor Class** 13 ([chain shirt](2-Mechanics/CLI/items/chain-shirt.md))
- **Hit Points** 22 (`4d8 + 4`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|11 (+0)|13 (+1)|10 (+0)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Perception +4, Religion +2
- **Senses** passive Perception 14
- **Languages** any two languages
- **Challenge** 2

***Spellcasting.*** The eldritch priest is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 12, `dice:1d20+4|noform|text(+4)` to hit with spell attacks). It has the following cleric spells prepared:

**Cantrips (at will)**: [eldritch blast](2-Mechanics/CLI/spells/eldritch-blast.md), [light](2-Mechanics/CLI/spells/light.md), [sacred flame](2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1st level (4 slots)**: [bane](2-Mechanics/CLI/spells/bane.md), [Tasha's hideous laughter](2-Mechanics/CLI/spells/tashas-hideous-laughter.md), [inflict wounds](2-Mechanics/CLI/spells/inflict-wounds.md), [sleep](2-Mechanics/CLI/spells/sleep.md)

**2nd level (3 slots)**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [see invisibility](2-Mechanics/CLI/spells/see-invisibility.md), [spiritual weapon](2-Mechanics/CLI/spells/spiritual-weapon.md)

## Actions

***Greatclub.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+1|noform|avg|text(5)` (`1d8 + 1`) bludgeoning damage.

***Prophecy of Doom (Recharges after a Short or Long Rest).*** The eldritch priest chooses a point it can see within 120 feet of it and rolls on the Eldritch Effects table. Each creature within 15 feet of that point must succeed on a DC 12 Wisdom saving throw or be subjected to an eldritch effect for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock