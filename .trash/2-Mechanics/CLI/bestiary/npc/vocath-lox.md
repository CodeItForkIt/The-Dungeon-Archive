---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/lox
- monster/cr/5
- monster/size/large
- monster/type/celestial
aliases: ["Vocath"]
---
# Vocath
*Source: Light of Xaryxis p. 42*  

```ad-statblock
title: Vocath
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/LoX/Vocath.webp#token)
*Large celestial, typically  Lawful Neutral*

- **Armor Class** 13 ([mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 75 (`10d10 + 20`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|15 (+2)|18 (+4)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +7, Wisdom +6, Charisma +5
- **Skills** Insight +9, Perception +6, Persuasion +5
- **Senses** passive Perception 16
- **Languages** Common, Giant, telepathy 60 ft. (see also Mercane telepathy)
- **Challenge** 5

## Traits

***Mercane Telepathy.*** Vocath can communicate telepathically with any other mercane it knows, regardless of the distance between them.

***Spellcasting (Psionics).*** Vocath casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 15):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [light](2-Mechanics/CLI/spells/light.md)

**1/day each**: [dimension door](2-Mechanics/CLI/spells/dimension-door.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only)

## Actions

***Multiattack.*** Vocath makes three Psi-Imbued Blade attacks.

***Psi-Imbued Blade.*** *Melee Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) slashing damage, and if the target is a creature, it must succeed on a DC 15 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of Vocath until the end of the target's next turn.
```
^statblock