---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/3
- monster/size/medium
- monster/type/construct
aliases: ["Galvan Magen"]
---
# Galvan Magen
*Source: Icewind Dale: Rime of the Frostmaiden p. 301*  

Galvan magen can fly. They also store static electricity, which they discharge as lightning bolts.

Magen are magical, humanlike beings created by a wizard spell (see the [create magen](2-Mechanics/CLI/spells/create-magen-idrotf.md) spell in appendix D) or by other arcane methods.

Though magen look like humanoids with green skin, they are constructs. When one is wounded, its blood is seen to have the color and consistency of mercury. They exist purely through magical means. When one is killed, its body disappears in a burst of harmless fire and a cloud of smoke that quickly dissipates.

```ad-statblock
title: Galvan Magen
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Galvan%20Magen.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 14
- **Hit Points** 68 (`8d8 + 32`)
- **Speed** 30 ft., fly 30 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|18 (+4)|18 (+4)|12 (+1)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 10
- **Damage Immunities** lightning, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 3

## Traits

***Fiery End.*** If the magen dies, its body disintegrates in a harmless burst of fire and smoke, leaving behind anything it was wearing or carrying.

***Magic Resistance.*** The magen has advantage on saving throws against spells and other magical effects.

***Unusual Nature.*** The magen doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The magen makes two Shocking Touch attacks.

***Shocking Touch.*** *Melee Spell Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target (the magen has advantage on the attack roll if the target is wearing armor made of metal). *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) lightning damage.

***Static Discharge (Recharge 5-6).*** The magen discharges a lightning bolt in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 14 Dexterity saving throw (with disadvantage if the creature is wearing armor made of metal), taking `dice:4d10|noform|avg|text(22)` (`4d10`) lightning damage on a failed save, or half as much damage on a successful one.
```
^statblock