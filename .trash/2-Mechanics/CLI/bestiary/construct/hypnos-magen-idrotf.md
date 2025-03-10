---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/1
- monster/size/medium
- monster/type/construct
aliases: ["Hypnos Magen"]
---
# Hypnos Magen
*Source: Icewind Dale: Rime of the Frostmaiden p. 301*  

Hypnos magen are telepathic and use their power of suggestion to control others. Their creators use them to force enemies to withdraw or surrender.

A hypnos magen carries no weapons, relying entirely on its psychic abilities to manipulate and harm other creatures.

Magen are magical, humanlike beings created by a wizard spell (see the [create magen](2-Mechanics/CLI/spells/create-magen-idrotf.md) spell in appendix D) or by other arcane methods.

Though magen look like humanoids with green skin, they are constructs. When one is wounded, its blood is seen to have the color and consistency of mercury. They exist purely through magical means. When one is killed, its body disappears in a burst of harmless fire and a cloud of smoke that quickly dissipates.

```ad-statblock
title: Hypnos Magen
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Hypnos%20Magen.webp#token)
*Medium construct, Unaligned*

- **Armor Class** 12
- **Hit Points** 34 (`4d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|18 (+4)|14 (+2)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 10
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak, telepathy 30 ft.
- **Challenge** 1

## Traits

***Fiery End.*** If the magen dies, its body disintegrates in a harmless burst of fire and smoke, leaving behind anything it was wearing or carrying.

***Magic Resistance.*** The magen has advantage on saving throws against spells and other magical effects.

***Unusual Nature.*** The magen doesn't require air, food, drink, or sleep.

## Actions

***Psychic Lash.*** The magen's eyes glow silver as it targets one creature that it can see within 60 feet of it. The target must succeed on a DC 12 Wisdom saving throw or take `dice:2d10|noform|avg|text(11)` (`2d10`) psychic damage.

***Suggestion.*** The magen casts the [suggestion](2-Mechanics/CLI/spells/suggestion.md) spell (save DC 12), requiring no material components. The target must be a creature that the magen can communicate with telepathically. If it succeeds on its saving throw, the target is immune to this magen's [suggestion](2-Mechanics/CLI/spells/suggestion.md) spell for the next 24 hours. The magen's spellcasting ability is Intelligence.
```
^statblock