---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/6
- monster/environment/farmland
- monster/environment/forest
- monster/size/medium
- monster/type/fey
aliases: ["Redcap"]
---
# Redcap
*Source: Tome of Beasts 1 (2023 Edition) p. 306*  

*This grizzled, weather-beaten creature looks like a sour old man, complete with scraggly beard. It carries a great pike and wears a blood-soaked hat and heavy boots shod with iron. It grins with massive yellow teeth*.

## Blood-Soaked Caps

Redcaps are exceedingly dangerous creatures who wear the mark of their cruelty and evil quite literally. The caps from which they take their name define their very existence—these caps must constantly be revived with fresh blood.

## Compelled to Kill

Redcaps aren't cruel and murderous by choice, but by necessity. A redcap must frequently bathe its cap in fresh, humanoid blood to sustain itself. If it fails to do so every three days, the creature withers and dies quickly. A redcap whose hat is nearly dry is a desperate, violent force of nature that prefers to die in battle rather than waste away to nothing.

## Bandits and Mercenaries

Most long-lived redcaps are drawn to serve in marauding armies or make a living through constant banditry.

## Statblock

```ad-statblock
title: Redcap
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Redcap.webp#token)
*Medium fey, Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 120 (`16d8 + 48`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|10 (+0)|17 (+3)|11 (+0)|13 (+1)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +6
- **Skills** Athletics +8, Intimidation +5
- **Senses** darkvision 60 ft., passive Perception 11
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Sylvan, Undercommon
- **Challenge** 6

## Traits

***Red Cap.*** The redcap must soak its cap in the blood of a Humanoid that has been dead for no more than 1 hour at least once every 3 days. Every 24 hours past the third day that it goes without soaking its cap in blood in this way, it suffers one level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). This [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) can be reduced only when the redcap finishes a long rest after soaking its cap in fresh Humanoid blood, which reduces its [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion) level to 0. If the redcap dies as a result of this [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), it crumbles to dust.

## Actions

***Multiattack.*** The redcap makes one Bleeding Bite attack and two Pike attacks.

***Bleeding Bite.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+5|noform|avg|text(14)` (`2d8 + 5`) piercing damage. If the target is a creature other than a Construct or Undead, it must succeed on a DC 15 Constitution saving throw or lose 7 `dice:2d6|noform|avg` (`2d6`) hp at the start of each of its turns due to a bleeding wound. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Any creature can take an action to stanch the wound with a successful DC 13 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check. The wound also closes if the target receives magical healing.

***Pike.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) piercing damage.

## Bonus Actions

***Solid Kick.*** The redcap kicks a Medium or smaller creature within 5 feet of it. The target must succeed on a DC 15 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock

## Environment

farmland, forest