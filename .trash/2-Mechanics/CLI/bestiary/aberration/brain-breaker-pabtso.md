---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/12
- monster/size/large
- monster/type/aberration/mind-flayer
aliases: ["Brain Breaker"]
---
# Brain Breaker
*Source: Phandelver and Below: The Shattered Obelisk p. 199*  

Brain breakers look like giant brains with stout legs, and they wear steel armor made from interlocked links of Ilvaash's runes (knots of tentacles, brains, and jagged lines reminiscent of jaws).

```ad-statblock
title: Brain Breaker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Brain%20Breaker.webp#token)
*Large aberration (mind flayer), Lawful Evil*

- **Armor Class** 14 ([ring mail](2-Mechanics/CLI/items/ring-mail.md))
- **Hit Points** 189 (`18d10 + 90`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|10 (+0)|20 (+5)|21 (+5)|19 (+4)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +9, Wisdom +8, Charisma +9
- **Skills** Arcana +9, Insight +12
- **Senses** blindsight 120 ft., passive Perception 14
- **Languages** telepathy 1 mile; understands Common, Deep Speech, and Undercommon but can't speak
- **Challenge** 12

## Traits

***Creature Sense.*** The brain breaker is aware of creatures within 1 mile of itself that have an Intelligence score of 4 or higher. It knows the distance and direction to each creature, as well as each one's Intelligence score, but can't sense anything else about it. A creature protected by a [mind blank](2-Mechanics/CLI/spells/mind-blank.md) spell, a [nondetection](2-Mechanics/CLI/spells/nondetection.md) spell, or similar magic can't be perceived in this manner.

***Magic Resistance.*** The brain breaker has advantage on saving throws against spells and other magical effects.

***Telepathic Hub.*** The brain breaker can use its telepathy to initiate and maintain telepathic conversations with up to ten creatures at a time. The brain breaker can let those creatures telepathically hear each other while connected in this way.

***Spellcasting (Psionics).*** The brain breaker casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 17):

**At will**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [levitate](2-Mechanics/CLI/spells/levitate.md)

## Actions

***Multiattack.*** The brain breaker makes two Tentacle attacks.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 30 ft., one target. *Hit:* `dice:3d8+2|noform|avg|text(15)` (`3d8 + 2`) bludgeoning damage. If the target is a Huge or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14) and takes `dice:1d8+5|noform|avg|text(9)` (`1d8 + 5`) psychic damage at the start of each of its turns until the grapple ends. The brain breaker can have up to four targets [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) at a time.

***Mind Blast (Recharge 5-6).*** Creatures of the brain breaker's choice within 60 feet of itself must succeed on a DC 17 Intelligence saving throw or take `dice:5d10+5|noform|avg|text(32)` (`5d10 + 5`) psychic damage and have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Bonus Actions

***Psychic Link.*** The brain breaker targets one creature with the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition that the brain breaker senses with its Creature Sense trait and establishes a psychic link with the target. Until the link ends, the brain breaker can perceive everything the target senses. The target becomes aware that something is linked to its mind once it no longer has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition, and the brain breaker can terminate the link at any time (no action required). The target can use an action on its turn to attempt to break the link, doing so with a successful DC 17 Charisma check. If the target breaks the link this way, the target takes `dice:3d6|noform|avg|text(10)` (`3d6`) psychic damage. The link also ends if the target and the brain breaker are more than 1 mile apart. The brain breaker can form psychic links with up to ten creatures at a time.
```
^statblock