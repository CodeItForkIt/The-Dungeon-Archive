---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/9
- monster/size/medium
- monster/type/aberration/mind-flayer
- monster/type/aberration/warlock
aliases: ["Qunbraxel"]
---
# Qunbraxel
*Source: Phandelver and Below: The Shattered Obelisk p. 135*  

Qunbraxel is an arrogant mind flayer warlock. Qunbraxel is always attended by four loyal grimlocks. They swap this duty with other grimlocks nearby, although Qunbraxel can hardly be bothered to tell one grimlock minion from another.

Cut off from any elder brain Qunbraxel considers worthy, the mind flayer hopes to join the Ilvaash fanatics and receive power and insight from the Far Realm.

```ad-statblock
title: Qunbraxel
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Qunbraxel.webp#token)
*Medium aberration (mind flayer, warlock), Lawful Evil*

- **Armor Class** 12 (15 with [mage armor](2-Mechanics/CLI/spells/mage-armor.md))
- **Hit Points** 112 (`15d8 + 45`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|14 (+2)|17 (+3)|19 (+4)|15 (+2)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +8, Wisdom +6, Charisma +8
- **Skills** Arcana +8, Insight +6, Perception +6, Stealth +6
- **Senses** darkvision 120 ft., passive Perception 16
- **Languages** Deep Speech, telepathy 60 ft., Undercommon
- **Challenge** 9

## Traits

***Magic Resistance.*** Qunbraxel has advantage on saving throws against spells and other magical effects.

***Spellcasting (Psionics).*** Qunbraxel casts one of the following spells, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 16):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [levitate](2-Mechanics/CLI/spells/levitate.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md) (self only), [mage hand](2-Mechanics/CLI/spells/mage-hand.md) (the hand is invisible), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [dominate monster](2-Mechanics/CLI/spells/dominate-monster.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md) (self only)

**2/day each**: [confusion](2-Mechanics/CLI/spells/confusion.md), [sending](2-Mechanics/CLI/spells/sending.md), [telekinesis](2-Mechanics/CLI/spells/telekinesis.md)

## Actions

***Multiattack.*** Qunbraxel makes two Eldritch Bolt attacks, or one Eldritch Bolt attack and one Tentacle attack.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) psychic damage. If the target is Medium or smaller, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 16) and must succeed on a DC 16 Intelligence saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the grapple ends.

***Eldritch Bolt.*** *Ranged Spell Attack:* `dice:1d20+8|noform|text(+8)` to hit, range 120 ft., one target. *Hit:* `dice:3d10+4|noform|avg|text(20)` (`3d10 + 4`) force damage.

***Extract Brain.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one Humanoid with the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition who is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Qunbraxel. *Hit:* `dice:10d10|noform|avg|text(55)` (`10d10`) piercing damage. If this damage reduces the target to 0 hit points, Qunbraxel kills it by extracting and devouring its brain.

***Mind Blast (Recharge 5-6).*** Qunbraxel magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 16 Intelligence saving throw or take `dice:5d8+4|noform|avg|text(26)` (`5d8 + 4`) psychic damage and have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
```
^statblock