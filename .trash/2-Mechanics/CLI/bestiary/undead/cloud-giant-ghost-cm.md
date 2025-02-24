---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cm
- monster/cr/9
- monster/size/huge
- monster/type/undead
aliases: ["Cloud Giant Ghost"]
---
# Cloud Giant Ghost
*Source: Candlekeep Mysteries p. 146*  

```ad-statblock
title: Cloud Giant Ghost
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CM/Cloud%20Giant%20Ghost.webp#token)
*Huge undead, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 104 (`16d12`)
- **Speed** 0 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|27 (+8)|11 (+0)|10 (+0)|12 (+1)|16 (+3)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +7, Charisma +7
- **Skills** Perception +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** cold
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](2-Mechanics/CLI/rules/conditions.md#Prone), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Giant
- **Challenge** 9

## Traits

***Ethereal Sight.*** The ghost can see 120 feet into the Ethereal Plane when it is on the Material Plane, and vice versa.

***Incorporeal Movement.*** The ghost can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|avg|text(5)` (`1d10`) force damage if it ends its turn inside an object.

***Regeneration.*** The ghost regains 10 hit points at the start of its turn. If the ghost takes radiant damage or damage from a magic weapon, this trait doesn't function at the start of the ghost's next turn. The ghost dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Spellcasting.*** The ghost casts one of the following spells, using Charisma as the spellcasting ability and requiring no material components:

**At will**: [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md)

**1/day**: [control weather](2-Mechanics/CLI/spells/control-weather.md)

**3/day**: [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

## Actions

***Multiattack.*** The ghost makes two melee attacks.

***Spectral Weapon.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+8|noform|avg|text(21)` (`3d8 + 8`) force damage.

***Etherealness.*** The ghost enters the Ethereal Plane from the Material Plane, or vice versa. It is visible on the Material Plane while it is in the Border Ethereal, and vice versa, yet it can't affect or be affected by anything on the other plane.

***Wind Howl (Recharge 6).*** The ghost emits a dreadful howl that summons a cold, biting wind. This wind engulfs up to three creatures of the ghost's choice that it can see within 60 feet of it. Each target is pulled up to 20 feet toward the ghost and must make a DC 15 Constitution saving throw, taking `dice:3d10|noform|avg|text(16)` (`3d10`) cold damage on a failed save, or half as much damage on a successful one.
```
^statblock