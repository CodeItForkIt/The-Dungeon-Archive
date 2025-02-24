---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/8
- monster/size/medium
- monster/type/monstrosity
aliases: ["Xakalonus"]
---
# Xakalonus
*Source: Grim Hollow: Lairs of Etharis p. 73*  

> [!quote]  
> 
> The Stillborn Forest crawls with these beasts, and their howls foretell even larger monsters approaching.

## Salvage

A xakalonus brain is encased in a viscous jelly which can be turned into a substance called [arcane oil](2-Mechanics/CLI/items/arcane-oil-ghloe.md) (see Appendix A of Lairs of Etharis). This oil's creation requires a proficient alchemist to spend 8 hours and 200 gp of components. They must succeed on a DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)) check to create the substance.

## Lore

- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** Xakalonus are created from wounds to the hraptnon. These creatures, though always originating in the Stillborn Forest, can be found anywhere in Etharis. They feed on the brains of creatures that use magic, then return to offer up the brain to the hraptnon.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** If magic effects but does not harm a xakalonus, the magic might heal them or power their attacks instead.  

## Statblock

```ad-statblock
title: Xakalonus
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Xakalonus.webp#token)
*Medium monstrosity, Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 75 (`10d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|17 (+3)| 9 (-1)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4
- **Senses** darkvision 120 ft., passive Perception 14
- **Languages** understands Draconic but can't speak
- **Challenge** 8

## Traits

***Magic Absorption.*** If a xakalonus succeeds on a saving throw against a magical effect that would damage it, it takes no damage. Instead, the xakalonus regains `dice:2d10|noform|avg|text(11)` (`2d10`) hit points. Alternatively, if the xakalonus is at full hit points, the next successful melee attack by the xakalonus deals an additional `dice:2d10|noform|avg|text(11)` (`2d10`) force damage.

***Magic Resistance.*** The xakalonus has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The xakalonus makes one bite and one claws attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) slashing damage.

***Sonic Bark (Recharge 5-6).*** All creatures within 30 ft. who can hear the xakalonus must succeed on a DC 14 Constitution saving throw or take `dice:4d6|noform|avg|text(14)` (`4d6`) thunder damage and be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of their next turn. Other xakalonus and the hraptnon are immune to this.
```
^statblock