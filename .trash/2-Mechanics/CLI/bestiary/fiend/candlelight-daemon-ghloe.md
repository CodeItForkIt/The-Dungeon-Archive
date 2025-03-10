---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/11
- monster/size/medium
- monster/type/fiend
aliases: ["Candlelight Daemon"]
---
# Candlelight Daemon
*Source: Grim Hollow: Lairs of Etharis p. 25*  

> [!quote]  
> 
> A candlelight daemon remains for the duration of a cursed candle's flame. That's long enough for a host of sinister deeds.

## Salvage

The melted leavings of a candlelight daemon's candle act as oil of sharpness against aberrations, celestials, fey, and fiends, as well as against the creature that created the candle.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Candlelight daemons return to the Netherworld if their candle goes out.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Candlelight daemons have immunities and resistances typical of fiends, including immunity to poison and resistance to cold, fire, lightning, and nonmagical weapon attacks. The daemon is also resistant to magic and capable of countering spells.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** A candlelight daemon is most effective in shadows or darkness, which allow the fiend to hide easily and bring its murderous talents to bear.  

## Statblock

```ad-statblock
title: Candlelight Daemon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Candlelight%20Daemon.webp#token)
*Medium fiend, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 170 (`20d8 + 80`)
- **Speed** 50 ft., fly 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|17 (+3)|18 (+4)|12 (+1)|14 (+2)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Deception +7, Insight +6, Investigation +5, Perception +6, Stealth +7
- **Senses** darkvision 120 ft., passive Perception 16
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Infernal
- **Challenge** 11

## Traits

***Candle Dependence.*** The daemon remains on the Material Plane only while the candle that summoned it burns.

***Magic Resistance.*** The daemon has advantage on saving throws against spells and other magical effects.

***Nether Step.*** As its movement for its turn, the candlelight daemon can teleport to an unoccupied space within 30 feet of it, provided the space it's teleporting to and from are both in dim light or darkness. The daemon doesn't need to see the destination.

***Shadow Stealth.*** While in dim light or darkness, the daemon can take the Hide action as a bonus action.

***Slayer's Advantage.*** The candlelight daemon has advantage on attack rolls against any creature that hasn't had a turn in combat.

***Slayer's Attack (1/Turn).*** The candlelight daemon deals an extra 35 `dice:10d6|noform|avg` (`10d6`) damage when it hits a target with an attack and has advantage on the attack roll. With the [suffocate](2-Mechanics/CLI/spells/suffocate-ghloe.md) spell, the daemon deals this damage as extra bludgeoning damage.

***Innate Spellcasting.*** The daemon's spellcasting ability is Charisma (spell save DC 15, `dice:1d20+7|noform|text(+7)` to hit with spell attacks). The daemon can innately cast the following spells, requiring no components:

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [hunter sense](2-Mechanics/CLI/spells/hunter-sense-ghloe.md), [knock](2-Mechanics/CLI/spells/knock.md)

**1/day each**: [counterspell](2-Mechanics/CLI/spells/counterspell.md), [darkness](2-Mechanics/CLI/spells/darkness.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [shield](2-Mechanics/CLI/spells/shield.md), [suffocate](2-Mechanics/CLI/spells/suffocate-ghloe.md)

## Actions

***Multiattack.*** The daemon makes two claw attacks and one gore attack. It can use hurl fire in place of any of these attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage and `dice:1d8|noform|avg|text(4)` (`1d8`) fire damage.

***Gore.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(12)` (`2d8 + 3`) piercing damage and `dice:1d8|noform|avg|text(4)` (`1d8`) fire damage.

***Hurl Fire.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one target. *Hit:* `dice:3d8|noform|avg|text(13)` (`3d8`) fire damage.
```
^statblock