---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/10
- monster/size/medium
- monster/type/celestial
aliases: ["Angel of Amonkhet"]
---
# Angel of Amonkhet
*Source: Plane Shift: Amonkhet p. 30*  

Whatever their original forms might have been, the angels of Amonkhet have been twisted into distorted reflections of Nicol Bolas. Their limbs are long and thin, with elongated shins and forearms. Their huge wings are adorned with white and black feathers. Light shines through their joints and chests as if from an internal fire, and their eyes glow with a gold or orange light.

Bolas's angels are his personal agents during his absence from Amonkhet. Their mission, which they pursue with unwavering devotion, is to keep Naktamun free of dissenting voices. They stand as sentinels over the city, extending supernatural senses to detect the presence of dissenters. They use their long, hooked [staffs](2-Mechanics/CLI/items/staff.md) to capture those who question the God-Pharaoh's rule, and are tasked with carrying out the punishment that Bolas's law demands. Dissenters are bound into sarcophagi—the Tombs of Disgrace—and exposed to the mockery of fellow citizens in the Display of Doubt. On the following morning, the angels carry the sarcophagi into the desert and abandon the dissenters to the horrors of the sands—and the Curse of Wandering.

Use the statistics of a [deva](2-Mechanics/CLI/bestiary/celestial/deva.md) for an angel on Amonkhet, replacing its mace attack with a staff attack. When the angel hits with a melee attack using its staff, the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and the angel can't attack another target with its staff.

```ad-statblock
title: Angel of Amonkhet
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Angel%20of%20Amonkhet.webp#token)
*Medium celestial, Lawful Good*

- **Armor Class** 17 (natural armor)
- **Hit Points** 136 (`16d8 + 64`)
- **Speed** 30 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|17 (+3)|20 (+5)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +9, Charisma +9
- **Skills** Insight +9, Perception +9
- **Senses** darkvision 120 ft., passive Perception 19
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all, telepathy 120 ft.
- **Challenge** 10

## Traits

***Angelic Weapons.*** The angel's weapon attacks are magical. When the angel hits with any weapon, the weapon deals an extra `dice:4d8|noform|avg` (`4d8`) radiant damage (included in the attack).

***Magic Resistance.*** The angel has advantage on saving throws against spells and other magical effects.

***Innate Spellcasting.*** The angel's spellcasting ability is Charisma (spell save DC 17). The angel can innately cast the following spells, requiring only verbal components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md)

**1/day each**: [commune](2-Mechanics/CLI/spells/commune.md), [raise dead](2-Mechanics/CLI/spells/raise-dead.md)

## Actions

***Multiattack.*** The angel makes two melee attacks.

***Staff.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(7)` (`1d8 + 4`) bludgeoning damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the angel can't attack another target with its staff.

***Healing Touch (3/Day).*** The angel touches another creature. The target magically regains `dice:4d8+2|noform|avg|text(20)` (`4d8 + 2`) hit points and is freed from any curse, disease, poison, blindness, or deafness.

***Change Shape.*** The angel magically polymorphs into a humanoid or beast that has a challenge rating equal to or less than its own, or back into its true form. It reverts to its true form if it dies. Any equipment it is wearing or carrying is absorbed or borne by the new form (the angel's choice).

In a new form, the angel retains its game statistics and ability to speak, but its AC, movement modes, Strength, Dexterity, and special senses are replaced by those of the new form, and it gains any statistics and capabilities (except class features, legendary actions, and lair actions) that the new form has but that it lacks.
```
^statblock