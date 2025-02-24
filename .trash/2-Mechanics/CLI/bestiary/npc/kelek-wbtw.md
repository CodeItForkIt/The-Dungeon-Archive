---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/sorcerer
aliases: ["Kelek"]
---
# Kelek
*Source: The Wild Beyond the Witchlight p. 219*  

Kelek is a greedy, narcissistic sociopath who revels in chaos but is a coward at heart. The fact that he's highly intelligent makes him even more dangerous. More than anything, he wants the staff of power in the possession of his most hated foe, Ringlerun (described later in this appendix).

```ad-statblock
title: Kelek
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Kelek.webp#token)
*Medium humanoid (human, sorcerer), Chaotic Evil*

- **Armor Class** 12 ([bracers of defense](2-Mechanics/CLI/items/bracers-of-defense.md))
- **Hit Points** 45 (`7d8 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|10 (+0)|14 (+2)|15 (+2)|13 (+1)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +5, Charisma +6
- **Skills** Deception +6, Intimidation +6
- **Senses** passive Perception 11
- **Languages** Common, Draconic, Elvish
- **Challenge** 5

## Traits

***Special Equipment.*** Kelek wears [bracers of defense](2-Mechanics/CLI/items/bracers-of-defense.md) and carries a [staff of striking](2-Mechanics/CLI/items/staff-of-striking.md) with 10 charges. The staff regains `dice:1d6+4|noform|avg` (`1d6 + 4`) expended charges daily at dawn. If its last charge is expended, roll a `dice:d20|noform|avg` (`d20`); on a 1, the staff becomes a nonmagical quarterstaff.

***Spellcasting.*** Kelek casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 14):

**At will**: [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [dominate beast](2-Mechanics/CLI/spells/dominate-beast.md), [fly](2-Mechanics/CLI/spells/fly.md), [mirror image](2-Mechanics/CLI/spells/mirror-image.md), [web](2-Mechanics/CLI/spells/web.md)

## Actions

***Multiattack.*** Kelek makes three attacks using Sorcerer's Bolt, Staff of Striking, or a combination of them. He can replace one of the attacks with a use of Spellcasting.

***Sorcerer's Bolt.*** *Melee or Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:2d12|noform|avg|text(13)` (`2d12`) force damage.

***Staff of Striking.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) bludgeoning damage, or `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) bludgeoning damage when used with two hands, and Kelek can expend up to 3 of the staff's charges, dealing an extra `dice:1d6|noform|avg|text(3)` (`1d6`) force damage for each expended charge.

***Fiery Explosion (Recharge 4-6).*** Kelek creates a magical explosion of fire centered on a point he can see within 120 feet of him. Each creature in a 20-foot-radius sphere centered on that point must make a DC 14 Dexterity saving throw, taking `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage on a failed save, or half as much damage on a successful one.

## Reactions

***Arcane Defense (3/Day).*** When he is hit by an attack, Kelek protects himself with an [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) barrier of magical force. Until the end of his next turn, he gains a +5 bonus to AC, including against the triggering attack.
```
^statblock