---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/5
- monster/size/medium
- monster/type/elemental
aliases: ["Murder Comet"]
---
# Murder Comet
*Source: Boo's Astral Menagerie p. 38*  

Evil spellcasters create murder comets by combining the essence of earth elementals with that of fire elementals. A murder comet looks like a screaming stone head wreathed in flame. It trails fire behind it as it flies through Wildspace, either singly or in a posse with other murder comets, looking for ships, crews, and other unsuspecting targets to destroy.

A murder comet's creator can bind their spirit to the comet. In this form, the comet's creator becomes ageless and immortal, free to race across Wildspace without need for air, sleep, or sustenance. The murder comet's face takes on the appearance of its creator's, and its statistics change as follows:

- Replace the comet's Intelligence, Wisdom, and Charisma scores with those of its creator.  
- Replace the comet's alignment and languages with those of its creator.  

```ad-statblock
title: Murder Comet
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Murder%20Comet.webp#token)
*Medium elemental, typically  Neutral Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 66 (`7d8 + 35`)
- **Speed** 0 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|15 (+2)|20 (+5)| 6 (-2)|10 (+0)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 240 ft., passive Perception 10
- **Damage Immunities** fire, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Ignan, Terran
- **Challenge** 5

## Traits

***Explode.*** When the comet drops to 0 hit points, it explodes in a 20-foot-radius sphere centered on itself. Each creature in the sphere must make a DC 16 Dexterity saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) fire damage on a failed save, or half as much damage on a successful one.

***Flyby.*** The comet doesn't provoke opportunity attacks when it flies out of an enemy's reach.

***Illumination.*** The comet sheds bright light in a 30-foot radius and dim light for an additional 30 feet.

***Siege Monster.*** The comet deals double damage to objects and structures.

***Unusual Nature.*** The comet doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The comet makes one Slam attack and one Spit Fire attack.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) fire damage.

***Spit Fire.*** *Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 60 ft., one target. *Hit:* `dice:2d10+2|noform|avg|text(13)` (`2d10 + 2`) fire damage.
```
^statblock