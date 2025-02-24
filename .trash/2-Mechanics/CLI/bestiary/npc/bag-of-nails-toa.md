---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/toa
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/tabaxi
aliases: ["Bag of Nails"]
---
# Bag of Nails
*Source: Tomb of Annihilation p. 102*  

Bag of Nails yearns for a hunter's death. Senility has taken hold, and now he sees all creatures as his prey.

He explains that he came to Omu to find a fabled treasure called the Navel of the Moon. He hoped to use its alleged powers to find his lost son, but he has long since given up hope of ever finding it.

```ad-statblock
title: Bag of Nails
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Bag%20of%20Nails.webp#token)
*Medium humanoid (tabaxi), Chaotic Neutral*

- **Armor Class** 15 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft., climb 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|14 (+2)|13 (+1)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Intelligence +4
- **Skills** Acrobatics +6, Deception +3, Perception +3, Stealth +9
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** poison
- **Languages** Thieves' cant, Common, Dwarvish
- **Challenge** 8

## Traits

***Feline Agility.*** When Bag of Nails moves on its turn in combat, he can double his speed until the end of the turn. Once he uses this trait, Bag of Nails can't use it again until he moves 0 feet on one of his turns.

***Assassinate.*** During his first turn, Bag of Nails has advantage on attack rolls against any creature that hasn't taken a turn. Any hit Bag of Nails scores against a [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised) creature is a critical hit.

***Evasion.*** If Bag of Nails is subjected to an effect that allows him to make a Dexterity saving throw to take only half damage, Bag of Nails instead takes no damage if he succeeds on the saving throw, and only half damage if it fails.

***Sneak Attack (1/Turn).*** Bag of Nails deals an extra `dice:4d6|noform|avg|text(14)` (`4d6`) damage when he hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of his that isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and Bag of Nails doesn't have disadvantage on the attack roll.

## Actions

***Multiattack.*** Bag of Nails makes two shortsword attacks.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+3|noform|text(+3)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4|noform|avg|text(2)` (`1d4`) slashing damage.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage, and the target must make a DC 15 Constitution saving throw, taking `dice:7d6|noform|avg|text(24)` (`7d6`) poison damage on a failed save, or half as much damage on a successful one.

***Longbow.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 150/600 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage, and the target must make a DC 15 Constitution saving throw, taking `dice:7d6|noform|avg|text(24)` (`7d6`) poison damage on a failed save, or half as much damage on a successful one.
```
^statblock