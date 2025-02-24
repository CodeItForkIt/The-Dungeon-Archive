---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/19
- monster/size/large
- monster/type/fiend/demon
aliases: ["Raklupis Spyder-Fiend"]
---
# Raklupis Spyder-Fiend
*Source: Vecna: Eve of Ruin p. 236*  

Raklupis spyder-fiends have hard, smooth shells and gleaming spines. With luxuriantly furry wolf heads, powerful arms, and alluring voices, raklupises are the only spyder-fiends that might be called majestic. They create delicate web globes, which they fill with their venom and hurl at foes. Raklupises are keen strategists, and most of them command legions of lesser spyder-fiends.

## Spyder-Fiends

Demonic beasts that combine the worst attributes of wolves and spiders, spyder-fiends scuttle about with bloated, spiderlike bodies and gnash with wolflike heads. Spyder-fiends are usually coated with gore, as brutal killing is their favorite pursuit. They spin durable webs and are ingenious in how they employ their webs against prey.

Spyder-fiends are organized into a hierarchy based on might and cunning, with higher-ranked spyder-fiends dominating lower ranks. Spyder-fiends of equivalent rank scheme against each other for advancement and eagerly turn against one another if treachery can improve their position.

Spyder-fiends loyally serve their general, Miska the Wolf-Spider. While they were rarely seen during Miska's imprisonment in Pandemonium, they have become increasingly active as Miska struggles to free himself in Pandesmos.

## Statblock

```ad-statblock
title: Raklupis Spyder-Fiend
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Raklupis%20Spyder-Fiend.webp#token)
*Large fiend (demon), typically  Chaotic Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 210 (`28d10 + 56`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|20 (+5)|14 (+2)|18 (+4)|16 (+3)|23 (+6)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +11, Constitution +8, Wisdom +9
- **Skills** Perception +9, Stealth +11
- **Senses** truesight 120 ft., passive Perception 19
- **Damage Immunities** cold, fire, lightning, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, telepathy 120 ft.
- **Challenge** 19

## Traits

***Magic Resistance.*** The raklupis has advantage on saving throws against spells and other magical effects.

***Spider Climb.*** The raklupis can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Sense.*** When in contact with a web, the raklupis knows the exact location of any other creature in contact with the same web.

***Web Walker.*** The raklupis ignores movement restrictions caused by webbing.

***Spellcasting.*** The raklupis casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 20).

**At will**: [Disguise Self](2-Mechanics/CLI/spells/disguise-self.md), [Invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only), [Mage Hand](2-Mechanics/CLI/spells/mage-hand.md), [Minor Illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**2/day each**: [Darkness](2-Mechanics/CLI/spells/darkness.md), [Dominate Monster](2-Mechanics/CLI/spells/dominate-monster.md), [Mass Suggestion](2-Mechanics/CLI/spells/mass-suggestion.md), [Telekinesis](2-Mechanics/CLI/spells/telekinesis.md), [Teleport](2-Mechanics/CLI/spells/teleport.md)

## Actions

***Multiattack.*** The raklupis makes a Bite attack and two Serrated Sword attacks. It can use Venom Globe in place of one of these attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) piercing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) poison damage. If the target is a creature, it must succeed on a DC 20 Constitution saving throw or have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 minute. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, a creature has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition and can't regain hit points. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Serrated Sword.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6+5|noform|avg|text(19)` (`4d6 + 5`) slashing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) poison damage.

***Venom Globe.*** *Ranged Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, range 60/180 ft., one target. *Hit:* `dice:10d8|noform|avg|text(45)` (`10d8`) poison damage.

## Bonus Actions

***Demand Loyalty.*** The raklupis magically ends the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) conditions on itself and on any number of allies within 60 feet of itself.
```
^statblock