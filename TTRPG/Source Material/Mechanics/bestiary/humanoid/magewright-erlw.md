---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/erlw
- monster/cr/0
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Magewright"]
---
# [Magewright](Mechanics\bestiary\humanoid/magewright-erlw.md)
*Source: Eberron: Rising from the Last War p. 318*  

In Khorvaire, magic is part of everyday life. A chef might use [prestidigitation](Mechanics/spells/prestidigitation.md) to heat and season food, while a blacksmith uses [mending](Mechanics/spells/mending.md) to perform minor repairs and [guidance](Mechanics/spells/guidance.md) to help inspire their work. Those who work minor magic into their labors are called magewrights.

Far more limited in magical power than a typical spellcaster, a magewright is dedicated to learning a handful of spells, and magewrights cast their non-cantrip spells as rituals—even spells that can't normally be cast in this way. Most magewright rituals take 10 minutes to perform, but certain complex rituals can take up to 1 hour. However long the ritual takes, it requires extra material components, usually in the form of dragonshards.

## Creating a Magewright

The magewright stat block provides the baseline statistics for a magewright. You then add to that baseline by choosing a specialty from the Magewright Specialties table, or roll for one. The specialty determines additional spells the magewright knows, including ones that can be cast only as rituals. The specialty also gives the magewright more proficiencies.

**Magewright Specialties**

`dice: [](magewright-erlw.md#^magewright-specialties)`

| dice: d8 | Specialty | Spells | Proficiencies |
|----------|-----------|--------|---------------|
| 1 | Artisan | [Guidance](Mechanics/spells/guidance.md), [mending](Mechanics/spells/mending.md) | One type of artisan's tools |
| 2 | Entertainer | [Minor illusion](Mechanics/spells/minor-illusion.md), [thaumaturgy](Mechanics/spells/thaumaturgy.md). Ritual only: [disguise self](Mechanics/spells/disguise-self.md). | [Performance](Mechanics/Rules/skills.md#Performance) (+3) |
| 3 | Healer | [Resistance](Mechanics/spells/resistance.md), [spare the dying](Mechanics/spells/spare-the-dying.md). Ritual only: [detect poison and disease](Mechanics/spells/detect-poison-and-disease.md), [lesser restoration](Mechanics/spells/lesser-restoration.md) (1 hour). | [Medicine](Mechanics/Rules/skills.md#Medicine) (+4), [herbalism kit](Mechanics/items/herbalism-kit.md) |
| 4 | Lamplighter | [Light](Mechanics/spells/light.md). Ritual only: [continual flame](Mechanics/spells/continual-flame.md) (1 hour). | [Tinker's tools](Mechanics/items/tinkers-tools.md) |
| 5 | Locksmith | [Mending](Mechanics/spells/mending.md). Ritual only: [arcane lock](Mechanics/spells/arcane-lock.md) (1 hour), [knock](Mechanics/spells/knock.md). | [Thieves' tools](Mechanics/items/thieves-tools.md), [tinker's tools](Mechanics/items/tinkers-tools.md) |
| 6 | Mediator | [Guidance](Mechanics/spells/guidance.md). Ritual only: [comprehend languages](Mechanics/spells/comprehend-languages.md), [zone of truth](Mechanics/spells/zone-of-truth.md). | [Insight](Mechanics/Rules/skills.md#Insight) (+4), [Persuasion](Mechanics/Rules/skills.md#Persuasion) (+3) |
| 7 | Medium | [Minor illusion](Mechanics/spells/minor-illusion.md). Ritual only: [speak with dead](Mechanics/spells/speak-with-dead.md). | [Deception](Mechanics/Rules/skills.md#Deception) (+3), [Religion](Mechanics/Rules/skills.md#Religion) (+4) |
| 8 | Oracle | [Guidance](Mechanics/spells/guidance.md). Ritual only: [augury](Mechanics/spells/augury.md), [divination](Mechanics/spells/divination.md) (1 hour). | [History](Mechanics/Rules/skills.md#History) (+4), [Religion](Mechanics/Rules/skills.md#Religion) (+4) |
^magewright-specialties

```statblock
"name": "Magewright (ERLW)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d8"
"stats":
- !!int "11"
- !!int "13"
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Arcana": !!int "4"
"senses": "passive Perception 12"
"languages": "Common plus any two languages"
"cr": "0"
"traits":
- "desc": "The magewright's spellcasting ability is Intelligence (spell save DC 12).\
    \ To cast one of its rituals, the magewright must provide additional material\
    \ components whose value in gold pieces is 20 times the spell's level. These components\
    \ are consumed when the ritual is finished. The magewright knows the following\
    \ spells:\n\nAt will: [mage hand](Mechanics/spells/mage-hand.md), [prestidigitation](Mechanics/spells/prestidigitation.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage."
  "name": "Dagger"
"source":
- "ERLW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Magewright.webp"
```
^statblock