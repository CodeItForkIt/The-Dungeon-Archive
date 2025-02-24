---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/7
- monster/size/large
- monster/type/celestial
aliases: ["Lesser Gluttony Seraph"]
---
# Lesser Gluttony Seraph
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
title: Lesser Gluttony Seraph
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Lesser%20Gluttony%20Seraph.webp#token)
*Large celestial, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 114 (`12d10 + 48`)
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|14 (+2)|19 (+4)|12 (+1)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +7, Wisdom +5, Charisma +5
- **Skills** Insight +5, Perception +5
- **Senses** darkvision 120 ft., passive Perception 15
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 7

## Traits

***Magic Resistance.*** The seraph has advantage on saving throws against spells and other magical effects.

***Seraphic Weapons.*** The seraph's weapon attacks are magical. When the seraph hits with any weapon, the weapon deals an extra (`dice:1d8|noform|avg` (`1d8`)) radiant damage (included in the attacks).

***Innate Spellcasting.*** The seraph's spellcasting ability is Charisma (spell save DC 13). The seraph can innately cast the following spells, using only verbal components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [light](2-Mechanics/CLI/spells/light.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day each**: [create food and water](2-Mechanics/CLI/spells/create-food-and-water.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** The seraph makes three attacks, only one of which can be a bite.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) piercing damage and `dice:1d8|noform|avg|text(4)` (`1d8`) radiant damage. If the target is a Medium or smaller creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the seraph can't bite another target.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d4+4|noform|avg|text(9)` (`2d4 + 4`) slashing damage and `dice:1d8|noform|avg|text(4)` (`1d8`) radiant damage.

***Tongue.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 15 ft., one creature. *Hit:* `dice:1d4+4|noform|avg|text(6)` (`1d4 + 4`) bludgeoning damage and `dice:1d8|noform|avg|text(4)` (`1d8`) radiant damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15) and pulled to within 5 feet of the seraph. Until the grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the seraph can't use its tongue or bite on another target.
```
^statblock