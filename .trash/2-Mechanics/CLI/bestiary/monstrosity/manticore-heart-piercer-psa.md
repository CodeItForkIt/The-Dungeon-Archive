---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/5
- monster/size/large
- monster/type/monstrosity
aliases: ["Manticore, Heart-Piercer"]
---
# Manticore, Heart-Piercer
*Source: Plane Shift: Amonkhet p. 36*  

Manticores are catlike creatures with feline bodies, tails like those of [scorpions](2-Mechanics/CLI/bestiary/beast/scorpion.md), and chitinous plates on their lower legs and feet. The venom of their tail stingers is the most virulent poison known on Amonkhet, and they can sting with lightning speed even while tearing at a foe with claws and teeth. Their deadliness makes them prized for use in the Trial of Zeal, where they grant glorified deaths to many initiates.

## The Desert Lands

The desolate wilderness beyond the protection of the Hekma is largely uncharted. Immediately beyond the protective veil is a chaotic dune sea called Shefet, the Scouring Sands. The desert wears away at the edges of the fertile lands surrounding Naktamun, serving as a constant reminder that only the bounty and protection of the God-Pharaoh stand between the people of the city-state and a grisly death in the sands beyond. Beyond Shefet are parched, cracked expanses called Ramunap, the Broken Lands. The ruins of ancient civilizations are said to lie in the Broken Lands, though no one has ever explored such ruins and returned to Naktamun to tell of them.

## Statblock

```ad-statblock
title: Manticore, Heart-Piercer
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Manticore%2C%20Heart-Piercer.webp#token)
*Large monstrosity, Chaotic Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 136 (`16d10 + 48`)
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|14 (+2)|16 (+3)| 5 (-3)|12 (+1)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** —
- **Challenge** 5

## Actions

***Multiattack.*** The manticore makes two attacks, one with its bite and one with its claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) slashing damage.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) piercing damage. The target must make a DC 14 Constitution saving throw, taking `dice:7d6|noform|avg|text(24)` (`7d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock