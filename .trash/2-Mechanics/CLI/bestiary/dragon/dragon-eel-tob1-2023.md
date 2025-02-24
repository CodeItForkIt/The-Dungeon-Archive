---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/12
- monster/environment/coastal
- monster/environment/underwater
- monster/size/huge
- monster/type/dragon
aliases: ["Dragon Eel"]
---
# Dragon Eel
*Source: Tome of Beasts 1 (2023 Edition) p. 111*  

*This slender aquatic creature sports a powerful single finned tail and wicked jaws like a matched pair of serrated blades.*

Dragon eels are wingless, slender, underwater dragons that vary widely in color from browns and blacks to brilliant iridescent hues in mottled patterns. Though not true dragons or drakes, they are no less fearsome and powerful.

## Fond of Servants

While most dragon eels are solitary and irascible, on rare instances some form pairs or small bands—and some gather humanoid servants.

## Magnetic and Lightning

Dragon eels make their natural homes in twisting underwater cave systems and prefer magnetically-aligned, metallic cavern formations navigable with their refined electric sight. Some dragon eels use their constant electric auras combined with acquired alchemical reagents to electroplate portions of their golden hoard onto the walls of their dwellings.

## Pirate Fleets and Dominions

Dragon eels claim large swaths of shoreline as their demesne. Although neither particularly cruel nor righteous, a dragon eel often lords over awed tribes, allowing locals to revere it as a mighty spirit. Some dragon eels use such tribes as the core of a pirate fleet or raiding parties carried on their backs. Their ability to swim through air during storms adds to their reputation as terrible thunder spirits.

## Bribable

Their deceptive moniker sometimes lulls foolish sailors into a false confidence when they expect to face a simple if dangerous eel beast, but instead find themselves dealing with intelligent draconic kings of the coastal shallows. Wise sailors traveling through known dragon eel territory bring tithes and offerings to placate them.

## Statblock

```ad-statblock
title: Dragon Eel
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dragon%20Eel.webp#token)
*Huge dragon, Neutral*

- **Armor Class** 18 (natural armor)
- **Hit Points** 195 (`17d12 + 85`)
- **Speed** 20 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|12 (+1)|20 (+5)|14 (+2)|13 (+1)|14 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +12, Dexterity +5, Intelligence +6, Wisdom +5, Charisma +6
- **Skills** Acrobatics +5, Athletics +12, Insight +5, Perception +5
- **Senses** darkvision 60 ft., passive Perception 15
- **Damage Immunities** lightning
- **Condition Immunities** [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [prone](2-Mechanics/CLI/rules/conditions.md#Prone)
- **Languages** Common, Draconic, Primordial
- **Challenge** 12

## Traits

***Limited Amphibiousness.*** The dragon eel can breathe air and water, but it needs to be submerged at least once every 6 hours to avoid suffocating.

***Shocking Hide.*** A creature that touches the dragon eel or hits it with a melee attack while within 5 feet of it takes `dice:1d10|noform|avg|text(5)` (`1d10`) lightning damage.

***Storm Glide.*** During storms with ample rain or lightning, the dragon eel gains a flying speed equal to its swimming speed.

## Actions

***Multiattack.*** The dragon eel makes one Bite attack and one Tail Slap attack.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:4d8+8|noform|avg|text(26)` (`4d8 + 8`) piercing damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) lightning damage, and the target must succeed on a DC 18 Constitution saving throw or become [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Tail Slap.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:5d8+8|noform|avg|text(30)` (`5d8 + 8`) bludgeoning damage plus `dice:1d10|noform|avg|text(5)` (`1d10`) lightning damage, and the target must succeed on a DC 18 Strength saving throw or be pushed up to 10 feet away from the eel. The dragon eel can choose to not push a target.

***Lightning Breath (Recharge 6).*** The dragon eel exhales lightning in a 60-foot line that is 5 feet wide. Each target in that line must make a DC 18 Dexterity saving throw, taking `dice:10d10|noform|avg|text(55)` (`10d10`) lightning damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

coastal, underwater