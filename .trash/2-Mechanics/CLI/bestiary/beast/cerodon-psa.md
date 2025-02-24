---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/6
- monster/size/huge
- monster/type/beast
aliases: ["Cerodon"]
---
# Cerodon
*Source: Plane Shift: Amonkhet p. 37*  

Cerodons are sometimes mistaken for herbivores because of their resemblance to bulls, but they are never mistaken for harmless. They stand over thirty feet tall at the shoulder, and their heads are crowned with enormous horns that jut forward from the nose, then extend backward almost the entire length of their bodies. The horn structure resembles a sandstone cliff, and a cerodon can use it to ruin buildings or monuments with a minimum of effort. Cerodons are extremely aggressive, and often mistake the shimmering Hekma for an intruder into their territory. Use the statistics of a [mammoth](2-Mechanics/CLI/bestiary/beast/mammoth.md) for these creatures, with the following additional trait:

## Siege Monster

The cerodon deals double damage to objects and structures.

## The Desert Lands

The desolate wilderness beyond the protection of the Hekma is largely uncharted. Immediately beyond the protective veil is a chaotic dune sea called Shefet, the Scouring Sands. The desert wears away at the edges of the fertile lands surrounding Naktamun, serving as a constant reminder that only the bounty and protection of the God-Pharaoh stand between the people of the city-state and a grisly death in the sands beyond. Beyond Shefet are parched, cracked expanses called Ramunap, the Broken Lands. The ruins of ancient civilizations are said to lie in the Broken Lands, though no one has ever explored such ruins and returned to Naktamun to tell of them.

## Statblock

```ad-statblock
title: Cerodon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Cerodon.webp#token)
*Huge beast, Unaligned*

- **Armor Class** 13 (natural armor)
- **Hit Points** 126 (`11d12 + 55`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)| 9 (-1)|21 (+5)| 3 (-4)|11 (+0)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 10
- **Languages** —
- **Challenge** 6

## Traits

***Trampling Charge.*** If the cerodon moves at least 20 feet straight toward a creature and then hits it with a gore attack on the same turn, that target must succeed on a DC 18 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). If the target is [prone](2-Mechanics/CLI/rules/conditions.md#Prone), the cerodon can make one stomp attack against it as a bonus action.

***Siege Monster.*** The cerodon deals double damage to objects and structures.

## Actions

***Gore.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+7|noform|avg|text(25)` (`4d8 + 7`) piercing damage.

***Stomp.*** *Melee Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft., one [prone](2-Mechanics/CLI/rules/conditions.md#Prone) creature. *Hit:* `dice:4d10+7|noform|avg|text(29)` (`4d10 + 7`) bludgeoning damage.
```
^statblock