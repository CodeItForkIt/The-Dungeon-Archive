---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/15
- monster/size/medium
- monster/type/fiend
aliases: ["Doomcaller"]
---
# Doomcaller
*Source: Grim Hollow: Lairs of Etharis p. 47*  

> [!quote]  
> 
> Despair, the end is nigh!

## Salvage

When slain, the eyes of a doomcaller harden into gems worth 2000 gp each.

When a creature holding one of these gems makes an attack roll, ability check, or saving throw, they can consume it to improve their fortunes. After the roll has been made, but before the GM has announced the result of the roll, the player can expend one gem and reroll the roll. Once done, the player must use the new result, the gem shatters and becomes worthless.

## Lore

- **DC 10 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** Doomcallers are powerful spellcasting fiends.  
- **DC 15 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** A doomcaller can summon succubi or barbed devils.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Doomcallers are resistant to cold, fire, lightning, and nonmagical weapons. They are immune to acid and poison.  

## Statblock

```ad-statblock
title: Doomcaller
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Doomcaller.webp#token)
*Medium fiend, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 150 (`20d8 + 60`)
- **Speed** 30 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|17 (+3)|17 (+3)|14 (+2)|12 (+1)|21 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +8, Intelligence +7, Wisdom +6, Charisma +10
- **Skills** Arcana +7, Deception +10, Insight +6, Perception +6, Persuasion +10, Religion +7
- **Senses** darkvision 120 ft., passive Perception 16
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all
- **Challenge** 15

## Traits

***Magic Resistance.*** The doomcaller has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The doomcaller is an 18th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 18, `dice:1d20+10|noform|text(+10)` to hit with spell attacks). It has the following spells prepared:

**Cantrips (at will)**: [fire bolt](2-Mechanics/CLI/spells/fire-bolt.md), [hunter sense](2-Mechanics/CLI/spells/hunter-sense-ghloe.md), [message](2-Mechanics/CLI/spells/message.md), [shocking grasp](2-Mechanics/CLI/spells/shocking-grasp.md), [true strike](2-Mechanics/CLI/spells/true-strike.md)

**1st level (4 slots)**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [magic missile](2-Mechanics/CLI/spells/magic-missile.md), [shield](2-Mechanics/CLI/spells/shield.md)

**2nd level (3 slots)**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [misty step](2-Mechanics/CLI/spells/misty-step.md)

**3rd level (3 slots)**: [bestow curse](2-Mechanics/CLI/spells/bestow-curse.md), [fireball](2-Mechanics/CLI/spells/fireball.md)

**4th level (3 slots)**: [banishment](2-Mechanics/CLI/spells/banishment.md), [consume mind](2-Mechanics/CLI/spells/consume-mind-ghloe.md)

**5th level (3 slots)**: [magic mirror](2-Mechanics/CLI/spells/magic-mirror-ghloe.md), [scrying](2-Mechanics/CLI/spells/scrying.md)

**6th level (1 slots)**: [disintegrate](2-Mechanics/CLI/spells/disintegrate.md)

**7th level (1 slots)**: [arboreal curse](2-Mechanics/CLI/spells/arboreal-curse-ghloe.md)

**8th level (1 slots)**: [mind blank](2-Mechanics/CLI/spells/mind-blank.md) *

**9th level (1 slots)**: [gate](2-Mechanics/CLI/spells/gate.md)

*The doomcaller casts this spell on itself before combat.

## Actions

***Slam.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage, and the target has disadvantage on their next attack roll. Additionally, all attacks against the target by allies of the doomcaller are made with advantage until the start of the doomcaller's next turn.

***Summon Fiend (1/Day).*** The doomcaller chooses what to summon and attempts a magical summoning. A doomcaller has a 60 percent chance of summoning `dice:1d6|noform|avg` (`1d6`) succubi or `dice:1d4|noform|avg` (`1d4`) barbed devils. A summoned fiend appears in an unoccupied space within 60 feet of its summoner, does as it pleases, and can't summon other fiends. The summoned fiend remains for 1 minute, until it or its summoner dies, or until its summoner takes a bonus action to dismiss it.

## Reactions

***Ill Fortune (3/Day).*** When a creature the doomcaller can see makes an attack roll, a saving throw, or an ability check, the doomcaller can roll a `dice:d20|noform|avg` (`d20`) and choose to use this roll in place of the attack roll, saving throw, or ability check.
```
^statblock