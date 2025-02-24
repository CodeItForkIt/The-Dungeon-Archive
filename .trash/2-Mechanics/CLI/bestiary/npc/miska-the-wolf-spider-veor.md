---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/24
- monster/size/huge
- monster/type/fiend/demon
aliases: ["Miska the Wolf-Spider"]
---
# Miska the Wolf-Spider
*Source: Vecna: Eve of Ruin p. 247*  

Miska the Wolf-Spider is a legendary demon lord and master of battlefield strategy. He has the lower body of a massive armored spider, four arms, and two enormous wolf heads that drip poison. Yet Miska's greatest strength is his cunning mind.

## History

Ages ago, Miska led the hordes of Chaos against the forces of Law at the behest of his patron, the enigmatic Queen of Chaos. It seemed Miska's domination couldn't be stopped.

In desperation, Miska's opponents crafted an artifact to bind him in an extraplanar prison. This rod broke apart after sealing him in Pandemonium, scattering across the planes and becoming known as the Rod of Seven Parts. The rod is the key to releasing Miska from his long imprisonment.

## Statblock

```ad-statblock
title: Miska the Wolf-Spider
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Miska%20the%20Wolf-Spider.webp#token)
*Huge fiend (demon), Chaotic Evil*

- **Armor Class** 21 (natural armor)
- **Hit Points** 399 (`38d12 + 152`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|18 (+4)|19 (+4)|18 (+4)|21 (+5)|22 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +11, Constitution +11, Wisdom +12
- **Skills** Insight +12, Perception +12, Stealth +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, telepathy 120 ft.
- **Challenge** 24

## Traits

***Foul Ichor.*** A creature that hits Miska with a melee weapon attack takes `dice:2d6|noform|avg|text(7)` (`2d6`) poison damage.

***Legendary Resistance (3/Day).*** If Miska fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Miska has advantage on saving throws against spells and other magical effects.

***Spider Climb.*** Miska can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Sense.*** When in contact with a web, Miska knows the exact location of any other creature in contact with the same web.

***Web Walker.*** Miska ignores movement restrictions caused by webbing.

***Spellcasting.*** Miska casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 21):

**At will**: [Disguise Self](2-Mechanics/CLI/spells/disguise-self.md), [Invisibility](2-Mechanics/CLI/spells/invisibility.md), [Mage Hand](2-Mechanics/CLI/spells/mage-hand.md), [Minor Illusion](2-Mechanics/CLI/spells/minor-illusion.md), [Web](2-Mechanics/CLI/spells/web.md)

**2/day each**: [Dominate Monster](2-Mechanics/CLI/spells/dominate-monster.md), [Mass Suggestion](2-Mechanics/CLI/spells/mass-suggestion.md), [Mirror Image](2-Mechanics/CLI/spells/mirror-image.md), [Telekinesis](2-Mechanics/CLI/spells/telekinesis.md), [Teleport](2-Mechanics/CLI/spells/teleport.md)

## Actions

***Multiattack.*** Miska makes one Lupine Bite attack and two Trident of Chaos attacks.

***Lupine Bite.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) piercing damage plus `dice:6d8|noform|avg|text(27)` (`6d8`) poison damage. If the target is a creature, it must succeed on a DC 21 Constitution saving throw or have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition for 1 minute. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, a creature has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition and can't regain hit points. A [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Trident of Chaos.*** *Melee Weapon Attack:* `dice:1d20+13|noform|text(+13)` to hit, reach 15 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) force damage.

## Bonus Actions

***Demand Loyalty.*** Miska magically ends the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) conditions on himself and on any of his allies within 120 feet of himself.

## Legendary Actions

***Howl.*** Miska utters a bloodthirsty howl at one creature within 120 feet of himself that isn't a Fiend. The target must succeed on a DC 20 Wisdom saving throw or take `dice:2d12|noform|avg|text(13)` (`2d12`) psychic damage.

***Skitter.*** Miska moves up to his speed without provoking opportunity attacks.

***Cast a Spell (Costs 2 Actions).*** Miska uses Spellcasting.
```
^statblock