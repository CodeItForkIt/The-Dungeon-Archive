---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/15
- monster/size/large
- monster/type/monstrosity
aliases: ["Lord of the Feast"]
---
# Lord of the Feast
*Source: Dungeons of Drakkenheim p. 211*  

This horrific albino garmyr stands well over twelve feet tall. He is covered in a mass of yellowish-white mangy fur, bloodstained and scarred from countless battles, and clad in a patchwork armour of leather, chain, and bladed plate with trophies—mummified heads—hanging from his belt. A mane of bony spines and tufts of barbed grey hair jut out from his head and down his back to a long white tail braided with skulls and bone fragments. His snarling visage is filled with long, razor-sharp fangs and smouldering red eyes. The Lord of The Feast holds an oversized longbow, strung with thick sinew. A quiver on his back holds enormous arrows, some bristling with barbed snares, others connected to coils of chains around the beast's wrists, while others are tipped with delerium shards.

```ad-statblock
title: Lord of the Feast
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Lord%20of%20the%20Feast.webp#token)
*Large monstrosity, Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 228 (`24d10 + 96`)
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|11 (+0)|18 (+4)|13 (+1)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +9, Constitution +9, Wisdom +9, Charisma +6
- **Skills** Athletics +9, Perception +14, Stealth +14, Survival +9
- **Senses** darkvision 120 ft., passive Perception 24
- **Languages** Abyssal
- **Challenge** 15

## Traits

***Legendary Resistance (3/Day).*** If the Lord of the Feast fails a saving throw, he can choose to succeed instead.

***Regeneration.*** The Lord of the Feast regains 20 hit points at the start of his turn if he has at least 1 hit point remaining.

***Close-Quarters Hunter.*** Being within 5 feet of a hostile creature doesn't impose disadvantage on the Lord of the Feast's ranged attack rolls.

***Predatory Senses.*** The Lord of the Feast has advantage on Wisdom ([Perception](2-Mechanics/CLI/rules/skills.md#Perception)) checks. He can pinpoint the position of any creature within 120 feet of him that is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible).

## Actions

***Multiattack.*** The Lord of the Feast makes three attacks: either one with each of its different arrow attacks, or one with his bite and two with his claws.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) piercing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage. A target hit by this attack must succeed on a DC 17 Constitution saving throw or gain one level of contamination.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft, one target. *Hit:* `dice:2d6+4|noform|avg|text(11)` (`2d6 + 4`) slashing damage.

***Contaminating Arrow.*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 150/600 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage. A target hit by this attack must succeed on a DC 17 Constitution saving throw or gain one level of contamination.

***Ensnaring Arrow.*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 150/600 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage. If the target is Large or smaller, it must succeed on a DC 17 Dexterity saving throw or become [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) in a magical snare for 1 minute. A [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) target can use its action to repeat the saving throw, ending the effect on itself on a success.

***Harpoon Arrow.*** *Ranged Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, range 150/600 ft., one target. *Hit:* `dice:2d8+4|noform|avg|text(13)` (`2d8 + 4`) piercing damage. If the target is a Huge or smaller creature, it must succeed on DC 17 Strength saving throw or be pulled up to 20 feet directly toward the Lord of the Feast.

## Legendary Actions

***Dash.*** The Lord of the Feast moves his speed without provoking opportunity attacks.

***Arrow (Costs 2 actions).*** The Lord of the Feast makes one arrow attack of his choice.

***Call of the Hunt (costs 3 actions).*** The Lord of the Feast releases a blood-curdling howl which can be heard all across Drakkenheim. Garmyr within 60 feet who can see and hear the Lord of the Feast can use their reaction to move up to half their speed and make one melee or ranged attack with advantage.
```
^statblock