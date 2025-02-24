---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/15
- monster/size/large
- monster/type/aberration
aliases: ["Phaerimm"]
---
# Phaerimm
*Source: Minsc and Boo's Journal of Villainy p. 145*  

Highly intelligent, phaerimms are malevolent aberrations that dwell deep beneath the surface of the world. Natural spellcasters, they delight in bringing pain and suffering to others. It is said phaerimms would willingly wipe every other being from existence, save for the fact they would then lack slaves to torture for sport.

## Monstrous Horrors

Phaerimms are hideous looking creatures—bulbous bodies with spindly arms and legs, topped by a gaping maw filled with row upon row of razor-sharp teeth. Their evil magic drains life and moisture from the natural world, and the Anauroch Desert was created through extensive use of their powers.

## Mental Enslavement

A phaerimm's mind-controlling abilities rival those of any mind flayer or beholder. Extremely solitary beings, they surround themselves with a retinue of mentally dominated creatures that serve as bodyguards, soldiers, and hunters. When these thralls cease to be useful, they are slaughtered and devoured by their phaerimm master. The phaerimm language is incomprehensible to humanoids, even with the use of magical assistance. However, a phaerimm can use telepathic magic to communicate with other beings through its slaves, though due to their solitary existence they seldom have need to communicate at all. The only real exception occurs on those rare occasions when several phaerimm will work together to defeat an enemy that is too strong for them to face individually.

## An Endangered Species

Phaerimms were pushed to the edge of extinction thousands of years ago by the ancient Netherese wizards. Only a few isolated pockets still exist, typically sealed away in deep chambers by their enemies. Phaerimms still have a particular hatred for tomb tappers, a Netherese construct that is immune to their mind control. Their population has been slow to recover from this purge, as a phaerimm is only capable of producing a single egg every century. This egg must be injected into a host through a stinger on the phaerimm's tail, which paralyzes the victim. The larva then consumes the host—still alive—from the inside.

## Statblock

```ad-statblock
title: Phaerimm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Phaerimm.webp#token)
*Large aberration, Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 170 (`20d10 + 60`)
- **Speed** 15 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|13 (+1)|16 (+3)|19 (+4)|20 (+5)|23 (+6)|

- **Proficiency Bonus** +5
- **Saving Throws** Intelligence +9, Charisma +11
- **Skills** Arcana +9, Insight +10
- **Senses** truesight 120 ft., passive Perception 15
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified)
- **Languages** Undercommon, understands Common, telepathy 100 ft.
- **Challenge** 15

## Traits

***Arcane Sight.*** The phaerimm discerns the location of all magical auras within sight and knows which creatures within 60 feet are spellcasters.

***Extended Concentration.*** The phaerimm can concentrate on two different spells at the same time. If [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) is broken, then both spells fade immediately.

***Immutable Form.*** The phaerimm is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The phaerimm has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** The phaerimm casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 19):

**At will**: [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

**1/day each**: [chain lightning](2-Mechanics/CLI/spells/chain-lightning.md), [confusion](2-Mechanics/CLI/spells/confusion.md), [dominate monster](2-Mechanics/CLI/spells/dominate-monster.md), [greater invisibility](2-Mechanics/CLI/spells/greater-invisibility.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md), [mass suggestion](2-Mechanics/CLI/spells/mass-suggestion.md), [prismatic spray](2-Mechanics/CLI/spells/prismatic-spray.md), [reverse gravity](2-Mechanics/CLI/spells/reverse-gravity.md)

**2/day each**: [crown of madness](2-Mechanics/CLI/spells/crown-of-madness.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [dominate person](2-Mechanics/CLI/spells/dominate-person.md), [fear](2-Mechanics/CLI/spells/fear.md), [fireball](2-Mechanics/CLI/spells/fireball.md), [phantasmal force](2-Mechanics/CLI/spells/phantasmal-force.md), [magic missile](2-Mechanics/CLI/spells/magic-missile.md), [shield](2-Mechanics/CLI/spells/shield.md)

## Actions

***Multiattack.*** The phaerimm makes four Claw attacks and then makes a Bite or Stinger attack. Alternatively, it uses Spellcasting and then makes two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+5|noform|avg|text(18)` (`2d12 + 5`) piercing damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) slashing damage.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage. If the target fails a DC 18 Constitution saving throw, they have the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) condition for 1 minute. The phaerimm's poison forces the [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) target to float 5 feet above the ground. The target may repeat the saving throw at the end of each of it's turns.

***Implant.*** The phaerimm makes a Stinger attack against a [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) target. If the stinger hits, an egg is implanted in the target. This egg can only be removed by spells that cure disease, such as lesser restoration. If the egg is not removed within 90 days, the larva emerges, and the host is killed. A phaerimm has a single egg so may only use this ability once.
```
^statblock