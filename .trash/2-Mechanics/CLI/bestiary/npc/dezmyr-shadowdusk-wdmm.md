---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/17
- monster/size/medium
- monster/type/undead
aliases: ["Dezmyr Shadowdusk"]
---
# Dezmyr Shadowdusk
*Source: Waterdeep: Dungeon of the Mad Mage p. 287*  

```ad-statblock
title: Dezmyr Shadowdusk
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Dezmyr%20Shadowdusk.webp#token)
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

***Warp Reality.*** As a bonus action on her turn, Dezmyr can warp reality, undoing damage dealt to herself or another creature that she can see within 20 feet of her. The beneficiary of this warped reality instantly regains 10 hit points.

***Magic Resistance.*** Dezmyr has advantage on saving throws against spells and other magical effects.

***Marshal Undead.*** Unless Dezmyr is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), it and undead creatures of its choice within 60 feet of it have advantage on saving throws against features that turn undead.

***Spellcasting.*** Dezmyr is a 19th-level spellcaster. Her spellcasting ability is Charisma (spell save DC 18, `dice:1d20+10|noform|text(+10)` to hit with spell attacks). She has the following paladin spells prepared:

**1st level (4 slots)**: [command](2-Mechanics/CLI/spells/command.md), [compelled duel](2-Mechanics/CLI/spells/compelled-duel.md), [searing smite](2-Mechanics/CLI/spells/searing-smite.md)

**2nd level (3 slots)**: [hold person](2-Mechanics/CLI/spells/hold-person.md), [magic weapon](2-Mechanics/CLI/spells/magic-weapon.md)

**3rd level (3 slots)**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [elemental weapon](2-Mechanics/CLI/spells/elemental-weapon.md)

**4th level (3 slots)**: [locate creature](2-Mechanics/CLI/spells/locate-creature.md), [staggering smite](2-Mechanics/CLI/spells/staggering-smite.md)

**5th level (2 slots)**: [destructive wave](2-Mechanics/CLI/spells/destructive-wave.md) (necrotic)

## Actions

***Multiattack.*** Dezmyr makes three longsword attacks.

***Longsword.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) slashing damage, or `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) slashing damage if used with two hands, plus `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage.

***Hellfire Orb (1/Day).*** Dezmyr hurls a magical ball of fire that explodes at a point it can see within 120 feet of it. Each creature in a 20-foot-radius sphere centered on that point must make a DC 18 Dexterity saving throw. The sphere spreads around corners. A creature takes `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage and `dice:10d6|noform|avg|text(35)` (`10d6`) necrotic damage on a failed save, or half as much damage on a successful one.

## Reactions

***Parry.*** Dezmyr adds 6 to its AC against one melee attack that would hit it. To do so, Dezmyr must see the attacker and be wielding a melee weapon.
```
^statblock