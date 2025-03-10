---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/12
- monster/environment/desert
- monster/environment/forest
- monster/environment/underdark
- monster/size/huge
- monster/type/monstrosity
aliases: ["Yuan-ti Anathema"]
---
# Yuan-ti Anathema
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 272*  

As part of their quest for godhood, a yuan-ti abomination might perform a ritual that, if successful, transforms them into an even greater form: a yuan-ti anathema. This ritual demands the sacrifice of hundreds of snakes and requires the abomination to bathe in the blood of their enemies. The transformation is quick but painful.

Anathemas consider themselves demigods on the path to greater divinity. They demand obeisance from weaker creatures and use every resource at their disposal to war against neighbors, seeking the captives, sacrifices, glory, and riches the anathemas believe they need to achieve true divinity.

Anathemas don't age, allowing them to pursue their goals until the end of days. Truly powerful ones might rule multiple yuan-ti cities and bring entire regions under their control.

```ad-statblock
title: Yuan-ti Anathema
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Yuan-ti%20Anathema.webp#token)
*Huge monstrosity, Typically  Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 189 (`18d12 + 72`)
- **Speed** 40 ft., climb 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|13 (+1)|19 (+4)|19 (+4)|17 (+3)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +11, Stealth +5
- **Senses** blindsight 30 ft., darkvision 60 ft., passive Perception 21
- **Damage Resistances** acid, fire, lightning
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 12

## Traits

***Magic Resistance.*** The anathema has advantage on saving throws against spells and other magical effects.

***Ophidiophobia Aura.*** Any creature of the anathema's choice, other than a snake or a yuan-ti, that starts its turn within 30 feet of the anathema must succeed on a DC 17 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of snakes and yuan-ti. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to this anathama's aura for the next 24 hours.

***Six Heads.*** The anathema has advantage on saves against being [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), or knocked [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious).

***Spellcasting (Anathema Form Only).*** The anathema casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will**: [animal friendship](2-Mechanics/CLI/spells/animal-friendship.md) (snakes only)

**3/day each**: [darkness](2-Mechanics/CLI/spells/darkness.md), [entangle](2-Mechanics/CLI/spells/entangle.md), [fear](2-Mechanics/CLI/spells/fear.md), [polymorph](2-Mechanics/CLI/spells/polymorph.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack (Anathema Form Only).*** The anathema makes two Claw attacks and one Flurry of Bites attack.

***Claw (Anathema Form Only).*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage.

***Flurry of Bites (Anathema Form Only).*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one creature. *Hit:* `dice:6d6+6|noform|avg|text(27)` (`6d6 + 6`) piercing damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage.

***Constrict (Snake Form Only).*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 15 ft., one Large or smaller creature. *Hit:* `dice:3d6+6|noform|avg|text(16)` (`3d6 + 6`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and it takes `dice:3d6+6|noform|avg|text(16)` (`3d6 + 6`) bludgeoning damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) acid damage at the start of each of its turns. The anathema can constrict only one creature at a time.

## Bonus Actions

***Change Shape.*** The anathema transforms into a Huge constrictor snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.
```
^statblock

## Environment

desert, forest, underdark