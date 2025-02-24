---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/wizard
aliases: ["Lohezet"]
---
# Lohezet
*Source: Dragonlance: Shadow of the Dragon Queen p. 205*  

A black-robed member of the Mages of High Sorcery, Lohezet is a scholar obsessed with extinct creatures and fallen empires. He views the Dragon Army as a way to recreate the glories of Ansalon's past. During the Dragon Armies' invasions of Khur and Kendermore, Lohezet's investigations of Istarian ruins revealed the location of the flying city of Onyari. He now travels with the Red Dragon Army, intent on finding the City of Lost Names and restoring it to the skies.

Lohezet employs the strategies of extinct poisonous predators in battle. His magical toxins wear down even the strongest foes, providing him with the opportunity to escape or reducing his enemies to discolored corpses.

```ad-statblock
title: Lohezet
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Lohezet.webp#token)
*Medium humanoid (human, wizard), Neutral Evil*

- **Armor Class** 12
- **Hit Points** 137 (`25d8 + 25`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|12 (+1)|20 (+5)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +5, Wisdom +6
- **Skills** Arcana +9, History +9, Medicine +6
- **Senses** passive Perception 12
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Dwarvish, Elvish, Infernal
- **Challenge** 12

## Traits

***Toxic Mastery.*** Lohezet ignores a creature's resistance to poison damage.

***Spellcasting.*** Lohezet casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [light](2-Mechanics/CLI/spells/light.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [arcane eye](2-Mechanics/CLI/spells/arcane-eye.md), [dominate person](2-Mechanics/CLI/spells/dominate-person.md), [wall of force](2-Mechanics/CLI/spells/wall-of-force.md)

**2/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md)

## Actions

***Multiattack.*** Lohezet makes three Withering Blast attacks and uses Miasma if it's available. He can replace one of the attacks with a use of Spellcasting.

***Withering Blast.*** *Melee or Ranged Spell Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft. or range 60 ft., one target. *Hit:* `dice:2d12+5|noform|avg|text(18)` (`2d12 + 5`) necrotic damage.

***Miasma (Recharge 4-6).*** Lohezet magically conjures a billowing cloud of purple fog in a 20-foot-radius sphere centered on a point within 120 feet of himself. The area within the sphere is heavily obscured, and when a creature starts its turn in the sphere or enters the sphere for the first time on a turn, it must make a DC 17 Constitution saving throw. On a failed save, the creature takes `dice:6d12|noform|avg|text(39)` (`6d12`) poison damage and is [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until the start of its next turn. On a successful save, the creature takes half as much damage and isn't [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned). The cloud lasts for 1 minute, until Lohezet ends it early (no action required), or until Lohezet uses this action again. A strong wind disperses the cloud.

## Reactions

***Noxious Rebuke (3/Day).*** When a creature within 60 feet of Lohezet damages him, Lohezet magically retaliates with a spray of foul, purple mist. The creature must make a DC 17 Constitution saving throw, taking `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock