---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/gos
- monster/cr/2
- monster/size/medium
- monster/type/undead
aliases: ["Drowned Blade"]
---
# Drowned Blade
*Source: Ghosts of Saltmarsh p. 235, Locathah Rising*  

Assaulting the hermitage in Tammeraut's Fate, this barnacle-encrusted undead warrior fights with surprising cunning. Starfish cling to its wispy beard, and its evil rage is visible in its bloated gray eyes.

## Bluerot

This disease targets humanoids. While afflicted with bluerot, a victim grows grotesque blue boils on their face and back. This disease is carried by undead (including the drowned ones in Tammeraut's Fate), and victims most often acquire it through wounds caused by infected creatures. The disease's boils manifest in `dice:1d4|noform|avg` (`1d4`) hours, causing the victim's Constitution and Charisma scores to decrease by `dice:1d4|noform|avg` (`1d4`) each, to a minimum of 3. This is quickly followed by a fever and tingling in the extremities. An infected creature is vulnerable to radiant damage and gains the ability to breathe underwater.

At the end of each long rest, an infected creature makes a DC 12 Constitution saving throw. On a success, the victim regains 1 point of Constitution and 1 point of Charisma lost to the disease. If the infected creature regains all the points lost to the disease, it is cured. Other effects that raise the victim's ability scores do not cure the disease. On a failed saving throw, the victim takes `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage as the boils burst and spread. A creature reduced to 0 hit points by this damage cannot regain hit points until the disease is cured, though it can be stabilized as normal.

## Statblock

```ad-statblock
title: Drowned Blade
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GoS/Drowned%20Blade.webp#token)
*Medium undead, Chaotic Evil*

- **Armor Class** 10 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 45 (`6d8 + 18`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 8 (-1)|16 (+3)| 3 (-4)| 9 (-1)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages it knew in life but can't speak
- **Challenge** 2

## Traits

***Bottom Treader.*** The drowned blade cannot swim, and it sinks to the bottom of any body of water. It takes no penalties to its movement or attacks underwater. It is immune to the effects of being underwater at a depth greater than 100 feet.

***Bound Together.*** The drowned blade shares its mind with every other drowned one within 1 mile of it, and can communicate its thoughts and observations to them instantaneously and without limitation.

***Undead Fortitude.*** If damage reduces the drowned blade to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the drowned blade drops to 1 hit point instead.

## Actions

***Multiattack.*** The drowned blade makes two rusted longsword attacks.

***Rusted Longsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) slashing damage, and the target must succeed on a DC 12 Constitution saving throw or contract [bluerot](2-Mechanics/CLI/rules/diseases.md#Bluerot) (see the "Bluerot" in notes).
```
^statblock