---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/14
- monster/size/large
- monster/type/celestial
aliases: ["Avarice Seraph"]
---
# Avarice Seraph
*Source: Grim Hollow: Lairs of Etharis p. 93*  

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
title: Avarice Seraph
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Avarice%20Seraph.webp#token)
*Large celestial, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 199 (`19d10 + 95`)
- **Speed** 40 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|20 (+5)|20 (+5)|14 (+2)|17 (+3)|20 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +10, Wisdom +8, Charisma +10
- **Skills** Deception +10, Insight +8, Perception +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Resistances** radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all, telepathy 120 ft.
- **Challenge** 14

## Traits

***Magic Resistance.*** The seraph has advantage on saving throws against spells and other magical effects.

***Seraphic Weapons.*** The seraph's weapon attacks are magical. When the seraph hits with any weapon, the weapon deals an extra `dice:4d8|noform|avg` (`4d8`) radiant damage (included in the attack).

***Innate Spellcasting.*** The seraph's spellcasting ability is Charisma (spell save DC 18). The seraph can innately cast the following spells, using only verbal components:

**At will**: [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only), [light](2-Mechanics/CLI/spells/light.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [thaumaturgy](2-Mechanics/CLI/spells/thaumaturgy.md)

**1/day**: [zone of truth](2-Mechanics/CLI/spells/zone-of-truth.md)

**3/day each**: [identify](2-Mechanics/CLI/spells/identify.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

## Actions

***Multiattack.*** The seraph makes three attacks.

***Scimitar.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage, or `dice:1d6+5|noform|avg|text(8)` (`1d6 + 5`) slashing damage in Small or Medium form, and `dice:4d8|noform|avg|text(18)` (`4d8`) radiant damage.

***Change Shape.*** The seraph magically polymorphs into a Small or Medium humanoid, into a Large giant, or back into its true form. Other than its size, its statistics are the same in each form. It's clothing and scimitars change size to match its new form. If the seraph dies, it reverts to its true form, and its equipment to its normal size.

***Voice of Avarice.*** The seraph presents objects of desire, which can be illusions the seraph creates, to creatures of its choice. If those creatures are within 60 feet of the seraph, able to see it and the desirable objects, and able to hear the seraph, the creatures must make a DC 18 Wisdom saving throw or become [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by the seraph until the seraph is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) or fails to use a bonus action on its turn to continue to present and speak about the desirable objects.

While [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) in this way, a target can take no reactions and can use its action only to Dash. If the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target is more than 5 feet from the seraph, the target must move as far as it can toward the seraph, trying to come within 5 feet. The target avoids obvious danger, including opportunity attacks. If the target can't avoid such danger, the target can repeat the saving throw before entering the dangerous area. While an affected creature is within 5 feet of the seraph, the creature can't take reactions and spends its turns staring at the desirable objects.

The target also repeats the saving throw if the target is subjected to a harmful effect, if the target can't see or hear the seraph, and at the end of each of the target's turns. If a creature's saving throw is successful, the effect ends for it. A target that successfully saves is immune to the Voice of Avarice of this seraph or any lesser seraph for the next 24 hours.
```
^statblock