---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/gos
- monster/cr/10
- monster/size/medium
- monster/type/aberration
aliases: ["Mr. Dory"]
---
# Mr. Dory
*Source: Ghosts of Saltmarsh p. 246*  

One of the four councillors who rule the Styes, Mr. Dory hides his cursed nature in plain sight. His rare, liquid-sensitive "skin condition" is actually a form of the same aboleth affliction that creates skum, though Dory's condition is not as severe, and he has managed to retain his free will.

```ad-statblock
title: Mr. Dory
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Mr.%20Dory.webp#token)
*Medium aberration, Chaotic Evil*

- **Armor Class** 18 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 170 (`20d8 + 80`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|20 (+5)|19 (+4)|14 (+2)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +6
- **Skills** Athletics +5, Perception +6, Stealth +9
- **Senses** darkvision 60 ft., passive Perception 16
- **Damage Immunities** necrotic
- **Languages** Abyssal, Common, Deep Speech, telepathy 60 ft.
- **Challenge** 10

## Traits

***Magic Resistance.*** Mr. Dory has advantage on saving throws against spells and other magical effects.

***Water Dependency.*** Mr. Dory takes `dice:1d12|noform|avg|text(6)` (`1d12`) acid damage at the end of every hour he goes without exposure to water.

***Innate Spellcasting.*** Mr. Dory's innate spellcasting ability is Charisma (save DC 15, `dice:1d20+7|noform|text(+7)` to hit with spell attacks). Mr. Dory can innately cast the following spells, requiring no material components:

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only)

**1/day each**: [cloudkill](2-Mechanics/CLI/spells/cloudkill.md), [etherealness](2-Mechanics/CLI/spells/etherealness.md)

**2/day each**: [fear](2-Mechanics/CLI/spells/fear.md), [fireball](2-Mechanics/CLI/spells/fireball.md), [fly](2-Mechanics/CLI/spells/fly.md)

## Actions

***Multiattack.*** Mr. Dory makes three attacks with his rapier.

***Rapier.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) piercing damage and `dice:2d6|noform|avg|text(7)` (`2d6`) necrotic damage.

***Eye of Corruption (Recharge 5-6).*** Mr. Dory glares at a creature he can see within 30 feet of him. The target must make a DC 15 Constitution saving throw. On a failed save, it takes `dice:5d10|noform|avg|text(27)` (`5d10`) necrotic damage and `dice:5d10|noform|avg|text(27)` (`5d10`) poison damage and then gains vulnerability to both necrotic and poison damage for 1 minute. On a successful save, it takes half damage and does not gain the vulnerabilities.
```
^statblock