---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/10
- monster/size/medium
- monster/type/undead/mind-flayer
- monster/type/undead/wizard
aliases: ["Oshundo the Alhoon"]
---
# Oshundo the Alhoon
*Source: Phandelver and Below: The Shattered Obelisk p. 153*  

Oshundo lived in Illithinoch at the height of the mind flayer empire many centuries ago, but Oshundo was driven out for practicing arcane magic. It's obvious that this rejection still stings Oshundo, who refers to Illithinoch's longdead leaders as "ignorant fools" who are "closed to the flexibility and power of arcane magic."

```ad-statblock
title: Oshundo the Alhoon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Oshundo%20the%20Alhoon.webp#token)
*Medium undead (mind flayer, wizard), Neutral Evil*

- **Armor Class** 15 (natural armor)
- **Hit Points** 150 (`20d8 + 60`)
- **Speed** 30 ft., fly 15 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|12 (+1)|16 (+3)|19 (+4)|17 (+3)|17 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +7, Intelligence +8, Wisdom +7, Charisma +7
- **Skills** Arcana +8, History +8, Insight +7, Perception +7, Stealth +5
- **Senses** truesight 120 ft., passive Perception 17
- **Damage Resistances** cold, lightning, necrotic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Deep Speech, telepathy 120 ft., Undercommon
- **Challenge** 10

## Traits

***Magic Resistance.*** Oshundo has advantage on saving throws against spells and other magical effects.

***Spellcasting.*** Oshundo casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 16):

**At will**: [dancing lights](2-Mechanics/CLI/spells/dancing-lights.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [dominate monster](2-Mechanics/CLI/spells/dominate-monster.md), [globe of invulnerability](2-Mechanics/CLI/spells/globe-of-invulnerability.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [modify memory](2-Mechanics/CLI/spells/modify-memory.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only), [wall of force](2-Mechanics/CLI/spells/wall-of-force.md)

## Actions

***Multiattack.*** Oshundo makes two Chilling Grasp or Arcane Bolt attacks.

***Chilling Grasp.*** *Melee Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:4d6|noform|avg|text(14)` (`4d6`) cold damage, and Oshundo regains 14 hit points if the target is a creature.

***Arcane Bolt.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 120 ft., one target. *Hit:* `dice:8d6|noform|avg|text(28)` (`8d6`) force damage.

***Thundering Blast (Recharge 5-6).*** Oshundo emits a wave of domineering energy in a 60-foot cone. Each creature in that area must succeed on a DC 16 Intelligence saving throw or take `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) thunder damage and have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Reactions

***Negate Spell (3/Day).*** Oshundo targets one creature it can perceive within 60 feet of itself that is casting a spell. If the spell is 3rd level or lower, the spell fails, but any spell slots or charges aren't wasted.
```
^statblock