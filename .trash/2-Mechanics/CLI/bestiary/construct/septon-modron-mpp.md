---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/12
- monster/size/large
- monster/type/construct
aliases: ["Septon Modron"]
---
# Septon Modron
*Source: Morte's Planar Parade p. 40, Sigil and the Outlands, Turn of Fortune's Wheel*  

Septons are auditors of base modrons in Mechanus, recording the activities in each of the plane's sectors to ensure operations are in perfect order. They are easily identified by their seven flexible limbs.

## Modrons

Constructed on the plane of Mechanus, modrons are partially mechanical beings that belong to a strict hierarchy. Each modron dutifully obeys commands from the rank directly above it and in turn acts as the superior to the rank directly below it, passing down commands from paragons of law to the lowliest monodrone. While most modrons are the lower-ranked base modrons—monodrones, duodrones, tridrones, quadrones, and pentadrones—the upper-tier hierarch modrons hold leadership positions, maintaining order in Mechanus and the realms beyond. For more information on modrons, see the*Monster Manual*.

## Statblock

```ad-statblock
title: Septon Modron
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Septon%20Modron.webp#token)
*Large construct, typically  Lawful Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 204 (`24d10 + 72`)
- **Speed** 30 ft., fly 30 ft. (hover), swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|15 (+2)|17 (+3)|18 (+4)|16 (+3)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +8, Wisdom +7
- **Skills** Perception +11
- **Senses** truesight 120 ft., passive Perception 21
- **Damage Resistances** lightning, psychic
- **Languages** all, telepathy 120 ft.
- **Challenge** 12

## Traits

***Axiomatic Mind.*** The septon can't be compelled to act in a manner contrary to its nature or its instructions.

***Combat Ready.*** The septon has advantage on initiative checks.

***Disintegration.*** If the septon dies, its body disintegrates into dust, leaving behind anything it was carrying.

***Spellcasting.*** The septon casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 16):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [mending](2-Mechanics/CLI/spells/mending.md) (as an action)

**1/day each**: [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only), [protection from evil and good](2-Mechanics/CLI/spells/protection-from-evil-and-good.md), [sending](2-Mechanics/CLI/spells/sending.md)

## Actions

***Multiattack.*** The septon makes four Tentacle attacks and uses Lightning Network or Spellcasting.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) piercing damage, and if the target is a Medium or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14). Until this grapple ends, the septon can't use this tentacle against other targets. The septon has seven tentacles, each of which can grapple one target.

***Lightning Network.*** The septon conjures a field of electricity that fills a 30-foot cube originating from itself before dissipating. Each creature in that area must make a DC 16 Dexterity saving throw. On a failed save, a creature takes `dice:6d10|noform|avg|text(33)` (`6d10`) lightning damage and has the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. On a successful save, a creature takes half as much damage only. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock