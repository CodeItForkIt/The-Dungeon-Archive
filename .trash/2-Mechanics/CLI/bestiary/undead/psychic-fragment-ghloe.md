---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/0
- monster/size/tiny
- monster/type/undead
aliases: ["Psychic Fragment"]
---
# Psychic Fragment
*Source: Grim Hollow: Lairs of Etharis p. 15*  

> [!quote]  
> 
> It appeared from the darkness: a faceless wraith whose outstretched arms sought purchase on my mortal frame. In desperation, I cried to my companions for aid, but my voice was silent. When it stole my words, I knew my doom was at hand.

## Salvage

The bones of a mortal transformed into a scream thief remain imbued with its undead aura. A skilled magic item crafter using 200 gp of magical regents, and spending at least 5 days of effort, can create a [wand of silence](2-Mechanics/CLI/items/wand-of-silence-ghloe.md) (see Appendix A of Lairs of Etharis) if they succeed on a DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check.

A spellcaster can capture a psychic fragment's essence before it dissipates after death. The spellcaster requires a container worth at least 100 gp. Anyone who succeeds on a DC 13 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check can capture a portion of the defeated psychic fragment. The container can store up to 10 hit die worth of undead essence for 8 hours before they dissipate.

As an action, a container holding this spiritual essence can be thrown up to 20 feet, shattering on impact. All creatures within 5 feet of the broken container must make a DC 12 Constitution saving throw. A failed saving throw results in `dice:1d4|noform|avg` (`1d4`) necrotic damage per hit die of essence stored, while a success deals half as much damage.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** The scream thief is immune to necrotic and poison. The incorporeal nature of psychic fragments makes them resistant to nonmagical weapons.  
- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** The touch of a scream thief drains life that magic cannot heal; only time and rest can.  

A scream thief remains trapped in its place of death, often accompanied by spirit fragments of the creatures it has killed.

## Statblock

```ad-statblock
title: Psychic Fragment
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Psychic%20Fragment.webp#token)
*Tiny undead, Chaotic Evil*

- **Armor Class** 12
- **Hit Points** 3 (`1d4 + 1`)
- **Speed** 0 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 3 (-4)|15 (+2)|13 (+1)| 2 (-4)|12 (+1)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** acid; cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** can repeat one phrase it knew in life
- **Challenge** 0

## Traits

***Incorporeal Movement.*** The psychic fragment can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Mimicry.*** The psychic fragment can mimic a single word or phrase it spoke in life. A creature that hears the sounds can tell they are imitations with a successful DC 11 Wisdom ([Insight](2-Mechanics/CLI/rules/skills.md#Insight)) check.

## Actions

***Withering Touch.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4|noform|avg|text(2)` (`1d4`) necrotic damage.
```
^statblock