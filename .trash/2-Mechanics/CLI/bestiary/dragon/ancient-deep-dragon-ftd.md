---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ftd
- monster/cr/18
- monster/size/gargantuan
- monster/type/dragon
aliases: ["Ancient Deep Dragon"]
---
# Ancient Deep Dragon
*Source: Fizban's Treasury of Dragons p. 173*  

Making their lairs in the depths of the Underdark, deep dragons are nightmarish cousins of chromatic dragons. The warped magical energy of their subterranean realm gives them the ability to exhale magical spores that instill fear and scar the mind.

Deep dragons' black-and-gray hide is smooth like a salamander's, and their eyes are pale. As they age, their spore breath causes fungi to bloom across their skin, especially around the head and neck. Their wings are attached to their front legs and can fold in close to the body, allowing deep dragons to easily maneuver through relatively narrow tunnels.

Deep dragons often hoard secrets, delighting in knowledge of far-off lands. Many seek out new insights and tricks that they can use against other denizens of the Underdark, preferring social manipulation and crafty dealmaking to exerting themselves in combat. Deep dragons look down on any creature that isn't useful to them, though they are willing to bargain for knowledge they lack.

## A Deep Dragon's Lair

Deep dragons make their lairs in well-hidden caves or sunless beaches in the Underdark, and these sites are often inaccessible without the ability to fly or dive underwater. They fill their lairs with secret passages and hiding places that allow them to escape or ambush visitors if the need arises. A well-cultivated lair abounds with Underdark fungi and plants, with the floor, walls, and ceiling covered in carpets of mold and moss, or featuring larger mushrooms and plants in neatly organized displays.

The challenge rating of a legendary deep dragon increases by 1 when it's encountered in its lair.

## Statblock

```ad-statblock
title: Ancient Deep Dragon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/FTD/Ancient%20Deep%20Dragon.webp#token)
*Gargantuan dragon, typically  Neutral Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 201 (`13d20 + 65`)
- **Speed** 40 ft., burrow 40 ft., fly 80 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|16 (+3)|20 (+5)|19 (+4)|18 (+4)|21 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +9, Constitution +11, Wisdom +10, Charisma +11
- **Skills** Perception +10, Persuasion +17, Stealth +15
- **Senses** blindsight 60 ft., darkvision 300 ft., passive Perception 20
- **Damage Resistances** poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Draconic, Undercommon
- **Challenge** 18

## Traits

***Legendary Resistance (3/Day).*** If the dragon fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The dragon makes one Bite attack and two Claw attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+6|noform|avg|text(17)` (`2d10 + 6`) piercing damage plus `dice:2d10|noform|avg|text(11)` (`2d10`) poison damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft., one target. *Hit:* `dice:1d8+6|noform|avg|text(10)` (`1d8 + 6`) bludgeoning damage. If the target is a creature, it must succeed on a DC 20 Strength saving throw or be knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).

***Change Shape.*** The dragon magically transforms into any creature that is Medium or Small, while retaining its game statistics (other than its size). This transformation ends if the dragon is reduced to 0 hit points or uses its action to end it.

***Nightmare Breath (Recharge 5-6).*** The dragon exhales a cloud of spores in a 90-foot cone. Each creature in that area must make a DC 19 Wisdom saving throw. On a failed save, the creature takes `dice:9d10|noform|avg|text(49)` (`9d10`) psychic damage, and it is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the dragon for 1 minute. On a successful save, the creature takes half as much damage with no additional effects. A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Legendary Actions

***Commanding Spores.*** The dragon releases spores around a creature within 30 feet of it that it can see. The target must succeed on a DC 19 Wisdom saving throw or use its reaction to make a melee weapon attack against a random creature within reach. If no creatures are within reach, or the target can't take a reaction, it takes `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage.

***Tail.*** The dragon makes one Tail attack.

***Spore Salvo (Costs 2 Actions).*** The dragon releases poisonous spores around a creature within 30 feet of it that it can see. The target must succeed on a DC 19 Constitution saving throw or take `dice:8d6|noform|avg|text(28)` (`8d6`) poison damage and become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. The [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

![Deep Dragon](2-Mechanics/CLI/bestiary/legendary-group/deep-dragon-ftd.md)
```
^statblock