---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/15
- monster/size/gargantuan
- monster/type/monstrosity
aliases: ["Sandwurm"]
---
# Sandwurm
*Source: Plane Shift: Amonkhet p. 35*  

Sandwurms are the largest predators of Shefet, swimming through the sandy dunes like [serpents](2-Mechanics/CLI/bestiary/beast/river-serpent-psa.md) through water. They are capable of amazing speed and can lift their lamprey-like heads far above the ground to snatch even flying creatures. But they can also lie in wait beneath the sands for years, until the slightest tremor alerts them to the presence of prey.

## The Desert Lands

The desolate wilderness beyond the protection of the Hekma is largely uncharted. Immediately beyond the protective veil is a chaotic dune sea called Shefet, the Scouring Sands. The desert wears away at the edges of the fertile lands surrounding Naktamun, serving as a constant reminder that only the bounty and protection of the God-Pharaoh stand between the people of the city-state and a grisly death in the sands beyond. Beyond Shefet are parched, cracked expanses called Ramunap, the Broken Lands. The ruins of ancient civilizations are said to lie in the Broken Lands, though no one has ever explored such ruins and returned to Naktamun to tell of them.

## Statblock

```ad-statblock
title: Sandwurm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Sandwurm.webp#token)
*Gargantuan monstrosity, Unaligned*

- **Armor Class** 18 (natural armor)
- **Hit Points** 247 (`15d20 + 90`)
- **Speed** 50 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)| 7 (-2)|22 (+6)| 1 (-5)| 8 (-1)| 4 (-3)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +11, Wisdom +4
- **Skills** ⏤
- **Senses** blindsight 30 ft., tremorsense 60 ft., passive Perception 9
- **Languages** —
- **Challenge** 15

## Traits

***Tunneler.*** The wurm can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.

## Actions

***Multiattack.*** The wurm makes two attacks: one with its bite and one with its stinger.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one target. *Hit:* `dice:3d8+9|noform|avg|text(22)` (`3d8 + 9`) piercing damage. If the target is a Large or smaller creature, it must succeed on a DC 19 Dexterity saving throw or be swallowed by the wurm. A swallowed creature is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained), it has total cover against attacks and other effects outside the wurm, and it takes `dice:6d6|noform|avg|text(21)` (`6d6`) acid damage at the start of each of the wurm's turns.

If the wurm takes 30 damage or more on a single turn from a creature inside it, the wurm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](2-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet of the wurm. If the wurm dies, a swallowed creature is no longer [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) by it and can escape from the corpse by using 20 feet of movement, exiting [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Tail Stinger.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 10 ft., one creature. *Hit:* `dice:3d6+9|noform|avg|text(19)` (`3d6 + 9`) piercing damage, and the target must make a DC 19 Constitution saving throw, taking `dice:12d6|noform|avg|text(42)` (`12d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock