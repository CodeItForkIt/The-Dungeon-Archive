---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/11
- monster/size/large
- monster/type/elemental
aliases: ["Shanzezim"]
---
# Shanzezim
*Source: Vecna: Eve of Ruin*  

```ad-statblock
title: Shanzezim
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Shanzezim.webp#token)
*Large elemental, Chaotic Neutral*

- **Armor Class** 17 (natural armor)
- **Hit Points** 229 (`17d10 + 136`)
- **Speed** 30 ft., fly 60 ft., swim 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|12 (+1)|26 (+8)|18 (+4)|17 (+3)|18 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +5, Wisdom +7, Charisma +8
- **Skills** ⏤
- **Senses** blindsight 30 ft., darkvision 120 ft., passive Perception 13
- **Damage Resistances** acid, cold, lightning
- **Languages** Aquan
- **Challenge** 11

## Traits

***Amphibious.*** Shanzezim can breathe air and water.

***Elemental Demise.*** If Shanzezim dies, its body disintegrates into a burst of water and foam, leaving behind only equipment Shanzezim was wearing or carrying.

***Innate Spellcasting.*** Shanzezim's innate spellcasting ability is Charisma (spell save DC 16, `dice:1d20+8|noform|text(+8)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will**: [create or destroy water](2-Mechanics/CLI/spells/create-or-destroy-water.md), [detect evil and good](2-Mechanics/CLI/spells/detect-evil-and-good.md), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [fog cloud](2-Mechanics/CLI/spells/fog-cloud.md), [purify food and drink](2-Mechanics/CLI/spells/purify-food-and-drink.md)

**1/day each**: [conjure elemental](2-Mechanics/CLI/spells/conjure-elemental.md) ([water elemental](2-Mechanics/CLI/bestiary/elemental/water-elemental.md) only), [control water](2-Mechanics/CLI/spells/control-water.md), [gaseous form](2-Mechanics/CLI/spells/gaseous-form.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md), [plane shift](2-Mechanics/CLI/spells/plane-shift.md)

**3/day each**: [tongues](2-Mechanics/CLI/spells/tongues.md), [water breathing](2-Mechanics/CLI/spells/water-breathing.md), [water walk](2-Mechanics/CLI/spells/water-walk.md)

## Actions

***Multiattack.*** Shanzezim makes two trident attacks.

***Trident.*** *Melee or Ranged Weapon Attack:* `dice:1d20+10|noform|text(+10)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:2d6+6|noform|avg|text(13)` (`2d6 + 6`) piercing damage, or `dice:2d8+6|noform|avg|text(15)` (`2d8 + 6`) piercing damage if used with two hands to make a melee attack.

***Water Jet.*** Shanzezim magically shoots water in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 16 Dexterity saving throw. On a failure, a target takes `dice:6d6|noform|avg|text(21)` (`6d6`) bludgeoning damage and, if it is Huge or smaller, is pushed up to 20 feet away from Shanzezim and knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone). On a success, a target takes half the bludgeoning damage, but is neither pushed nor knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone).
```
^statblock