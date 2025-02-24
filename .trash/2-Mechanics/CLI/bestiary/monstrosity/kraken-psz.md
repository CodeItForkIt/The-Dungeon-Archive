---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/13
- monster/size/huge
- monster/type/monstrosity
aliases: ["Kraken"]
---
# Kraken
*Source: Plane Shift: Zendikar p. 25*  

Lurking in the deepest reaches of Zendikar's seas, krakens are mysterious monsters of unpredictable wrath and terrible destruction. Though they take the form of rampaging brutes when they appear on the surface, the truth of their existence is more complex. Krakens embody force of will and the drive for self-determination shared by all thinking beings. When their will is turned to destruction, they are capable of wreaking terrible havoc upon ships at sea or coastal settlements. But they live most of their adult lives in utter isolation in the deeps, focused on their own probing of the seas' mysteries.

A kraken has a roughly humanoid shape, with two strong arms and a broad chest. Its head is encased in a rough shell that sprouts two large horns, and one of its hands is a bony claw. It has dozens of tentacles—a writhing mass below its toothy mouth, another mass at the end of one arm, and several long tentacles in place of legs. On its back is a huge conch-like shell.

Though the Monster Manual has its own version of the kraken, Zendikar's krakens are actually more similar to storm giants.

```ad-statblock
title: Kraken
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Kraken.webp#token)
*Huge monstrosity, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 230 (`20d12 + 100`)
- **Speed** 30 ft., swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|29 (+9)|14 (+2)|20 (+5)|16 (+3)|18 (+4)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** ⏤
- **Skills** Athletics +14, Perception +9
- **Senses** darkvision 120 ft., passive Perception 19
- **Damage Resistances** cold
- **Damage Immunities** lightning, thunder
- **Languages** Common
- **Challenge** 13

## Traits

***Amphibious.*** The kraken can breathe air and water.

***Innate Spellcasting.*** The kraken's innate spellcasting ability is Charisma (spell save DC 17). The kraken can innately cast the following spells, requiring no components:

**3/day each**: [control weather](2-Mechanics/CLI/spells/control-weather.md), [water breathing](2-Mechanics/CLI/spells/water-breathing.md)

## Actions

***Multiattack.*** The kraken makes two attacks: one with its claw and one with its tentacles.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:6d6+9|noform|avg|text(30)` (`6d6 + 9`) slashing damage.

***Tentacles.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 20 ft., one target. *Hit:* `dice:6d6+9|noform|avg|text(30)` (`6d6 + 9`) bludgeoning damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained).

***Lightning Strike (Recharge 5-6).*** The kraken hurls a magical lightning bolt at a point it can see within 500 feet of it. Each creature within 10 feet of that point must make a DC 17 Dexterity saving throw, taking `dice:12d8|noform|avg|text(54)` (`12d8`) lightning damage on a failed save, or half as much damage on a successful one.
```
^statblock