---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/14
- monster/size/large
- monster/type/fiend/devil
aliases: ["Corruption Devil (Paeliryon)"]
---
# Corruption Devil (Paeliryon)
*Source: Chains of Asmodeus p. 239*  

One of the stronger greater devils, the paeliryon focus on corruption and obtaining mortal souls. While they can be found on almost every layer of the Nine Hells, paeliryons are particularly prominent in Dis and Malbolge, where they hold positions of power. Their duties include managing lesser devils, directing and manipulating the soul trade, and infernal politics. They're particularly talented at blackmailing and spying—abilities used both within and without the Nine Hells.

## Imposing Devils

As greater devils, paeliryons are particularly large, often weighing more than 4000 pounds. Like hags, their skin is covered in boils and warts of varying colors, and they have massive bellies and leathery wings. Despite their physical drawbacks, corruption devils are quite formidable in combat. Rather than fight themselves, however, they use followers and lesser devils as fodder.

## Sire of Corruption

Occasionally a paeliryon becomes more powerful than their sisters and takes on the mantle of a sire of corruption. These sires can be counted among the strongest infernals, aside from archdevils, and usually direct their power to other planes of existence. Befitting their name, sires of corruption only seek one goal: to corrupt. To this end, their plans often involve the decay of empires or corruption of religious groups. Sires are few and far between, and a new sire usually rises only once every few centuries. Though they usually operate alone, some sires have served archdevils whose plans involved enough corruption to encourage cooperation.

## Statblock

```ad-statblock
title: Corruption Devil (Paeliryon)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Corruption%20Devil%20%28Paeliryon%29.webp#token)
*Large fiend (devil), Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 218 (`19d10 + 114`)
- **Speed** 20 ft., burrow 20 ft., fly 60 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|14 (+2)|22 (+6)|19 (+4)|15 (+2)|14 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +11, Wisdom +7
- **Skills** Arcana +9, Deception +7, Insight +7, Intimidation +7
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 12
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 14

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the paeliryon's darkvision.

***Keen Eyes.*** The paeliryon scores a critical hit on a roll of 19 or 20.

***Magic Resistance.*** The paeliryon has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The paeliryon casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [Bestow Curse](2-Mechanics/CLI/spells/bestow-curse.md), [Command](2-Mechanics/CLI/spells/command.md), [Darkness](2-Mechanics/CLI/spells/darkness.md), [Hold Monster](2-Mechanics/CLI/spells/hold-monster.md), [Major Image](2-Mechanics/CLI/spells/major-image.md)

**1/day each**: [Antilife Shell](2-Mechanics/CLI/spells/antilife-shell.md), [Incendiary Cloud](2-Mechanics/CLI/spells/incendiary-cloud.md), [Scrying](2-Mechanics/CLI/spells/scrying.md), [Weird](2-Mechanics/CLI/spells/weird.md)

## Actions

***Multiattack.*** The paeliryon makes three Claw attacks. It can replace one of the attacks with Draining Grasp (if available).

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) slashing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) fire damage.

***Draining Grasp (Recharge 4-6).*** The paeliryon makes a Claw attack. On a hit, the target's Charisma score is reduced by `dice:1d4|noform|avg|text(2)` (`1d4`). This reduction lasts until the target finishes a short or long rest. A creature whose Charisma is reduced to 3 or less because of this ability, has the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute.
```
^statblock