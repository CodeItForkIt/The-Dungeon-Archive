---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/7
- monster/size/medium
- monster/type/celestial
aliases: ["Lesser Avarice Seraph"]
---
# Lesser Avarice Seraph
*Source: Grim Hollow: Lairs of Etharis p. 94*  

> [!quote]  
> 
> Don't go to the temple. Something sinister has claimed it. Seek shelter elsewhere.

## Salvage

An avarice seraph's metal-tipped feathers can be sold. Those of the lesser seraph are worth 250 gp, while those of the seraph are worth 1,000 gp.

Someone who has proficiency with alchemist's supplies can melt the metal on the feathers of an avarice seraph and use some feathers as fletching to make one arrow of celestial slaying for a lesser seraph, or four such arrows from the seraph. Making one arrow takes 7 days of work, reagents worth 1,000 gp, and a successful DC 17 Intelligence or Wisdom check.

The saliva of a gluttony seraph functions as antitoxin—three doses can be collected from a lesser seraph, while ten can be gathered from a seraph. Someone who has proficiency with alchemist's supplies or an herbalism kit can mix two doses of this saliva with reagents worth 50 gp and brew the mixture for 4 hours. The resulting elixir affects the imbiber as a protection from poison spell, curing a random poison in the drinker's system.

## Lore

- **DC 10 Intelligence ([History](2-Mechanics/CLI/rules/skills.md#History)).** The disavowed are seraphs fallen to evil. Each still retains a measure of its celestial power.  
- **DC 15 Intelligence ([Religion](2-Mechanics/CLI/rules/skills.md#Religion)).** From their celestial heritage, disavowed retain magic resistance and resistance to nonmagical attacks, as well as immunity to being charmed, exhausted, and frightened. Even in a fallen state, the seraph imparts magic and radiant damage to its attacks. Gluttony seraphs are also immune to poison.  
- **DC 20 Intelligence ([Arcana](2-Mechanics/CLI/rules/skills.md#Arcana)).** Avarice seraphs can rouse the greed in any creature. Huge gluttony seraphs can swallow and digest people, although their lesser kin can't.  

## Statblock

```ad-statblock
title: Lesser Avarice Seraph
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lesser%20Avarice%20Seraph.webp#token)
*Medium celestial, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 105 (`14d8 + 42`)
- **Speed** 30 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|18 (+4)|17 (+3)|13 (+1)|15 (+2)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6, Wisdom +5, Charisma +6
- **Skills** Deception +6, Insight +5, Perception +5
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all, telepathy 120 ft.
- **Challenge** 7

## Traits

***Magic Resistance.*** The seraph has advantage on saving throws against spells and other magical effects.

***Seraphic Weapons.*** The seraph's weapon attacks are magical. When the seraph hits with any weapon, the weapon deals an extra (`dice:2d8|noform|avg` (`2d8`)) radiant damage (included in the attack).

***Innate Spellcasting.*** The seraph's spellcasting ability is Charisma (spell save DC 14). The seraph can innately cast the following spells, using only verbal components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [light](2-Mechanics/CLI/spells/light.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [identify](2-Mechanics/CLI/spells/identify.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** The seraph makes three attacks.

***Scimitar.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage and `dice:2d8|noform|avg|text(9)` (`2d8`) radiant damage.

***Tempting Call.*** The seraph calls out a tempting promise to one creature that can hear it withing 30 feet. The creature must succeed on a DC 14 Charisma saving throw. On a failed save, the creature cannot take actions for 1 minute, as it dwells on the promise the seraph made. The target can repeat the saving throw at the end of each turn, ending the effect on a success. Each failed saving throw after the initial failure deals `dice:2d8|noform|avg|text(9)` (`2d8`) psychic damage to the target
```
^statblock