---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wbtw
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/orc
aliases: ["Zarak"]
---
# Zarak
*Source: The Wild Beyond the Witchlight p. 222*  

Zarak is an assassin without honor or conscience. Unusually short of stature for someone of orcish heritage, he might pass for an ugly, beardless dwarf were it not for his rotting tusks and grayish pallor. The only thing he loves is money, and he wouldn't hesitate to stab allies in the back if they came between him and the riches he covets.

```ad-statblock
title: Zarak
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WBtW/Zarak.webp#token)
*Medium humanoid (orc), Chaotic Evil*

- **Armor Class** 14 ([leather armor](2-Mechanics/CLI/items/leather-armor.md))
- **Hit Points** 37 (`5d8 + 15`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)|16 (+3)|16 (+3)|11 (+0)|15 (+2)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +5, Intelligence +2
- **Skills** Acrobatics +7, Insight +6, Perception +6, Stealth +7
- **Senses** darkvision 60, passive Perception 16
- **Languages** Common, Orc
- **Challenge** 2

## Traits

***Special Equipment.*** Zarak carries a [potion of invisibility](2-Mechanics/CLI/items/potion-of-invisibility.md).

## Actions

***Multiattack.*** Zarak makes two Dagger attacks.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage, plus an extra `dice:2d4|noform|avg|text(5)` (`2d4`) piercing damage if the target is a creature and Zarak has at least 18 hit points.

***Garrote.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one Humanoid. *Hit:* `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) slashing damage, and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 11). Until this grapple ends, the target takes `dice:2d4+3|noform|avg|text(8)` (`2d4 + 3`) slashing damage at the start of each of its turns, and Zarak can't grapple another creature or use Assassin's Whim.

## Bonus Actions

***Assassin's Whim.*** Zarak takes the Dash, Disengage, or Hide action.

## Reactions

***Uncanny Dodge.*** Zarak halves the damage he takes from an attack made against him, provided he can see the attacker.
```
^statblock