---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/5
- monster/size/medium
- monster/type/monstrosity
aliases: ["Thri-kreen Mystic"]
---
# Thri-kreen Mystic
*Source: Boo's Astral Menagerie p. 61, Light of Xaryxis*  

Thri-kreen mystics use psionics to navigate difficult terrain in Wildspace, turn invisible, and drain life from their prey. They often serve as spelljammers aboard thri-kreen ships.

```ad-statblock
title: Thri-kreen Mystic
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Thri-kreen%20Mystic.webp#token)
*Medium monstrosity, Any alignment*

- **Armor Class** 15 (natural armor)
- **Hit Points** 99 (`18d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|15 (+2)|13 (+1)|12 (+1)|16 (+3)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6, Stealth +5, Survival +6
- **Senses** darkvision 60 ft., passive Perception 16
- **Languages** telepathy 60 ft., Thri-kreen
- **Challenge** 5

***Spellcasting (Psionics).*** The thri-kreen casts one of the following spells, requiring no spell components and using Wisdom as the spellcasting ability:

**At will**: [levitate](2-Mechanics/CLI/spells/levitate.md) (self only), [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible)

**1/day each**: [freedom of movement](2-Mechanics/CLI/spells/freedom-of-movement.md) (self only), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only)

## Actions

***Multiattack.*** The thri-kreen makes two Gythka attacks or four Psychic Bolt attacks.

***Gythka.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+1|noform|avg|text(10)` (`2d8 + 1`) slashing damage.

***Psychic Bolt.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 60 ft., one creature. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) psychic damage.

***Drain Vitality (Recharges after a Short or Long Rest).*** The thri-kreen targets one creature it can see within 30 feet of itself. The target must make a DC 14 Constitution saving throw, taking `dice:5d12|noform|avg|text(32)` (`5d12`) necrotic damage on a failed save, or half as much damage on a successful one. The thri-kreen regains hit points equal to the damage dealt.

## Bonus Actions

***Chameleon Carapace.*** The thri-kreen changes the color of its carapace to match the color and texture of its surroundings, gaining advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks it makes to hide in those surroundings.
```
^statblock