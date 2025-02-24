---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cos
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
aliases: ["Vistana Bandit Captain"]
---
# Vistana Bandit Captain
*Source: Curse of Strahd p. 28*  

```ad-statblock
title: Vistana Bandit Captain
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Vistana%20Bandit%20Captain.webp#token)
*Medium humanoid (any race), Any Non-Lawful alignment*

- **Armor Class** 15 ([studded leather](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 65 (`10d8 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|16 (+3)|14 (+2)|14 (+2)|11 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Strength +4, Dexterity +5, Wisdom +2
- **Skills** Athletics +4, Deception +4
- **Senses** passive Perception 10
- **Languages** any two languages
- **Challenge** 2

## Actions

***Multiattack.*** The captain makes three melee attacks: two with its scimitar and one with its dagger. Or the captain makes two ranged attacks with its daggers.

***Scimitar.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|avg|text(6)` (`1d6 + 3`) slashing damage.

***Dagger.*** *Melee or Ranged Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage.

***Curse (Recharges After a Long Rest).*** 12

- The target is unable to perform a certain kind of act involving fine motor control, such as tying knots, writing, playing an instrument, sewing, or casting spells that have somatic components. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- The target's appearance changes in a sinister yet purely cosmetic way. For example, the curse can place a scar on the target's face, turn the target's teeth into yellow fangs, or give the target bad breath. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- A nonmagical item in the target's possession (chosen by the DM) disappears and can't be found until the curse ends. The lost item can weigh no more than 1 pound. When this curse ends, the Vistana takes `dice:1d6|noform|avg` (`1d6`) psychic damage.  
- The target gains vulnerability to a damage type of the Vistana's choice. When this curse ends, the Vistana takes `dice:3d6|noform|avg` (`3d6`) psychic damage.  
- The target has disadvantage on ability checks and saving throws tied to one ability score of the Vistana's choice. When this curse ends, the Vistana takes `dice:3d6|noform|avg` (`3d6`) psychic damage.  
- The target's attunement to one magic item (chosen by the DM) ends, and the target can't attune to the chosen item until the curse ends. When this curse ends, the Vistana takes `dice:5d6|noform|avg` (`5d6`) psychic damage.  
- The target is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), or both. When this curse ends, the Vistana takes `dice:5d6|noform|avg` (`5d6`) psychic damage.  

The curse lasts until ended with a [greater restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell, a [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell, or similar magic. It doesn't end when the target dies. If a cursed target is returned to life, the curse remains in effect.

***Evil Eye (Recharges after a Short or Long Rest).*** 12

A Vistana who uses Evil Eye can't use it again before finishing a short or long rest. Once a target succeeds on a saving throw against a Vistana's Evil Eye, it is immune to the Evil Eye of all Vistani for 24 hours.

## Reactions

***Parry.*** The captain adds 2 to its AC against one melee attack that would hit it. To do so, the captain must see the attacker and be wielding a melee weapon.
```
^statblock