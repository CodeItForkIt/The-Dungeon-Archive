---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/strig
aliases: ["Strig Knight"]
---
# Strig Knight
*Source: Humblewood Campaign Setting p. 204*  

The Perch Guard produces many skilled soldiers, but only those who possess a great degree of talent are trained to become knights. The knights of Alderheart's Perch Guard are taught how to protect others by creating opportunities for allies to regroup or retreat as necessary. Experts in sword-and-shield fighting, the knight's heavily-armoured fighting style allows them to hold the line against even the fiercest of enemies. The strig knight listed is equipped with a [wing crest shield](2-Mechanics/CLI/items/wing-crest-shield-hwcs.md) (see "Appendix D: New Magic Items").

```ad-statblock
title: Strig Knight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Strig%20Knight.webp#token)
*Medium humanoid (strig), Any Non-Chaotic alignment*

- **Armor Class** 18 ([half plate armor](2-Mechanics/CLI/items/half-plate-armor.md), [shield](2-Mechanics/CLI/items/shield.md))
- **Hit Points** 60 (`8d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|16 (+3)| 8 (-1)|13 (+1)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +5, Wisdom +4
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 11
- **Languages** Birdfolk, can also understand Auran but can't speak it
- **Challenge** 3

## Traits

***Glide.*** When falling at least 10 feet, the knight can spend a reaction to fly up to their speed in one direction as they descend. They land in an unoccupied space at the end of their movement, and take no falling damage. They cannot glide while carrying heavy objects, heavy weapons, or shields (though they can drop any held items as part of their reaction).

***Talons.*** The knight rolls advantage on Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) checks made to climb any surface their talons could reasonably grip.

***Maneuver (2/Day).*** When the knight hits with an attack, they can choose to maneuver the enemy out of position, granting an ally within 5 feet of the target the opportunity to use their reaction to move away from this enemy at half their movement speed without provoking an [attack of opportunity](2-Mechanics/CLI/rules/actions.md#Opportunity%20Attack).

## Actions

***Multiattack.*** The knight makes two short sword attacks.

***Short Sword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage.

***Talons.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage. The knight can choose to grapple a target hit by this attack as a bonus action.

***Wing Crest Shield (1/Day).*** The knight casts the [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md) spell (save DC 15).
```
^statblock