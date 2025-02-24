---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/19
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/wizard
aliases: ["Tasha the Witch"]
---
# Tasha the Witch
*Source: Vecna: Eve of Ruin p. 252*  

Tasha's path to greatness began when she was adopted by the arch-hag Baba Yaga, who named her Natasha. Tasha went on to create various spells, including Tasha's Hideous Laughter, and her magic-fueled ambitions brought her into contact with demons and demon lords, which she subjugated and used against her enemies. On the Material Plane, she became known as Iggwilv the Witch Queen and wrote the Demonomicon of Iggwilv, the greatest of all treatises on the Abyss and its demonic inhabitants. In recent years, Tasha sequestered herself in the Feywild, achieving incredible power and slowly turning into a Fey creature. Tasha became Zybilna, archfey of the domain of Prismeer.

## Answering the Summons

When Zybilna received Alustriel Silverhand's summons to combat Vecna, the archfey was sorely needed in Prismeer. As a compromise, and to honor Tasha's friendship with Alustriel, Zybilna sent a version of herself from the past to Alustriel's side. The Tasha who appears in*Vecna: Eve of Ruin*is a powerful wizard, though she is not yet a witch queen or an archfey.

## Statblock

```ad-statblock
title: Tasha the Witch
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Tasha%20the%20Witch.webp#token)
*Medium humanoid (human, wizard), Chaotic Neutral*

- **Armor Class** 19 ([robe of the archmagi](2-Mechanics/CLI/items/robe-of-the-archmagi.md))
- **Hit Points** 210 (`28d8 + 84`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|18 (+4)|17 (+3)|23 (+6)|12 (+1)|22 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Intelligence +12, Wisdom +7, Charisma +12
- **Skills** Arcana +18, History +12, Persuasion +12
- **Senses** passive Perception 11
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Abyssal, Celestial, Common, Draconic, Elvish, Infernal, Sylvan
- **Challenge** 19

## Traits

***Legendary Resistance (3/Day).*** If Tasha fails a saving throw, she can choose to succeed instead.

***Magic Resistance.*** Tasha has advantage on saving throws against spells and other magical effects. (This trait is bestowed by her Robe of the Archmagi.)

***Special Equipment.*** Tasha wears a Robe of the Archmagi.

***Spellcasting.*** Tasha casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 22, `dice:1d20+14|noform|text(+14)` to hit with spell attacks):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic.md), [Disguise Self](2-Mechanics/CLI/spells/disguise-self.md), [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic.md), [Light](2-Mechanics/CLI/spells/light.md), [Mage Hand](2-Mechanics/CLI/spells/mage-hand.md), [Message](2-Mechanics/CLI/spells/message.md), [Prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md), [Tasha's Hideous Laughter](2-Mechanics/CLI/spells/tashas-hideous-laughter.md)

**1/day each**: [Maze](2-Mechanics/CLI/spells/maze.md), [Telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

**2/day**: [Polymorph](2-Mechanics/CLI/spells/polymorph.md)

## Actions

***Multiattack.*** Tasha makes two Caustic Blast attacks and uses Psychic Whip once.

***Caustic Blast.*** *Melee or Ranged Spell Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* `dice:6d4+6|noform|avg|text(21)` (`6d4 + 6`) acid damage.

***Psychic Whip.*** Tasha psychically lashes out at one creature she can see within 90 feet of herself. The target must make a DC 20 Intelligence saving throw. On a failed save, the target takes `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage and has the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of Tasha's next turn. On a successful save, the target takes half as much damage only.

## Bonus Actions

***Abyssal Visage (2/Day).*** For 1 minute, Tasha gains a flying speed of 30 feet, is immune to poison damage and the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition, and has advantage on attack rolls against any creature that doesn't have all its hit points. These benefits end early if Tasha has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition or if she uses another bonus action to dismiss them.

## Reactions

***Arcane Rebuff.*** Immediately after Tasha takes damage, she unleashes arcane energy in a 10-foot-radius sphere centered on herself. All other creatures in that area must make a DC 20 Dexterity saving throw, taking `dice:3d12|noform|avg|text(19)` (`3d12`) lightning damage on a failed save or half as much damage on a successful one. Tasha then teleports, along with any equipment she is wearing or carrying, to an unoccupied space she can see within 60 feet of herself.
```
^statblock