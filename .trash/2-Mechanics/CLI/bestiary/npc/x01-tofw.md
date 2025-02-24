---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tofw
- monster/cr/13
- monster/size/huge
- monster/type/construct
aliases: ["X01"]
---
# X01
*Source: Turn of Fortune's Wheel p. 91*  

```ad-statblock
title: X01
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToFW/X01.webp#token)
*Huge construct, typically  Lawful Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 209 (`22d12 + 66`)
- **Speed** 40 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|16 (+3)|17 (+3)|19 (+4)|17 (+3)|15 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Intelligence +9, Wisdom +8
- **Skills** Perception +13
- **Senses** truesight 120 ft., passive Perception 23
- **Damage Resistances** lightning, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all, telepathy 120 ft.
- **Challenge** 13

## Traits

***Axiomatic Mind.*** X01 can't be compelled to act in a manner contrary to its nature or its instructions.

***Combat Ready.*** X01 has advantage on initiative rolls.

***Disintegration.*** If X01 dies, its body disintegrates into dust, leaving behind anything it was carrying.

***Legendary Resistance (4/Day).*** If X01 fails a saving throw, it can choose to succeed instead.

***Spellcasting.*** X01 casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [mending](2-Mechanics/CLI/spells/mending.md) (as an action)

**1/day each**: [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only), [protection from evil and good](2-Mechanics/CLI/spells/protection-from-evil-and-good.md)

## Actions

***Multiattack.*** X01 makes one Pincer attack and two Tentacle attacks.

***Pincer.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) force damage. If the target is a creature, it must succeed on a DC 17 Constitution saving throw or have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition until the end of its next turn.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) piercing damage, and if the target is a Medium or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14). Until this grapple ends, X01 can't use this tentacle against other targets. X01 has six tentacles, each of which can grapple one target.

## Reactions

X01 can take up to three reactions per round but only one per turn.

***Counter Magic.*** X01 attempts to interrupt a creature it can see that is casting a spell. If the spell is 3rd level or lower, it fails and has no effect. If the spell is 4th level or higher, X01 makes an Intelligence check (DC 10 + the spell's level). On a success, the spell fails and has no effect.

***Lightning Rebuke.*** When a creature within 120 feet of X01 damages it, X01 magically retaliates with an arc of lightning. The creature must make a DC 17 Dexterity saving throw, taking `dice:2d10|noform|avg|text(11)` (`2d10`) lightning damage on a failed save, or half as much damage on a successful one.
```
^statblock