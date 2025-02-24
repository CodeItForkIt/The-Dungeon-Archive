---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/vrgr
- monster/cr/7
- monster/size/medium
- monster/type/undead
aliases: ["Priest of Osybus (Deathly Boon)"]
---
# Priest of Osybus (Deathly Boon)
*Source: Van Richten's Guide to Ravenloft p. 241, Vecna: Eve of Ruin*  

```ad-statblock
title: Priest of Osybus (Deathly Boon)
*Medium undead, Unaligned*

- **Armor Class** 14 (natural armor)
- **Hit Points** 60 (`8d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|16 (+3)|18 (+4)|17 (+3)|11 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +7, Wisdom +6, Charisma +3
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** any three languages
- **Challenge** 7

## Traits

***Tattoo of Osybus.*** If the priest drops to 0 hit points, roll on the Boons of Undeath table for the boon the priest receives. The priest dies if it receives a boon it already has. If it receives a new boon, it revives at the start of its next turn with half its hit points restored, and its creature type is now Undead.

To prevent this revival, the Tattoo of Osybus on the priest's body must be destroyed. The tattoo is invulnerable while the priest has at least 1 hit point. The tattoo is otherwise an object with AC 15, and it is immune to poison and psychic damage. It has 15 hit points, but it regains all its hit points at the end of every combatant's turn.

***Innate Spellcasting.*** The priest casts one of the following spells, requiring no components and using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: 

**1/day each**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md), [create undead](2-Mechanics/CLI/spells/create-undead.md)

## Actions

***Multiattack.*** The priest attacks twice.

***Soul Blade.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+2|noform|avg|text(7)` (`2d4 + 2`) piercing damage, and if the target is a creature, it is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the start of the priest's next turn. If this damage reduces a Medium or smaller creature to 0 hit points, the creature dies, and its soul is trapped in the priest's body, manifesting as a shadowy Soul Tattoo on the priest. The soul is freed if the priest dies.

***Necrotic Bolt.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one target. *Hit:* `dice:3d8+4|noform|avg|text(17)` (`3d8 + 4`) necrotic damage, and the target can't regain hit points until the start of the priest's next turn.

***Circle of Death (Spell; (Recharge 5|m-6)).*** Each creature in a 60-foot-radius sphere centered on a point the priest can see within 150 feet of it must make a DC 15 Constitution saving throw, taking `dice:8d6|noform|avg|text(28)` (`8d6`) necrotic damage on a failed save, or half as much damage on a successful one.)

## Bonus Actions

***Soul Tattoo (Recharge 5-6).*** The priest touches one of the Soul Tattoos on its body. The tattoo vanishes as the trapped soul manifests as a shadowy creature that appears in an unoccupied space the priest can see within 30 feet of it. The creature has the size and silhouette of its original body, but it otherwise uses the stat block of a shadow.

The shadow obeys the priest's mental commands (no action required) and takes its turn immediately after the priest. If the creature is within 5 feet of the priest, it can turn back into a tattoo as an action, reappearing on the priest's flesh and regaining all its hit points.
```
^statblock