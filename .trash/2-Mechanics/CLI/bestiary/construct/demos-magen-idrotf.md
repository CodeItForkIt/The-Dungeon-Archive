---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/2
- monster/size/medium
- monster/type/construct
aliases: ["Demos Magen"]
---
# Demos Magen
*Source: Icewind Dale: Rime of the Frostmaiden p. 300*  

Demos magen wear armor, wield weapons, and typically serve as guards.

Magen are magical, humanlike beings created by a wizard spell (see the [create magen](2-Mechanics/CLI/spells/create-magen-idrotf.md) spell in appendix D) or by other arcane methods.

Though magen look like humanoids with green skin, they are constructs. When one is wounded, its blood is seen to have the color and consistency of mercury. They exist purely through magical means. When one is killed, its body disappears in a burst of harmless fire and a cloud of smoke that quickly dissipates.

```ad-statblock
title: Demos Magen
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Demos%20Magen.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 16 ([chain mail](2-Mechanics/CLI/items/chain-mail.md))
- **Hit Points** 51 (`6d8 + 24`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|14 (+2)|18 (+4)|10 (+0)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 2

## Traits

***Fiery End.*** If the magen dies, its body disintegrates in a harmless burst of fire and smoke, leaving behind anything it was wearing or carrying.

***Magic Resistance.*** The magen has advantage on saving throws against spells and other magical effects.

***Unusual Nature.*** The magen doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The magen makes two melee attacks.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+2|noform|avg|text(9)` (`2d6 + 2`) slashing damage.

***Light Crossbow.*** *Ranged Weapon Attack:* `dice:1d20+4|noform|text(+4)` to hit, range 80/320 ft., one target. *Hit:* `dice:1d8+2|noform|avg|text(6)` (`1d8 + 2`) piercing damage.
```
^statblock