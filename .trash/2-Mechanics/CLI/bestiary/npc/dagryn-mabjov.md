---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/dwarf
aliases: ["Dagryn"]
---
# Dagryn
*Source: Minsc and Boo's Journal of Villainy p. 110*  

> [!quote] A quote from Volo  
> 
> I've long pursued the story of the dwarf who could change into a dragon. That Minsc and his ridiculous pet could track him down first is infuriating!

Dagryn appears as an old, stooped dwarf, crippled with age and afflictions. Long ago, however, he went by another name... and another form.

Originally, Dagryn was a powerful black dragon that hunted the Underdark, feasting on everything from beholders to drow to illithid. But he was particularly fond of dwarves, whom he considered a delicacy. Supremely arrogant, Dagryn believe no denizens of the Underdark could challenge his power, until he had the misfortune of angering a coven of hags.

The hags trapped and killed the great wyrm, but instead of leaving him for dead, they reincarnated him in the form of a dwarf—a twisted joke on the once fearsome creature. In a final mockery of his former glory, they branded him with the name Dagryn—a bastardized echo of the mighty beast he once had been. Dagryn has now lived so many years as a dwarf that the memories of his life before the reincarnation have mostly faded. In addition to forgetting his true name, he no longer remembers his origin world, though he knows that Faerûn is not where he was born.

In the early years after his transformation, Dagryn discovered another cruel quirk of the hag's curse. After several years his wretched existence as a lowly dwarf became unbearable, and Dagryn was driven to suicide. But upon his death, he woke to discover his body had been restored to its original dragon form. However, his joy was short lived—after 24 hours he once again shifted back into his dwarven shape... but now he had a malformed leg, giving him a painful limp.

Over the next decades, the true scope of the horror inflicted upon him became apparent. Each time his dwarven body was killed, he would be reborn as a dragon for a single day. And each time he turned back into a dwarf he would find himself afflicted with some new infirmity: arthritic joints; rotting teeth; punishing migraines; constant ulcers.

Dagryn now dreads adding new ailments to the relentless, crippling pain of his dwarven body. Whenever he is killed—a somewhat frequent occurrence, as a frail, old dwarf is an easy target—he spends his time as a dragon unleashing mad vengeance upon the world in an orgy of death, destruction, and mayhem. As a result, he has developed two very distinct and contrasting personalities: the timid, subservient dwarf and the raging, hate-filled dragon.

```ad-statblock
title: Dagryn
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Dagryn.webp#token)
*Medium humanoid (dwarf), Neutral Evil*

- **Armor Class** 19 ([splint](2-Mechanics/CLI/items/splint-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 84 (`13d8 + 26`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)| 8 (-1)|14 (+2)|14 (+2)|13 (+1)|17 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +5, Performance +5, Persuasion +5
- **Senses** darkvision 120 ft., passive Perception 11
- **Damage Resistances** poison
- **Damage Immunities** acid
- **Languages** Common, Draconic, Dwarvish, Undercommon
- **Challenge** 4

## Traits

***Draconic Transformation.*** When Dagryn drops to 0 hit points, instead of falling [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious), he transforms into his dragon form. He immediately gains all the statistics of an [adult black dragon](2-Mechanics/CLI/bestiary/dragon/adult-black-dragon.md) with the exception that his size is Medium, and has the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition. At the start of his next turn, he grows to Large size, but remains [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned). At the start of his subsequent turn, Dagryn grows to Huge size and is no longer [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned). Dagryn remains in his dragon form for 24 hours whereupon he reverts to this stat block.

***Dwarven Resilience.*** Dagryn has advantage on saving throws against poison, spells, and illusions, as well as to resist being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed).

***Spellcasting.*** Dagryn casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 13):

**At will**: [alter self](2-Mechanics/CLI/spells/alter-self.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [levitate](2-Mechanics/CLI/spells/levitate.md), [major image](2-Mechanics/CLI/spells/major-image.md), [vicious mockery](2-Mechanics/CLI/spells/vicious-mockery.md)

**1/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [seeming](2-Mechanics/CLI/spells/seeming.md)

**2/day each**: [bane](2-Mechanics/CLI/spells/bane.md), [fear](2-Mechanics/CLI/spells/fear.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md), [misty step](2-Mechanics/CLI/spells/misty-step.md)

## Actions

***Club.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+1|noform|avg|text(3)` (`1d4 + 1`) bludgeoning damage.

***Eruption.*** *Ranged Spell Attack:* `dice:1d20+5|noform|text(+5)` to hit, range 120 ft., one target. *Hit:* `dice:2d10+3|noform|avg|text(14)` (`2d10 + 3`) acid damage.

## Bonus Actions

***Invisibility (Recharges after a Short or Long Rest).*** Dagryn magically turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) for 1 hour or until he attacks or casts a spell. Any equipment Dagryn wears or carries turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) with him.
```
^statblock