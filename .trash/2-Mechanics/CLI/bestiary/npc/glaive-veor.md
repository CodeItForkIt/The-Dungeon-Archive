---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/11
- monster/size/medium
- monster/type/construct/warforged
aliases: ["Glaive"]
---
# Glaive
*Source: Vecna: Eve of Ruin p. 81*  

Since the Mournland's earliest days, Glaive has wielded her namesake weapon in service to the Lord of Blades' bloody conquest of the blighted region. Among the blades, Glaive is best known for her talent at self-modification. "Glaive" is etched onto the back of her neck-plate. It is the only name Glaive has ever known, and fellow blades don't dare call her anything else. Mournland adventurers, however, refer to the terrifying commander by another name: Kill Switch.

```ad-statblock
title: Glaive
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Glaive.webp#token)
*Medium construct (warforged), Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 187 (`22d8 + 88`)
- **Speed** 30 ft. (50 ft. with overdrive)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|16 (+3)|19 (+4)|11 (+0)|16 (+3)| 9 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +9, Dexterity +7, Wisdom +7
- **Skills** Athletics +9, Perception +7, Stealth +7, Survival +7
- **Senses** passive Perception 17
- **Damage Resistances** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common
- **Challenge** 11

## Traits

***Heatsink.*** When Glaive takes cold damage, her Overdrive immediately recharges.

***Pack Tactics.*** Glaive has advantage on attack rolls if at least one ally is within 5 feet of the creature she's attacking and the ally doesn't have the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

## Actions

***Multiattack.*** Glaive makes two Spiked Glaive attacks and two Serrated Bolt attacks.

***Spiked Glaive.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:1d10+5|noform|avg|text(10)` (`1d10 + 5`) piercing or slashing damage, or `dice:1d10+9|noform|avg|text(14)` (`1d10 + 9`) piercing or slashing damage if Glaive is in overdrive.

***Serrated Bolt.*** *Ranged Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 60 ft., one target. *Hit:* `dice:3d6+3|noform|avg|text(13)` (`3d6 + 3`) piercing damage. If Glaive has advantage on the attack roll, the serrated bolt lodges in the target, and the target's speed is reduced by 10 feet until the serrated bolt is removed. A target's speed can be reduced by only one serrated bolt at a time. A creature can use its action to remove a serrated bolt lodged in itself or another creature within its reach; when the bolt is removed from a creature, that creature takes `dice:2d4|noform|avg|text(5)` (`2d4`) slashing damage.

## Bonus Actions

***Overdrive (Recharges after Finishing a Short or Long Rest).*** Glaive enters a state of overdrive that lasts for 1 minute or until she has the [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) condition. While in overdrive, Glaive gains the following benefits:

- Glaive has advantage on Strength checks and Strength saving throws.  
- When Glaive makes a melee weapon attack, she gains a +4 bonus to the damage roll.  
- Glaive's speed increases to 50 feet.  

## Reactions

***Self-Preservation.*** In response to being hit by a weapon attack, Glaive reduces the damage by `dice:2d10|noform|avg|text(11)` (`2d10`).
```
^statblock