---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/4
- monster/size/huge
- monster/type/monstrosity
aliases: ["Ashsnake"]
---
# Ashsnake
*Source: Humblewood Campaign Setting p. 177*  

> [!quote] A quote from From The Epic of Fire, a centuries old poem  
> 
> "Beneath the ash it lies in wait. A hiss, a snap, and it's too late."

Ashsnakes are huge monstrosities which resemble snakes molded from volcanic magma. Their bodies seeth with an internal heat below the charcoal-gray scales that cover their forms. While the blazing light emanating from their empty eye sockets makes it appear as though ashsnakes can see, they rely entirely on vibrations to assess their surroundings.

## Mysterious Origins

Little is known about the origins of the ashsnake. They recently emerged from beneath the ashen plains of the Scorched Grove and appear to have an insatiable hunger. Ashnakes use the mounds of ash and dust in the Grove to conceal their presence, allowing them to close in on unwary prey and ambush them. While not particularly intelligent, ashsnakes possess predatorial cunning and survival instincts eerily reminiscent of the fauna that inhabited the Grove before its burning.

## Sightless Worms

Ashsnakes have no ability to detect sights and sounds in a traditional sense. They are, however, adept at sensing even the smallest vibration, and the slightest footfall is enough to draw their attention. Some scholars believe it may be possible to "disappear" from an ashsnakes "vision" by standing perfectly still, but finding volunteers to confirm this theory has under-standably proven difficult.

## Statblock

```ad-statblock
title: Ashsnake
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Ashsnake.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 14 (natural armor; 18 while under ash)
- **Hit Points** 67 (`7d12 + 21`)
- **Speed** 40 ft., burrow 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|16 (+3)| 4 (-3)|12 (+1)| 4 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 30 ft. (blind beyond this radius), tremorsense 60 ft., passive Perception 11
- **Damage Vulnerabilities** cold
- **Damage Resistances** fire
- **Languages** understands Ignan, but can't speak
- **Challenge** 4

## Traits

***Ash Cover.*** The ashsnake has advantage on Dexterity ([Stealth](2-Mechanics/CLI/rules/skills.md#Stealth)) checks made when it is burrowing in ash, as well as a +4 bonus to its armor class.

***Eruption.*** When the ashsnake emerges from burrowing, any creature within 5 feet of it that is at least one size smaller than the ashsnake must make a DC 14 Dexterity saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

## Actions

***Multiattack.*** The Ashsnake can make one bite attack and either one Constrict or Crush attack each round.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+3|noform|avg|text(8)` (`1d10 + 3`) piercing damage.

***Constrict.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+3|noform|avg|text(8)` (`2d8 + 3`) bludgeoning damage and the target is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 14). Until the grapple ends the target is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) and the ashsnake cannot constrict or crush another target. The ashsnake can release the target at any time during its turn.

***Crush.*** The ashsnake crushes its [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) target, dealing `dice:2d8+3|noform|avg|text(11)` (`2d8 + 3`) bludgeoning damage.

***Ashen Breath (Recharge 5-6).*** The ashsnake breathes out a cloud of superheated ash in a 15-foot cone. Each creature in the area must make a DC 14 Dexterity saving throw, taking `dice:2d10|noform|avg|text(11)` (`2d10`) fire damage on a failed save, or half as much on a success.
```
^statblock