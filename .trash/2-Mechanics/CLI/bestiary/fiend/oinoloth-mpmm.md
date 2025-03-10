---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/12
- monster/environment/desert
- monster/environment/underdark
- monster/size/medium
- monster/type/fiend/yugoloth
aliases: ["Oinoloth"]
---
# Oinoloth
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 202, Mordenkainen's Tome of Foes p. 251*  

Grim specters of death, oinoloths bring pestilence wherever they go. When armies recognize their awful forms, their mere appearance causes soldiers to break ranks and flee, lest they succumb to one of the awful plagues that oinoloths let loose.

Oinoloths solve thorny problems by killing everyone involved. They are typically hired as a last resort when a siege has gone on too long or an army has proven too strong to overcome. Once summoned, oinoloths stalk the killing field, poisoning the ground and sickening creatures they encounter. Sometimes they might be hired to lift the very plagues they spread, but the price for such work is high, and the effort turns the creatures they save into debilitated wrecks.

```ad-statblock
title: Oinoloth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Oinoloth.webp#token)
*Medium fiend (yugoloth), Typically  Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 119 (`14d8 + 56`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|17 (+3)|18 (+4)|17 (+3)|16 (+3)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +7
- **Skills** Deception +8, Intimidation +8, Perception +7
- **Senses** blindsight 60 ft., darkvision 60 ft., passive Perception 17
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 12

## Traits

***Magic Resistance.*** The oinoloth has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The oinoloth casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [darkness](2-Mechanics/CLI/spells/darkness.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only)

**1/day each**: [feeblemind](2-Mechanics/CLI/spells/feeblemind.md), [globe of invulnerability](2-Mechanics/CLI/spells/globe-of-invulnerability.md)

## Actions

***Multiattack.*** The oinoloth makes two Claw attacks, and it uses Spellcasting or Teleport.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) slashing damage plus `dice:4d10|noform|avg|text(22)` (`4d10`) necrotic damage.

***Corrupted Healing (Recharge 6).*** The oinoloth touches one willing creature within 5 feet of it. The target regains all its hit points. In addition, the oinoloth can end one disease on the target or remove one of the following conditions from it: [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), or [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). The target then gains 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), and its hit point maximum is reduced by `dice:2d6|noform|avg|text(7)` (`2d6`). This reduction can be removed only by a [wish](2-Mechanics/CLI/spells/wish.md) spell or by casting [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) on the target three times within the same hour. The target dies if its hit point maximum is reduced to 0.

***Teleport.*** The oinoloth teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.

## Bonus Actions

***Bringer of Plagues (Recharge 5-6).*** The oinoloth blights the area in a 30-foot-radius sphere centered on itself. The blight lasts for 24 hours. While the area is blighted, all normal plants there wither and die.

Furthermore, when a creature moves into the blighted area or starts its turn there, that creature must make a DC 16 Constitution saving throw. On a failed save, the creature takes `dice:4d6|noform|avg|text(14)` (`4d6`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). On a successful save, the creature is immune to the oinoloth's Bringer of Plagues for the next 24 hours.

The [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can't regain hit points. After every 24 hours that elapse, the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw. On a failed save, the creature's hit point maximum is reduced by `dice:1d10|noform|avg|text(5)` (`1d10`). This reduction lasts until the poison ends, and the target dies if its hit point maximum is reduced to 0. The poison ends after the creature successfully saves against it three times.
```
^statblock

## Environment

desert, underdark