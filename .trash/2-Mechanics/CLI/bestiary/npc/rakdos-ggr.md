---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/24
- monster/size/huge
- monster/type/fiend/demon
aliases: ["Rakdos"]
---
# Rakdos
*Source: Guildmasters' Guide to Ravnica p. 247*  

Rakdos, the demon for whom his cult is named, embodies hedonism. He is also the consummate entertainer, whose mere appearance is an act of grisly performance art. A monstrous figure standing thirty feet tall, spreading enormous wings, crowned with fire and swinging a flaming scythe, Rakdos demands the spotlight. His every entrance is a showstopper.

Sometimes after his grand entrance, Rakdos crouches to witness the performances of those who adore him. To them, his opinion is the only one that matters, but he is a demanding spectator. He has seen thousands of years of circus tricks and has no patience for performers who don't give their all. His flaming scythe has brought more than one tepid show to a sudden and spectacular close. Jaded as he is, Rakdos attends his cult's performances only rarely. He often retreats into his lair below the cult's guildhall for months or years at a time, but his followers know that he might emerge at any time to witness the latest spectacle.

```ad-statblock
title: Rakdos
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Rakdos.webp#token)
*Huge fiend (demon), Chaotic Evil*

- **Armor Class** 20 (natural armor)
- **Hit Points** 300 (`24d12 + 144`)
- **Speed** 40 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|15 (+2)|22 (+6)|14 (+2)|18 (+4)|30 (+10)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +15, Constitution +13, Wisdom +11, Charisma +17
- **Skills** Intimidation +17, Performance +17, Persuasion +17
- **Senses** truesight 120 ft., passive Perception 14
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common
- **Challenge** 24

## Traits

***Captivating Presence.*** Any creature that starts its turn within 30 feet of Rakdos must make a DC 25 Wisdom saving throw. On a failed save, the creature becomes [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by Rakdos for 1 minute or until the creature is farther than 30 feet away from him. On a successful save, the creature becomes immune to Rakdos's Captivating Presence for 24 hours.

***Cruel Entertainment.*** When a creature Rakdos can see within 60 feet of him is reduced to 0 hit points, Rakdos gains 25 temporary hit points.

***Legendary Resistance (3/Day).*** If Rakdos fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Rakdos has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** Rakdos's weapon attacks are magical.

***Innate Spellcasting.*** Rakdos's spellcasting ability is Charisma (spell save DC 25). He can innately cast [hellish rebuke](2-Mechanics/CLI/spells/hellish-rebuke.md) (at 5th level) at will, requiring no material components.

**At will**: [hellish rebuke](2-Mechanics/CLI/spells/hellish-rebuke.md)

## Actions

***Multiattack.*** Rakdos makes two attacks with his Curtain-Call Scythe or his claws.

***Curtain-Call Scythe.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+8|noform|avg|text(24)` (`3d10 + 8`) slashing damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) fire damage.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+15|noform|text(+15)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+8|noform|avg|text(17)` (`2d8 + 8`) slashing damage.

## Legendary Actions

***Sadistic Revelry.*** Each creature within 60 feet of Rakdos that is his ally or is [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by him must use its reaction to move up to half its speed toward the creature closest to it that it can see, provided it isn't already within 5 feet of that creature. It then must make one melee attack against that creature if it is able to do so.

***Scythe (Costs 2 Actions).*** Rakdos uses Curtain-Call Scythe.

***Touch of Pain (Costs 3 Actions).*** Rakdos makes a claw attack against one creature within 10 feet of him. The target must succeed on a DC 25 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. While [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) in this way, the creature can't maintain [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) on a spell or any other effect that requires [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration). The [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock