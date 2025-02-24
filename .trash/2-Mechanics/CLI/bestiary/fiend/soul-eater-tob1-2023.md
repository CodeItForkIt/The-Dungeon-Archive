---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/any
- monster/environment/planar
- monster/size/medium
- monster/type/fiend
aliases: ["Soul Eater"]
---
# Soul Eater
*Source: Tome of Beasts 1 (2023 Edition) p. 336*  

*The creature walks on crab-like legs, carrying a fleshy, ectoplasm-filled mass on its back.*

## Merchants from the Lower Planes

Soul eaters are soul-collecting fiends from the Lower Planes where they freely barter for prey. When a soul eater dies, the souls it carried are released and returned to their bodies or to their appropriate final destinations. Regardless, a dead soul eater has no souls for the demons and devils who value souls as currency. This gives soul eaters a measure of safety and power in the Lower Planes, and many of them operate as neutral merchants among other fiends.

## Hatred of the Sun God

Soul eaters bear a particular antipathy for followers of the deities of the sun. They go to great lengths to kill any such deity's clergy, even defying the wishes of their fiendish superiors on occasion.

## Statblock

```ad-statblock
title: Soul Eater
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Soul%20Eater.webp#token)
*Medium fiend, Neutral Evil*

- **Armor Class** 16
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|22 (+6)|17 (+3)|12 (+1)|11 (+0)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +9, Constitution +6, Charisma +3
- **Skills** Intimidation +3, Perception +3, Stealth +9
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 7

## Traits

***Magic Resistance.*** The soul eater has advantage on saving throws against spells and other magical effects.

***Soul Sense.*** The soul eater can pinpoint the location of creatures that have souls within 60 feet of it and can sense the general direction of such creatures within 1 mile of it.

## Actions

***Multiattack.*** The soul eater makes two Claw attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage.

***Hasten Consumption (Recharge 5-6).*** The soul eater emits a wave of psychic energy to hasten the demise of nearby creatures, bringing them one step closer to having their souls consumed. Each creature within 20 feet of the soul eater must make a DC 14 Charisma saving throw, taking `dice:9d6|noform|avg|text(31)` (`9d6`) psychic damage on a failed save, or half as much damage on a successful one. A creature reduced to below half its hp maximum by this effect has disadvantage on the saving throw against the soul eater's Soul Drain for 1 minute.

## Reactions

***Soul Drain.*** When the soul eater reduces a target to 0 hp, the soul eater consumes that creature's soul. The victim must succeed on a DC 14 Constitution saving throw or immediately die as the soul eater consumes its soul. A creature killed in this way can be restored to life only by means of a true resurrection or a [wish](2-Mechanics/CLI/spells/wish.md) spell. If the soul eater is killed within 120 feet of the body of a soul it consumed and the victim has been dead for no longer than 1 minute, the victim's soul returns to the body and returns to life, [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) and stable with 0 hp.
```
^statblock

## Environment

any, planar