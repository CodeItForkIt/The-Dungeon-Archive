---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/17
- monster/size/medium
- monster/type/undead
aliases: ["Death Knight"]
---
# Death Knight
*Source: Monster Manual p. 47, Ghosts of Saltmarsh, Divine Contention, Dragon of Icespire Peak, Baldur's Gate: Descent Into Avernus, Explorer's Guide to Wildemount, Tasha's Cauldron of Everything, Candlekeep Mysteries, Dragonlance: Shadow of the Dragon Queen, Adventure Atlas: The Mortuary, Sigil and the Outlands, Vecna: Eve of Ruin*  

When a paladin that falls from grace dies without seeking atonement, dark powers can transform the once-mortal knight into a hateful undead creature. A death knight is a skeletal warrior clad in fearsome plate armor. Beneath its helmet, one can see the knight's skull with malevolent pinpoints of light burning in its eye sockets.

## Eldritch Power

The death knight retains the ability to cast divine spells. However, no death knight can use its magic to heal. A death knight also attracts and commands lesser undead, although death knights that serve powerful fiends might have fiendish followers instead. Death knights often use warhorse skeletons and nightmares as mounts.

## Immortal Until Redeemed

A death knight can arise anew even after it has been destroyed. Only when it atones for a life of wickedness or finds redemption can it finally escape its undead purgatory and truly perish.

## Undead Nature

A death knight doesn't require air, food, drink, or sleep.

> [!note] Lord Soth
> 
> Lord Soth began his fall from grace with an act of heroism, saving an elf named Isolde from an ogre. Soth and Isolde fell in love, but Soth was already married. He had a servant dispose of his wife and was charged with murder, but fled with Isolde. When his castle fell under siege, he prayed for guidance and was told that he must atone for his misdeeds by completing a quest, but growing fears about Isolde's fidelity caused him to abandon his quest. Because his mission was not accomplished, a great cataclysm swept the land. When Isolde gave birth to a son, Soth refused to believe that the child was his and slew them both. All were incinerated in a fire that swept through the castle, yet Soth would find no rest in death, becoming a death knight.
^lord-soth

## Statblock

```ad-statblock
title: Death Knight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MM/Death%20Knight.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 20 ([plate armor](2-Mechanics/CLI/items/plate-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 180 (`19d8 + 95`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|11 (+0)|20 (+5)|12 (+1)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Wisdom +9, Charisma +10
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 17

## Traits

***Magic Resistance.*** The death knight has advantage on saving throws against spells and other magical effects.

***Marshal Undead.*** Unless the death knight is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), it and undead creatures of its choice within 60 feet of it have advantage on saving throws against features that turn undead.

***Spellcasting.*** The death knight is a 19th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 18, `dice:1d20+10|noform|text(+10)` to hit with spell attacks). It has the following paladin spells prepared:

**1st level (4 slots)**: [command](2-Mechanics/CLI/spells/command.md), [compelled duel](2-Mechanics/CLI/spells/compelled-duel.md), [searing smite](2-Mechanics/CLI/spells/searing-smite.md)

**2nd level (3 slots)**: [hold person](2-Mechanics/CLI/spells/hold-person.md), [magic weapon](2-Mechanics/CLI/spells/magic-weapon.md)

**3rd level (3 slots)**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [elemental weapon](2-Mechanics/CLI/spells/elemental-weapon.md)

**4th level (3 slots)**: [banishment](2-Mechanics/CLI/spells/banishment.md), [staggering smite](2-Mechanics/CLI/spells/staggering-smite.md)

**5th level (2 slots)**: [destructive wave](2-Mechanics/CLI/spells/destructive-wave.md) (necrotic)

## Actions

***Multiattack.*** The death knight makes three longsword attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) slashing damage, or `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) slashing damage if used with two hands, plus `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage.

***Hellfire Orb (1/Day).*** The death knight hurls a magical ball of fire that explodes at a point it can see within 120 feet of it. Each creature in a 20-foot-radius sphere centered on that point must make a DC 18 Dexterity saving throw. The sphere spreads around corners. A creature takes `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage and `dice:10d6|noform|avg|text(35)` (`10d6`) necrotic damage on a failed save, or half as much damage on a successful one.

## Reactions

***Parry.*** The death knight adds 6 to its AC against one melee attack that would hit it. To do so, the death knight must see the attacker and be wielding a melee weapon.
```
^statblock