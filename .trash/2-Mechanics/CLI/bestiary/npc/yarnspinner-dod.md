---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dod
- monster/cr/10
- monster/size/huge
- monster/type/fey/archfey
aliases: ["Yarnspinner"]
---
# Yarnspinner
*Source: Domains of Delight p. 22*  

## Yarnspinner

Yarnspinner has a monstrous form resembling that of an enormous spider. However, he has a benevolent personality and is obsessed with stories. In fact, he has amassed quite a collection of storybooks, which he keeps in silk sacks for easy transport. When Yarnspinner dreams, he projects a harmless, ghost-like version of himself that wanders his domain. In this form, he can talk to strangers and steer them one direction or another without fear of being harmed. If a visitor needs a safe haven, Yarnspinner is more than happy to fashion a hut made of spider silk for his guest to inhabit. The visitor is free to remain there as long as they wish, provided they do no harm to the other denizens of Fablerise.

Yarnspinner's favorite activity is to read stories aloud to the animals that occupy his domain, all of which benefit from having had [awaken](2-Mechanics/CLI/spells/awaken.md) spells cast on them. The archfey's stories attract quite a gathering and are the talk of Fablerise's awakened animal kingdom.

## Fablerise

Fablerise is a vast thicket of thick roots, thorny vines, and sinuous creepers that weave together to form long tunnels, grand hallways, and enormous domes. It's a gloomy realm. A mushroom circle in the heart of the domain serves as a fey crossing, and one can travel more quickly through the thicket by whistling a tune while walking backward.

## Statblock

```ad-statblock
title: Yarnspinner
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoD/Yarnspinner.webp#token)
*Huge fey (archfey), Lawful Good*

- **Armor Class** 16 (natural armor)
- **Hit Points** 138 (`12d12 + 60`)
- **Speed** 40 ft., climb 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|16 (+3)|21 (+5)|18 (+4)|21 (+5)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +9, Wisdom +9, Charisma +8
- **Skills** Perception +13, Stealth +7
- **Senses** truesight 120 ft., passive Perception 23
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Common, Druidic, Sylvan
- **Challenge** 10

## Traits

***Fey Rebirth.*** If Yarnspinner dies in his Domain of Delight, he revives with all his hit points `dice:1d4|noform|avg` (`1d4`) days later in a safe location in that domain.

***Legendary Resistance (3/Day).*** If Yarnspinner fails a saving throw, he can choose to succeed instead.

***Spider Climb.*** Yarnspinner can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Web Walker.*** Yarnspinner ignores movement restrictions caused by webbing.

***Web Weaver (3/Day).*** Yarnspinner can take 1 minute to craft one of the following structures out of webbing:

- A 3-inch-thick, opaque wall of webbing consisting of up to three 10-foot-square sections, each of which must be anchored on at least two sides by other walls or surfaces. Each section has AC 12; 20 hit points; vulnerability to fire damage; and immunity to bludgeoning, poison, and psychic damage.  
- A hut small enough to fit in a 10-foot cube. The hut comes with a closable door and a comfortable bed made of webbing, sized for a Tiny, Small, or Medium creature.  
- A message consisting of no more than twenty-five characters, anchored at various points so it hangs in the air.  

***Spellcasting.*** Yarnspinner casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 17):

**At will**: [faerie fire](2-Mechanics/CLI/spells/faerie-fire.md), [speak with animals](2-Mechanics/CLI/spells/speak-with-animals.md)

**1/day each**: [awaken](2-Mechanics/CLI/spells/awaken.md) (as an action), [pass without trace](2-Mechanics/CLI/spells/pass-without-trace.md)

**2/day each**: [animal friendship](2-Mechanics/CLI/spells/animal-friendship.md), [create food and water](2-Mechanics/CLI/spells/create-food-and-water.md), [revivify](2-Mechanics/CLI/spells/revivify.md)

## Actions

***Multiattack.*** Yarnspinner makes two Bite attacks and uses Spellcasting or Web once.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, reach 10 ft., one target. *Hit:* `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) poison damage.

***Web.*** Yarnspinner shoots webbing at one creature he can see within 120 feet of himself. The target must succeed on a DC 17 Strength saving throw or be [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) for 1 hour. The target can repeat the save at the end of each of its turns, ending the effect on itself on a success.
```
^statblock