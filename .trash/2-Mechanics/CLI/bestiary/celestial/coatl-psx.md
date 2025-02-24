---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/4
- monster/size/medium
- monster/type/celestial
aliases: ["Coatl"]
---
# Coatl
*Source: Plane Shift: Ixalan p. 35*  

The River Heralds believe that the waters of the world are divided into two spheres: the river and the sea are the lower half, with the jungle and the sky above. They believe that the sea possesses an unfathomable wisdom, the deep musings of the unspeakably ancient world. But the wisdom of the sky and the rivers is embodied in the coatls—winged serpents that twist through the air to reflect the course of rivers along the ground.

Coatls are immortal guardians of the sky, dwelling always among the clouds. The River Heralds say that they can be enticed to the ground by the earnest supplication of the wisest of merfolk shamans. Coatls are said to be wise beyond mortal measure and incapable of speaking a falsehood, so their advice is often sought in times of desperate need. The sight of a coatl is thought to foretell favorable winds—a belief that has begun to spread from the River Herald shamans to the pirates of the Brazen Coalition. Use the [couatl](2-Mechanics/CLI/bestiary/celestial/couatl.md) statistics in the "Monster Manual" for Ixalan's coatls.

```ad-statblock
title: Coatl
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Coatl.webp#token)
*Medium celestial, Lawful Good*

- **Armor Class** 19 (natural armor)
- **Hit Points** 97 (`13d8 + 39`)
- **Speed** 30 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|20 (+5)|17 (+3)|18 (+4)|20 (+5)|18 (+4)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +5, Wisdom +7, Charisma +6
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 15
- **Damage Resistances** radiant
- **Damage Immunities** psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** all, telepathy 120 ft.
- **Challenge** 4

## Traits

***Magic Weapons.*** The coatl's weapon attacks are magical.

***Shielded Mind.*** The coatl is immune to scrying and to any effect that would sense its emotions, read its thoughts, or detect its location.

***Innate Spellcasting.*** The coatl's spellcasting ability is Charisma (spell save DC 14). It can innately cast the following spells, requiring only verbal components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md)

**1/day each**: [dream](2-Mechanics/CLI/spells/dream.md), [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md), [scrying](2-Mechanics/CLI/spells/scrying.md)

**3/day each**: [bless](2-Mechanics/CLI/spells/bless.md), [create food and water](2-Mechanics/CLI/spells/create-food-and-water.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md), [protection from poison](2-Mechanics/CLI/spells/protection-from-poison.md), [sanctuary](2-Mechanics/CLI/spells/sanctuary.md), [shield](2-Mechanics/CLI/spells/shield.md)

## Actions

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) piercing damage, and the target must succeed on a DC 13 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 24 hours. Until this poison ends, the target is [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious). Another creature can use an action to shake the target awake.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 10 ft., one Medium or smaller creature. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the coatl can't constrict another target.

***Change Shape.*** The coatl magically polymorphs into a humanoid or beast that has a challenge rating equal to or less than its own, or back into its true form. It reverts to its true form if it dies. Any equipment it is wearing or carrying is absorbed or borne by the new form (the coatl's choice).

In a new form, the coatl retains its game statistics and ability to speak, but its AC, movement modes, Strength, Dexterity, and other actions are replaced by those of the new form, and it gains any statistics and capabilities (except class features, legendary actions, and lair actions) that the new form has but that it lacks. If the new form has a bite attack, the coatl can use its bite in that form.
```
^statblock