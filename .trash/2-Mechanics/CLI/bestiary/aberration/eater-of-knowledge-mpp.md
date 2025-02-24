---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/6
- monster/size/large
- monster/type/aberration
aliases: ["Eater of Knowledge"]
---
# Eater of Knowledge
*Source: Morte's Planar Parade p. 29, Sigil and the Outlands, Turn of Fortune's Wheel*  

Originally created by the mind flayer god-brain Ilsensine and now produced by some of that god's followers, eaters of knowledge are lumbering, bipedal masses of squelching muscles and exposed brain matter. These rugose hulks collect information from others by devouring brains before returning to their masters with delicious secrets. Unlike illithids, which overwhelm their foes with psionic power, eaters of knowledge use their physical strength to hold prey while burly feeding tentacles crack free their victims' brains. Consuming brains fuels these brutes' psionic power, making eaters of knowledge deadlier with each brain devoured.

```ad-statblock
title: Eater of Knowledge
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Eater%20of%20Knowledge.webp#token)
*Large aberration, typically  Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 102 (`12d10 + 36`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|10 (+0)|17 (+3)|18 (+4)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +7, Intelligence +7
- **Skills** Arcana +7, Perception +6
- **Senses** passive Perception 16
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** telepathy 120 ft.
- **Challenge** 6

## Traits

***Brains Devoured.*** When the eater of knowledge is first encountered, roll `dice:1d10|noform|avg` (`1d10`) to determine the number of brains it has already consumed.

***Magic Resistance.*** The eater of knowledge has advantage on saving throws against spells and other magical effects.

***Spellcasting (Psionics).*** The eater of knowledge casts one of the following spells, requiring no spell components and using Intelligence as its spellcasting ability (spell save DC 15). It must have consumed the requisite number of brains to cast the spell, as indicated:

**1/day each**: [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only, 0 brains), [detect magic](2-Mechanics/CLI/spells/detect-magic.md) (1 brain), [silent image](2-Mechanics/CLI/spells/silent-image.md) (2 brains), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (3 brains), [hypnotic pattern](2-Mechanics/CLI/spells/hypnotic-pattern.md) (4 brains), [major image](2-Mechanics/CLI/spells/major-image.md) (5 brains), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md) (6 brains), [arcane eye](2-Mechanics/CLI/spells/arcane-eye.md) (7 brains), [mislead](2-Mechanics/CLI/spells/mislead.md) (8 brains), [greater invisibility](2-Mechanics/CLI/spells/greater-invisibility.md) (9 brains), [mass suggestion](2-Mechanics/CLI/spells/mass-suggestion.md) (10 or more brains)

## Actions

***Multiattack.*** The eater of knowledge makes two Slam attacks. If both attacks hit the same creature and the target is Large or smaller, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14) and must succeed on a DC 15 Intelligence saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the grapple ends.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) bludgeoning damage.

***Extract Brain.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one Humanoid with the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition. *Hit:* `dice:10d8|noform|avg|text(45)` (`10d8`) piercing damage. If this damage reduces the target to 0 hit points, the eater of knowledge kills the target by extracting and consuming its brain.
```
^statblock