---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/0
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Magewright"]
---
# Magewright
*Source: Eberron: Rising from the Last War p. 318*  

In Khorvaire, magic is part of everyday life. A chef might use [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md) to heat and season food, while a blacksmith uses [mending](2-Mechanics/CLI/spells/mending.md) to perform minor repairs and [guidance](2-Mechanics/CLI/spells/guidance.md) to help inspire their work. Those who work minor magic into their labors are called magewrights.

Far more limited in magical power than a typical spellcaster, a magewright is dedicated to learning a handful of spells, and magewrights cast their non-cantrip spells as rituals—even spells that can't normally be cast in this way. Most magewright rituals take 10 minutes to perform, but certain complex rituals can take up to 1 hour. However long the ritual takes, it requires extra material components, usually in the form of dragonshards.

## Creating a Magewright

The magewright stat block provides the baseline statistics for a magewright. You then add to that baseline by choosing a specialty from the Magewright Specialties table, or roll for one. The specialty determines additional spells the magewright knows, including ones that can be cast only as rituals. The specialty also gives the magewright more proficiencies.

**Magewright Specialties**

`dice: [](magewright-erlw.md#^magewright-specialties)`

| dice: d8 | Specialty | Spells | Proficiencies |
|----------|-----------|--------|---------------|
| 1 | Artisan | [Guidance](2-Mechanics/CLI/spells/guidance.md), [mending](2-Mechanics/CLI/spells/mending.md) | One type of artisan's tools |
| 2 | Entertainer | [Minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md). Ritual only: [disguise self](2-Mechanics/CLI/spells/disguise-self.md). | [Performance](2-Mechanics/CLI/rules/skills.md#Performance) (+3) |
| 3 | Healer | [Resistance](2-Mechanics/CLI/spells/resistance.md), [spare the dying](2-Mechanics/CLI/spells/spare-the-dying.md). Ritual only: [detect poison and disease](2-Mechanics/CLI/spells/detect-poison-and-disease.md), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md) (1 hour). | [Medicine](2-Mechanics/CLI/rules/skills.md#Medicine) (+4), [herbalism kit](2-Mechanics/CLI/items/herbalism-kit.md) |
| 4 | Lamplighter | [Light](2-Mechanics/CLI/spells/light.md). Ritual only: [continual flame](2-Mechanics/CLI/spells/continual-flame.md) (1 hour). | [Tinker's tools](2-Mechanics/CLI/items/tinkers-tools.md) |
| 5 | Locksmith | [Mending](2-Mechanics/CLI/spells/mending.md). Ritual only: [arcane lock](2-Mechanics/CLI/spells/arcane-lock.md) (1 hour), [knock](2-Mechanics/CLI/spells/knock.md). | [Thieves' tools](2-Mechanics/CLI/items/thieves-tools.md), [tinker's tools](2-Mechanics/CLI/items/tinkers-tools.md) |
| 6 | Mediator | [Guidance](2-Mechanics/CLI/spells/guidance.md). Ritual only: [comprehend languages](2-Mechanics/CLI/spells/comprehend-languages.md), [zone of truth](2-Mechanics/CLI/spells/zone-of-truth.md). | [Insight](2-Mechanics/CLI/rules/skills.md#Insight) (+4), [Persuasion](2-Mechanics/CLI/rules/skills.md#Persuasion) (+3) |
| 7 | Medium | [Minor illusion](2-Mechanics/CLI/spells/minor-illusion.md). Ritual only: [speak with dead](2-Mechanics/CLI/spells/speak-with-dead.md). | [Deception](2-Mechanics/CLI/rules/skills.md#Deception) (+3), [Religion](2-Mechanics/CLI/rules/skills.md#Religion) (+4) |
| 8 | Oracle | [Guidance](2-Mechanics/CLI/spells/guidance.md). Ritual only: [augury](2-Mechanics/CLI/spells/augury.md), [divination](2-Mechanics/CLI/spells/divination.md) (1 hour). | [History](2-Mechanics/CLI/rules/skills.md#History) (+4), [Religion](2-Mechanics/CLI/rules/skills.md#Religion) (+4) |
^magewright-specialties

## Statblock

```ad-statblock
title: Magewright
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Magewright.webp#token)
*Medium humanoid (any race), Any alignment*

- **Armor Class** 11
- **Hit Points** 9 (`2d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|13 (+1)|10 (+0)|14 (+2)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Arcana +4
- **Senses** passive Perception 12
- **Languages** Common plus any two languages
- **Challenge** 0

***Spellcasting.*** The magewright's spellcasting ability is Intelligence (spell save DC 12). To cast one of its rituals, the magewright must provide additional material components whose value in gold pieces is 20 times the spell's level. These components are consumed when the ritual is finished. The magewright knows the following spells:

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

## Actions

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) piercing damage.
```
^statblock