---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/7
- monster/size/huge
- monster/type/aberration
aliases: ["Flesh Meld"]
---
# Flesh Meld
*Source: Phandelver and Below: The Shattered Obelisk p. 207*  

Squelching and quivering with insatiable hunger, a flesh meld is a hulking amalgamation of teeth, blood, and body parts. Sinuous appendages of gore, each ending in a gnashing mouth, bite at prey before yanking the piteous creatures into the flesh meld's core. The stench of death surrounds a flesh meld.

When a creature is consumed by a flesh meld, the creature's mind is merged into the flesh meld's consciousness. More resilient minds may fight against this assimilation, but inevitably, the mind succumbs to the discordant chorus of thoughts to kill and consume.

```ad-statblock
title: Flesh Meld
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Flesh%20Meld.webp#token)
*Huge aberration, typically  Chaotic Evil*

- **Armor Class** 12
- **Hit Points** 95 (`10d12 + 30`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|21 (+5)|14 (+2)|17 (+3)| 7 (-2)|13 (+1)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +8, Dexterity +5
- **Skills** ⏤
- **Senses** blindsight 60 ft. (can't see beyond this radius), passive Perception 11
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** understands all but can't speak
- **Challenge** 7

## Traits

***Amorphous.*** The flesh meld can move through a space as narrow as 1 inch without squeezing.

***Aura of Death.*** At the start of each of the flesh meld's turns, each creature within 5 feet of it must succeed on a DC 15 Constitution saving throw or take `dice:1d6|noform|avg|text(3)` (`1d6`) necrotic damage and have the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition until the start of the flesh meld's next turn.

***Magic Resistance.*** The flesh meld has advantage on saving throws against spells and other magical effects.

***Spider Climb.*** The flesh meld can climb difficult surfaces, including ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** The flesh meld makes two Bite attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 30 ft., one target. *Hit:* `dice:2d10+5|noform|avg|text(16)` (`2d10 + 5`) piercing damage, and if the target is a Large or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 15) and is pulled up to 15 feet toward the flesh meld.

## Bonus Actions

***Consume Creature.*** The flesh meld targets one Large or smaller creature within 5 feet of itself that it's grappling. The target must succeed on a DC 15 Dexterity saving throw or be swallowed by the flesh meld. The flesh meld can have one creature swallowed at a time.

A swallowed creature no longer has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition. While swallowed, it has the [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) conditions, has total cover against attacks and other effects outside the flesh meld, and takes `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage at the start of each of the flesh meld's turns. If this damage reduces a swallowed creature to 0 hit points, the creature dies, and the flesh meld consumes its body.

If the flesh meld takes 30 damage or more on a single turn from the swallowed creature, the flesh meld must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate the creature, which falls with the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition in a space within 5 feet of the flesh meld. If the flesh meld dies, the swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 10 feet of movement, exiting with the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.
```
^statblock