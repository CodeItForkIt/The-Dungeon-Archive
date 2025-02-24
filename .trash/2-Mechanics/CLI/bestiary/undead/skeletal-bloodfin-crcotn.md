---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/crcotn
- monster/cr/9
- monster/size/large
- monster/type/undead
aliases: ["Skeletal Bloodfin"]
---
# Skeletal Bloodfin
*Source: Critical Role: Call of the Netherdeep p. 159*  

Covered in vicious-looking crimson spines and sleek scales, the slithering bloodfin flashes through the lightless waters of the Netherdeep. As it swims closer, its toothed maw comes into view—just before it unhinges its jaw, clamps down on its prey, and swallows it whole.

A slithering bloodfin looks like a giant eel with a head like a shark's. It magically siphons life energy from swallowed prey and uses that energy to repair damage to its own body.

When a bloodfin dies, its body bursts. The resulting gore is toxic, threatening to infect nearby creatures, until it is dissipated by currents.

```ad-statblock
title: Skeletal Bloodfin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CRCotN/Skeletal%20Bloodfin.webp#token)
*Large undead, Unaligned*

- **Armor Class** 16 (natural armor)
- **Hit Points** 93 (`11d10 + 33`)
- **Speed** 5 ft., swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|16 (+3)| 2 (-4)|10 (+0)| 3 (-4)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** Perception +4
- **Senses** blindsight 100 ft. (blind beyond this radius), passive Perception 14
- **Damage Resistances** piercing, slashing
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** —
- **Challenge** 9

## Traits

***Death Burst.*** When the bloodfin dies, it explodes in a cloud of toxic blood. Each creature in a 10-foot-radius sphere centered on the exploding bloodfin, including any creature swallowed by the bloodfin, must succeed on a DC 15 Constitution saving throw or take `dice:3d6|noform|avg|text(10)` (`3d6`) poison damage. A creature inside the bloodfin when it explodes falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in the space formerly occupied by the bloodfin and is no longer [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it.

***Unusual Nature.*** The skeletal bloodfin requires no food, drink, air, or sleep.

## Actions

***Multiattack.*** The bloodfin makes one Bite attack and one Tail attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit (with advantage if the target is a creature missing any hit points), reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage, and if the target is a creature, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 15). Until this grapple ends, the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), and the bloodfin can't bite another target.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit (with advantage if the target is a creature missing any hit points), reach 10 ft., one target. *Hit:* `dice:4d6+5|noform|avg|text(19)` (`4d6 + 5`) bludgeoning damage.

## Bonus Actions

***Swallow.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one Medium or smaller creature the bloodfin is grappling. *Hit:* The bloodfin swallows the target. The swallowed creature is no longer [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) but is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). It has total cover against attacks and other effects outside the bloodfin, it takes `dice:4d6|noform|avg|text(14)` (`4d6`) necrotic damage at the start of each of its turns, and the bloodfin regains hit points equal to the necrotic damage dealt. A bloodfin can have only one creature swallowed at a time.

If the bloodfin takes 30 damage or more on a single turn from the swallowed creature, the bloodfin must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate the creature, which falls [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 5 feet of the bloodfin and is no longer [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it.
```
^statblock