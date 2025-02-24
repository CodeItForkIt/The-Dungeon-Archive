---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cos
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Vistana Spy"]
---
# Vistana Spy
*Source: Curse of Strahd p. 28*  

```ad-statblock
title: Vistana Spy
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Vistana%20Spy.webp#token)
*Medium humanoid (any race), Any alignment*

- **Armor Class** 12
- **Hit Points** 27 (`6d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|10 (+0)|12 (+1)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** Deception +5, Insight +4, Investigation +5, Perception +6, Persuasion +5, Sleight of Hand +4, Stealth +4
- **Senses** passive Perception 16
- **Languages** any two languages
- **Challenge** 1

## Traits

***Cunning Action.*** On each of its turns, the spy can use a bonus action to take the Dash, Disengage, or Hide action.

***Sneak Attack (1/Turn).*** The spy deals an extra `dice:2d6|noform|avg|text(7)` (`2d6`) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the spy that isn't [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) and the spy doesn't have disadvantage on the attack roll.

## Actions

***Multiattack.*** The spy makes two melee attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage.

***Hand Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 30/120 ft., one target. *Hit:* `dice:1d6+2|noform|avg|text(5)` (`1d6 + 2`) piercing damage.

***Curse (Recharges After a Long Rest).*** 13

- The target is unable to perform a certain kind of act involving fine motor control, such as tying knots, writing, playing an instrument, sewing, or casting spells that have somatic components. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- The target's appearance changes in a sinister yet purely cosmetic way. For example, the curse can place a scar on the target's face, turn the target's teeth into yellow fangs, or give the target bad breath. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- A nonmagical item in the target's possession (chosen by the DM) disappears and can't be found until the curse ends. The lost item can weigh no more than 1 pound. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- The target gains vulnerability to a damage type of the Vistana's choice. When this curse ends, the Vistana takes `dice:3d6|noform|avg` (`3d6`) psychic damage.  
- The target has disadvantage on ability checks and saving throws tied to one ability score of the Vistana's choice. When this curse ends, the Vistana takes `dice:3d6|noform|avg` (`3d6`) psychic damage.  
- The target's attunement to one magic item (chosen by the DM) ends, and the target can't attune to the chosen item until the curse ends. When this curse ends, the Vistana takes `dice:5d6|noform|avg` (`5d6`) psychic damage.  
- The target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), or both. When this curse ends, the Vistana takes `dice:5d6|noform|avg` (`5d6`) psychic damage.  

The curse lasts until ended with a [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell, a [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell, or similar magic. It doesn't end when the target dies. If a cursed target is returned to life, the curse remains in effect.

***Evil Eye (Recharges after a Short or Long Rest).*** 13

A Vistana who uses Evil Eye can't use it again before finishing a short or long rest. Once a target succeeds on a saving throw against a Vistana's Evil Eye, it is immune to the Evil Eye of all Vistani for 24 hours.
```
^statblock