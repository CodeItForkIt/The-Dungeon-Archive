---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/8
- monster/size/huge
- monster/type/monstrosity
aliases: ["Hydra"]
---
# Hydra
*Source: Plane Shift: Kaladesh p. 30*  

Hydras are giant lizards resembling iguanas, with multiple heads set atop long, snakelike necks. Aether traces whorling patterns through their scales, shapes the crests running down their necks and tails, and glows blue within the skin under their chins. Most hydras have five or six heads, but small hydras with as few as three heads—as well as enormous specimens with eight or more—have been seen in the deep forests far from Ghirapur.

Hydras are fierce predators, favoring prey that has absorbed large quantities of aether from the environment. This taste for aether also leads them to devour aether-powered machines whenever they encounter such devices, from thopters to automatons. In the remote wilderness near Peema where hydras are plentiful, such altercations are rarely an issue. But in the rare event of a hydra coming too close to civilization—or even wandering into one of Ghirapur's greenbelts—they can cause widespread destruction in their hunt for aether.

Use the [hydra](2-Mechanics/CLI/bestiary/monstrosity/hydra.md) statistics in the "Monster Manual".

```ad-statblock
title: Hydra
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Hydra.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 172 (`15d12 + 75`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|12 (+1)|20 (+5)| 2 (-4)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** Perception +6
- **Senses** darkvision 60 ft., passive Perception 16
- **Languages** —
- **Challenge** 8

## Traits

***Hold Breath.*** The hydra can hold its breath for 1 hour.

***Multiple Heads.*** The hydra has five heads. While it has more than one head, the hydra has advantage on saving throws against being [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), and knocked [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious).

Whenever the hydra takes 25 or more damage in a single turn, one of its heads dies. If all its heads die, the hydra dies.

At the end of its turn, it grows two heads for each of its heads that died since its last turn, unless it has taken fire damage since its last turn. The hydra regains 10 hit points for each head regrown in this way.

***Reactive Heads.*** For each head the hydra has beyond one, it gets an extra reaction that can be used only for opportunity attacks.

***Wakeful.*** While the hydra sleeps, at least one of its heads is awake.

## Actions

***Multiattack.*** The hydra makes as many bite attacks as it has heads.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) piercing damage.
```
^statblock