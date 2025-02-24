---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hwcs
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/strig
aliases: ["Riffin, the Ash-Knight"]
---
# Riffin, the Ash-Knight
*Source: Humblewood Campaign Setting p. 204*  

Riffin is a small stout strig, standing a few inches over three feet, whose plumage and proportions resemble a little owl. A traveling knight of the realm, Riffin lived in Ashbarrow before its destruction, and was carried to Alderheart by his friend Odwald, who saved him from the fire. Being one of the only knights to hail from Ashbarrow, folk began calling him the "Ash-Knight," a title which he now uses to keep the memory of his home alive. Riffin is a simple strig with a charming way of viewing the world. He is also a steadfast warrior who strongly believes in doing what is right, helping those in need, and honoring his debts. Riffin uses the [strig knight](2-Mechanics/CLI/bestiary/humanoid/strig-knight-hwcs.md) stat block. His alignment is lawful good.

```ad-statblock
title: Riffin, the Ash-Knight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HWCS/Riffin%2C%20the%20Ash-Knight.webp#token)
*Medium humanoid (strig), Lawful Good*

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

***Glide.*** When falling at least 10 feet, Riffin can spend a reaction to fly up to his speed in one direction as he descends. He lands in an unoccupied space at the end of his movement, and takes no falling damage. He cannot glide while carrying heavy objects, heavy weapons, or shields (though he can drop any held items as part of his reaction).

***Talons.*** Riffin rolls advantage on Strength ([Athletics](2-Mechanics/CLI/rules/skills.md#Athletics)) checks made to climb any surface his talons could reasonably grip.

***Maneuver (2/Day).*** When Riffin hits with an attack, he can choose to maneuver the enemy out of position, granting an ally within 5 feet of the target the opportunity to use their reaction to move away from this enemy at half their movement speed without provoking an [attack of opportunity](2-Mechanics/CLI/rules/actions.md#Opportunity%20Attack).

## Actions

***Multiattack.*** Riffin makes two short sword attacks.

***Short Sword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage.

***Talons.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage. The knight can choose to grapple a target hit by this attack as a bonus action.

***Wing Crest Shield (1/Day).*** Riffin casts the [gust of wind](2-Mechanics/CLI/spells/gust-of-wind.md) spell (save DC 15).
```
^statblock