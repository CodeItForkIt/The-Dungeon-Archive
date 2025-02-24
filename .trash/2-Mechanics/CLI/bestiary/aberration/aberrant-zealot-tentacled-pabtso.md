---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/8
- monster/size/medium
- monster/type/aberration
aliases: ["Aberrant Zealot (Tentacled)"]
---
# Aberrant Zealot (Tentacled)
*Source: Phandelver and Below: The Shattered Obelisk p. 181*  

```ad-statblock
title: Aberrant Zealot (Tentacled)
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Aberrant%20Zealot%20%28Tentacled%29.webp#token)
*Medium aberration, typically  Chaotic Evil*

- **Armor Class** 16 ([studded leather armor](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 93 (`17d8 + 17`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|18 (+4)|12 (+1)|13 (+1)| 8 (-1)|19 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Charisma +7
- **Skills** Perception +5
- **Senses** darkvision 60 ft., truesight 10 ft., passive Perception 15
- **Damage Resistances** psychic
- **Condition Immunities** [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common, Deep Speech
- **Challenge** 8

## Traits

***Aberrant Form.*** The zealot exudes the chaos of the Far Realm. Any non-Aberration creature that starts its turn within 5 feet of the zealot must succeed on a DC 15 Wisdom saving throw or take `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage.

***Weirdly Pliable.*** The zealot, along with any equipment it is wearing or carrying, is unnaturally flexible. The zealot can move through any space as narrow as 1 inch without squeezing.

***Spellcasting (Psionics).*** The zealot casts one of the following spells, requiring no components and using Charisma as the spellcasting ability (spell save DC 15):

**At will**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md)

**1/day each**: [arcane gate](2-Mechanics/CLI/spells/arcane-gate.md), [hunger of Hadar](2-Mechanics/CLI/spells/hunger-of-hadar.md)

## Actions

***Multiattack.*** The zealot makes one Psychic Rend attack and two Shortsword attacks.

***Psychic Rend.*** *Melee or Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 15 ft. or range 120 ft., one target. *Hit:* `dice:3d6+4|noform|avg|text(14)` (`3d6 + 4`) psychic damage, and the target must succeed on a DC 15 Wisdom saving throw or have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition until the start of the zealot's next turn.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 15 ft., one target. *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:2d6|noform|avg|text(7)` (`2d6`) psychic damage.

***Mind Blast (Recharge 5-6).*** The zealot magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 15 Intelligence saving throw or take `dice:4d8+4|noform|avg|text(22)` (`4d8 + 4`) psychic damage and have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition on itself on a success.

## Bonus Actions

***Void Warp (Recharge 5-6).*** The zealot teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 120 feet of itself, leaving a churning void in the space it left. Immediately after it teleports, each creature within 30 feet of the void other than the zealot must make a DC 15 Strength saving throw. On a failed save, a creature takes `dice:4d8|noform|avg|text(18)` (`4d8`) force damage and is pulled to the unoccupied space closest to the void. On a successful save, the creature takes half as much damage only. The void then disappears.
```
^statblock