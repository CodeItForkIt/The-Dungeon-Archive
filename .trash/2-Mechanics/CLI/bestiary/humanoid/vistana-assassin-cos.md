---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cos
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Vistana Assassin"]
---
# Vistana Assassin
*Source: Curse of Strahd p. 28*  

```ad-statblock
title: Vistana Assassin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Vistana%20Assassin.webp#token)
*Medium humanoid (any race), Any Non-Good alignment*

- **Armor Class** 15 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 78 (`12d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|14 (+2)|13 (+1)|11 (+0)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6, Intelligence +4
- **Skills** Acrobatics +6, Deception +3, Perception +3, Stealth +9
- **Senses** passive Perception 13
- **Damage Resistances** poison
- **Languages** Thieves' cant plus any two languages
- **Challenge** 8

## Traits

***Assassinate.*** During its first turn, the assassin has advantage on attack rolls against any creature that hasn't taken a turn. Any hit the assassin scores against a [surprised](2-Mechanics/CLI/rules/conditions.md#Surprised) creature is a critical hit.

***Evasion.*** If the assassin is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the assassin instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

***Sneak Attack (1/Turn).*** The assassin deals an extra `dice:4d6|noform|avg|text(14)` (`4d6`) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the assassin that isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and the assassin doesn't have disadvantage on the attack roll.

## Actions

***Multiattack.*** The assassin makes two shortsword attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) piercing damage, and the target must make a DC 15 Constitution saving throw, taking `dice:7d6|noform|avg|text(24)` (`7d6`) poison damage on a failed save, or half as much damage on a successful one.

***Light Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d8+3|noform|avg|text(7)` (`1d8 + 3`) piercing damage, and the target must make a DC 15 Constitution saving throw, taking `dice:7d6|noform|avg|text(24)` (`7d6`) poison damage on a failed save, or half as much damage on a successful one.

***Curse (Recharges After a Long Rest).*** 11

- The target is unable to perform a certain kind of act involving fine motor control, such as tying knots, writing, playing an instrument, sewing, or casting spells that have somatic components. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- The target's appearance changes in a sinister yet purely cosmetic way. For example, the curse can place a scar on the target's face, turn the target's teeth into yellow fangs, or give the target bad breath. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- A nonmagical item in the target's possession (chosen by the DM) disappears and can't be found until the curse ends. The lost item can weigh no more than 1 pound. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- The target gains vulnerability to a damage type of the Vistana's choice. When this curse ends, the Vistana takes `dice:3d6|noform|avg` (`3d6`) psychic damage.  
- The target has disadvantage on ability checks and saving throws tied to one ability score of the Vistana's choice. When this curse ends, the Vistana takes `dice:3d6|noform|avg` (`3d6`) psychic damage.  
- The target's attunement to one magic item (chosen by the DM) ends, and the target can't attune to the chosen item until the curse ends. When this curse ends, the Vistana takes `dice:5d6|noform|avg` (`5d6`) psychic damage.  
- The target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), or both. When this curse ends, the Vistana takes `dice:5d6|noform|avg` (`5d6`) psychic damage.  

The curse lasts until ended with a [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell, a [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell, or similar magic. It doesn't end when the target dies. If a cursed target is returned to life, the curse remains in effect.

***Evil Eye (Recharges after a Short or Long Rest).*** 11

A Vistana who uses Evil Eye can't use it again before finishing a short or long rest. Once a target succeeds on a saving throw against a Vistana's Evil Eye, it is immune to the Evil Eye of all Vistani for 24 hours.
```
^statblock