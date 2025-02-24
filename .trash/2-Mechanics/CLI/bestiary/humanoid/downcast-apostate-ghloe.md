---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/11
- monster/size/medium
- monster/type/humanoid/downcast
aliases: ["Downcast Apostate"]
---
# Downcast Apostate
*Source: Grim Hollow: Lairs of Etharis p. 49*  

> [!quote]  
> 
> To assume the downcast are good at heart is foolish. Many still cling to delusions of grandeur and do anything to maintain them.

## Salvage

The recently deceased body of a downcast can be used in a ritual to unlock magical power. This ritual takes 16 hours to complete and requires candles, chalk, incense, silver, and other reagents worth 2,000 gp. Upon completion of this ritual, the downcast's body disintegrates, and the ritualist can choose one benefit.

- **Life Force.** The ritualist's maximum hit points increase by 2 per level (or Hit Die) the ritualist has. Each time the ritualist gains a level (or Hit Die), the ritualist's hit point maximum increases by 2. Also, the ritualist's natural lifespan increases by 250 years.  
- **Magic Power.** The ritualist learns the thaumaturgy cantrip and gains additional benefits based on the type of downcast sacrificed, as follows.  

    *Aurelian*: The ritualist's Charisma score increases by 1, to a maximum of 20. Once per day, the ritualist can cast cure wounds as a 1st level spell.  

    *Galiant*: The ritualist's Constitution score increases by 1, to a maximum of 20. Once per day, the ritualist can cast shield of faith as a 1st level spell.  

    *Maliganti*: The ritualist's Strength score increases by 1, to a maximum of 20. Once per day, the ritualist can cast branding smite as a 1st level spell.  

    *Ulmyrite*: The ritualist's Intelligence score increases by 1, to a maximum of 20. Once per day, the ritualist can cast detect magic.  
- **Resurrection.** Upon finishing the ritual, the ritualist can cast resurrection without expending a spell slot or providing any other components.  

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The downcast were once immortal celestial servants to the gods. Each has inclinations and aptitudes based on the god they once served.  
- **DC 13 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** As a result of their divine nature, fallen though it might be, downcast have resistance to necrotic damage and limited access to innate magic.  
- **DC 15 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** The physical form of a downcast contains significant power from before their fallen state. A ritual requiring the sacrifice or corpse of a downcast can draw out this power.  

## Statblock

```ad-statblock
title: Downcast Apostate
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Downcast%20Apostate.webp#token)
*Medium humanoid (downcast), Any alignment*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 150 (`20d8 + 60`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|17 (+3)|13 (+1)|12 (+1)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +5, Charisma +8
- **Skills** Deception +8, Intimidation +8, Perception +5, Persuasion +8, Religion +5, Stealth +6
- **Senses** darkvision 120 ft., truesight 30 ft., passive Perception 15
- **Damage Resistances** necrotic
- **Languages** Celestial and two other languages
- **Challenge** 11

## Traits

***Apostate's Weapons.*** The downcast apostate's weapon attacks are magical.

***Innate Spellcasting.*** The downcast apostate's spellcasting ability is Charisma. The apostate can innately cast the following spells, requiring no material components:

**At will**: [alter self](2-Mechanics/CLI/spells/alter-self.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [jump](2-Mechanics/CLI/spells/jump.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

***Spellcasting.*** The downcast apostate is an 18th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 16, `dice:1d20+8|noform|text(+8)` to hit with spell attacks). It regains its expended spell slots when it finishes a short or long rest. It knows the following warlock spells:

**1/day each**: [glibness](2-Mechanics/CLI/spells/glibness.md), [mass suggestion](2-Mechanics/CLI/spells/mass-suggestion.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md), [power word kill](2-Mechanics/CLI/spells/power-word-kill.md)

**Cantrips (at will)**: [chill touch](2-Mechanics/CLI/spells/chill-touch.md), [light](2-Mechanics/CLI/spells/light.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [sacred flame](2-Mechanics/CLI/spells/sacred-flame.md)

**1st-5th level (4 slots)**: [counterspell](2-Mechanics/CLI/spells/counterspell.md), [cure wounds](2-Mechanics/CLI/spells/cure-wounds.md), [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [flame strike](2-Mechanics/CLI/spells/flame-strike.md), [fly](2-Mechanics/CLI/spells/fly.md), [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md), [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [insect plague](2-Mechanics/CLI/spells/insect-plague.md), [lesser restoration](2-Mechanics/CLI/spells/lesser-restoration.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md), [tongues](2-Mechanics/CLI/spells/tongues.md), [vampiric touch](2-Mechanics/CLI/spells/vampiric-touch.md), [wall of fire](2-Mechanics/CLI/spells/wall-of-fire.md)

## Actions

***Morningstar.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) bludgeoning damage and `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic or radiant damage (downcast apostate's choice).
```
^statblock