---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/6
- monster/size/medium
- monster/type/monstrosity/sorcerer
aliases: ["Aurak Draconian"]
---
# Aurak Draconian
*Source: Dragonlance: Shadow of the Dragon Queen p. 196*  

Created from the eggs of gold dragons, aurak draconians are the most powerful of draconians, their entire being thrumming with eldritch power. Unlike other draconians, auraks are wingless. This might lull foes into a false sense of security, until the auraks exhale noxious fumes resembling those of their dragon progenitors. Auraks are masterminds and strategists that serve as commanders in the Dragon Armies. They often lead contingents of less powerful draconians. When slain, aurak draconians unleash their inherent magic in a deadly burst of lightning.

## Draconians

Draconians are bipedal monsters born from metallic dragon eggs that have been corrupted by a combination of warped alchemy and the Dragon Queen's foul magic. The Dragon Armies closely guard the secret of the draconians' creation, allowing Krynn's metallic dragons to continue to think their eggs are being held hostage so they don't oppose the Dragon Queen's conquests.

## Statblock

```ad-statblock
title: Aurak Draconian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Aurak%20Draconian.webp#token)
*Medium monstrosity (sorcerer), typically  Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 67 (`9d8 + 27`)
- **Speed** 35 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|14 (+2)|16 (+3)|16 (+3)|11 (+0)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +6, Wisdom +3, Charisma +6
- **Skills** Perception +3
- **Senses** truesight 60 ft., passive Perception 13
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed)
- **Languages** Common, Draconic
- **Challenge** 6

## Traits

***Aura of Command.*** The draconian radiates a commanding presence in a 20-foot-radius sphere centered on itself. A draconian in the aura that can see or hear the aurak can't be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and has advantage on saving throws made to avoid or end the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition on itself.

***Death Throes.*** When the draconian is reduced to 0 hit points, its magical essence lashes out as a ball of lightning at the closest creature within 30 feet of it before arcing out to up to two other creatures within 15 feet of the first. Each creature must make a DC 14 Dexterity saving throw. On a failed save, the creature takes `dice:2d8|noform|avg|text(9)` (`2d8`) lightning damage and is [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn. On a successful save, the creature takes half as much damage and isn't [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned).

***Spellcasting.*** The draconian casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 14):

**At will**: [invisibility](2-Mechanics/CLI/spells/invisibility.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md)

**1/day**: [dominate person](2-Mechanics/CLI/spells/dominate-person.md)

**2/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [sending](2-Mechanics/CLI/spells/sending.md)

## Actions

***Multiattack.*** The draconian makes three Rend or Energy Ray attacks.

***Rend.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d12+2|noform|avg|text(8)` (`1d12 + 2`) slashing damage.

***Energy Ray.*** *Ranged Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 60 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) force damage.

***Noxious Breath (Recharge 5-6).*** The draconian exhales a 15-foot cone of noxious gas. Each creature in that area must make a DC 14 Constitution saving throw. On a failed save, the creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) poison damage and gains 1 level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). On a successful save, the creature takes half as much damage, doesn't gain [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), and is immune to all draconians' Noxious Breath for 24 hours.
```
^statblock