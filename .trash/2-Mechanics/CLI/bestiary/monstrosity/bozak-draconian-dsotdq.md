---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/2
- monster/size/medium
- monster/type/monstrosity/sorcerer
aliases: ["Bozak Draconian"]
---
# Bozak Draconian
*Source: Dragonlance: Shadow of the Dragon Queen p. 198*  

Bozak draconians are born from bronze dragon eggs and wield magic to aid their allies in battle. Their wings aren't strong enough for full flight, but bozaks can use them to glide during a fall. When bozaks die, their flesh shrivels away before their bones explode, sending a shower of magical splinters in all directions.

## Draconians

Draconians are bipedal monsters born from metallic dragon eggs that have been corrupted by a combination of warped alchemy and the Dragon Queen's foul magic. The Dragon Armies closely guard the secret of the draconians' creation, allowing Krynn's metallic dragons to continue to think their eggs are being held hostage so they don't oppose the Dragon Queen's conquests.

## Statblock

```ad-statblock
title: Bozak Draconian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Bozak%20Draconian.webp#token)
*Medium monstrosity (sorcerer), typically  Lawful Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 40 (`9d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|10 (+0)|11 (+0)|11 (+0)|10 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +2, Wisdom +2, Charisma +4
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Languages** Common, Draconic
- **Challenge** 2

## Traits

***Death Throes.*** When the draconian is reduced to 0 hit points, its scales and flesh immediately shrivel away, and then its bones explode. Each creature within 10 feet of it must succeed on a DC 10 Dexterity saving throw or take `dice:2d8|noform|avg|text(9)` (`2d8`) force damage.

***Glide.*** When the draconian falls and isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), it subtracts up to 100 feet from the fall when calculating the fall's damage, and it can move up to 2 feet horizontally for every 1 foot it descends.

***Spellcasting.*** The draconian casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 12):

**1/day each**: [enlarge/reduce](2-Mechanics/CLI/spells/enlarge-reduce.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [stinking cloud](2-Mechanics/CLI/spells/stinking-cloud.md), [web](2-Mechanics/CLI/spells/web.md)

## Actions

***Multiattack.*** The draconian makes two Trident melee attacks or two Lightning Discharge attacks.

***Trident.*** *Melee or Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage, or `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage if used with two hands to make a melee attack.

***Lightning Discharge.*** *Ranged Spell Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 60 ft., one target. *Hit:* `dice:3d6|noform|avg|text(10)` (`3d6`) lightning damage.
```
^statblock