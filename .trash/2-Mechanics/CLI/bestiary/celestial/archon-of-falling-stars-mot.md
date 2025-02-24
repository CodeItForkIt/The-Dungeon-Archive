---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mot
- monster/cr/12
- monster/size/medium
- monster/type/celestial
aliases: ["Archon of Falling Stars"]
---
# Archon of Falling Stars
*Source: Mythic Odysseys of Theros p. 212*  

The epic accounting of the world's earliest histories called *The Cosmogony* recounts the battle between a group of the gods' champions and a mighty archon, which took place at the mysterious eastern edge of the world. Defeated, the falling archon is said to have met the rising sun. But Heliod showed mercy to the penitent archon, who swore to uphold justice and righteousness in the world's wildest places. As a sign of his mercy, Heliod gave the archon a spear that rivaled his own in its brilliance. This was the first archon of falling stars.

The mysterious conquerors known as archons once ruled vast empires. These armored warlords saw themselves as champions of merciless justice, and they ruled with iron fists. But their dominance ultimately came to an end. As the archon overlords toppled, they scattered to the fringes of the world, and their holdings developed into the poleis of today.

Even though the age of archons is long past, many wonder if the few surviving archons might someday attempt to reestablish their empire or if they are truly resigned to their lesser role in the world.

```ad-statblock
title: Archon of Falling Stars
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Archon%20of%20Falling%20Stars.webp#token)
*Medium celestial, Lawful Good*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 144 (`17d8 + 68`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|15 (+2)|19 (+4)|15 (+2)|21 (+5)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +9, Constitution +8, Wisdom +9, Charisma +8
- **Skills** Arcana +6, History +6, Insight +9, Perception +9
- **Senses** truesight 120 ft., passive Perception 19
- **Damage Immunities** radiant
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** all
- **Challenge** 12

## Traits

***Magic Resistance.*** The archon has advantage on saving throws against spells and other magical effects.

***Mount.*** If the archon isn't mounted, it can use a bonus action to magically teleport onto the creature serving as its mount, provided the archon and its mount are on the same plane of existence. When it teleports, the archon appears astride the mount, along with any equipment it is wearing or carrying. While mounted and not [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), the archon can't be [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised), and both it and its mount have advantage on Dexterity saving throws. If the archon is reduced to 0 hit points while riding its mount, the mount is reduced to 0 hit points as well.

***Radiant Rebirth (Recharges after a Long Rest).*** If the archon is reduced to 0 hit points, it regains 30 hit points and springs back to its feet with a burst of radiance. Each creature of the archon's choice within 30 feet of it must succeed on a DC 16 Constitution saving throw, or the creature takes `dice:3d8|noform|avg|text(13)` (`3d8`) radiant damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the start of the archon's turn.

***Innate Spellcasting.*** The archon's spellcasting ability is Wisdom (spell save DC 17, `dice:1d20+9|noform|text(+9)` to hit with spell attacks). The archon can innately cast the following spells, requiring no material components:

**At will**: [command](2-Mechanics/CLI/spells/command.md), [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md), [spare the dying](2-Mechanics/CLI/spells/spare-the-dying.md)

**1/day each**: [crusader's mantle](2-Mechanics/CLI/spells/crusaders-mantle.md), [spirit guardians](2-Mechanics/CLI/spells/spirit-guardians.md)

## Actions

***Multiattack.*** The archon makes two attacks with its radiant spear.

***Radiant Spear.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) radiant damage.

## Legendary Actions

***Attack.*** The archon makes a radiant spear attack or casts [guiding bolt](2-Mechanics/CLI/spells/guiding-bolt.md).

***Coordinated Assault (Costs 2 Actions).*** The archon makes a radiant spear attack, and then its mount can use its reaction to make a melee weapon attack.

***Return to Nyx (Costs 3 Actions).*** The archon causes a corpse it can see within 30 feet of it to burst into a shower of radiant stars leaving no trace of it behind. Everything it is wearing or carrying remains. Each creature within 10 feet of the corpse when it bursts must succeed on a DC 16 Dexterity saving throw or take `dice:4d10|noform|avg|text(22)` (`4d10`) radiant damage.
```
^statblock