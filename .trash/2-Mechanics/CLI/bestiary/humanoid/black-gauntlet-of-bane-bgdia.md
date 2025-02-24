---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgdia
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
aliases: ["Black Gauntlet of Bane"]
---
# Black Gauntlet of Bane
*Source: Baldur's Gate: Descent Into Avernus p. 235*  

Bane's devoted followers are warriors who seek to rule through martial strength and intimidation, cruel tyrants who use threats and gifts as needed to ensure loyalty. They enslave those too weak to resist them and shower the strong with gifts and promises of power to turn them into loyal vassals.

## Cruel Tyrants

Whenever Bane's followers gain power, they institute draconian measures to ensure that their rule is unquestioned. They stamp out all opposition while richly rewarding those who swear fealty.

## Warrior Cult

Cultists of Bane are warriors who wear heavy armor and wield maces, swords, spears, and crossbows. They paint the right gauntlet of their armor black in honor of their patron. Bane's clerics wield black maces with heads shaped to look like a closed fist.

## Cult Ranks

Bane's cultists operate according to strict military hierarchies. The lowest rank consists of the fists of Bane, foot soldiers who obey all orders without hesitation. They are led by iron consuls, cunning field officers who excel at coordinating the fists in combat. The black gauntlets are the priests who command the consuls.

## Statblock

```ad-statblock
title: Black Gauntlet of Bane
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGDIA/Black%20Gauntlet%20of%20Bane.webp#token)
*Medium humanoid (human), Lawful Evil*

- **Armor Class** 16 ([chain mail](2-Mechanics/CLI/items/chain-mail.md))
- **Hit Points** 51 (`6d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|11 (+0)|18 (+4)|12 (+1)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +5
- **Skills** Intimidation +7, Perception +5
- **Senses** passive Perception 15
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common
- **Challenge** 6

## Traits

***Aura of Terror.*** When a hostile creature within 5 feet of the black gauntlet makes an attack roll or a saving throw, it has disadvantage on the roll. Creatures that are immune to the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition are immune to this trait.

***Tactical Discipline.*** The black gauntlet has advantage on all ability checks and saving throws made during combat.

***Spellcasting.*** The black gauntlet is a 5th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 15, `dice:1d20+7|noform|text(+7)` to hit with spell attacks). It has the following cleric spells prepared:

**Cantrips (at will)**: [guidance](2-Mechanics/CLI/spells/guidance.md), [sacred flame](2-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1st level (4 slots)**: [bane](2-Mechanics/CLI/spells/bane.md), [bless](2-Mechanics/CLI/spells/bless.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md) (see "Actions" below)

**2nd level (3 slots)**: [blindness/deafness](2-Mechanics/CLI/spells/blindness-deafness.md), [hold person](2-Mechanics/CLI/spells/hold-person.md), [silence](2-Mechanics/CLI/spells/silence.md)

**3rd level (2 slots)**: [sending](2-Mechanics/CLI/spells/sending.md), [spirit guardians](2-Mechanics/CLI/spells/spirit-guardians.md)

## Actions

***Multiattack.*** The black gauntlet makes two attacks with its mace.

***Mace.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) bludgeoning damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage.

***Guiding Bolt (1st-Level Spell; Requires a Spell Slot).*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one creature. *Hit:* `dice:4d6|noform|avg|text(14)` (`4d6`) radiant damage, and the next attack roll made against the target before the end of the black gauntlet's next turn has advantage. If the black gauntlet casts this spell using a spell slot of 2nd level or higher, the damage increases by `dice:1d6|noform|avg` (`1d6`) for each slot level above 1st.
```
^statblock