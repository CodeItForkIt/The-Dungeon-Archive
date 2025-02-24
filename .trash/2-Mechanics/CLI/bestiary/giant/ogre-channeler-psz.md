---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/7
- monster/size/large
- monster/type/giant
aliases: ["Ogre Channeler"]
---
# Ogre Channeler
*Source: Plane Shift: Zendikar p. 31*  

The ogres of Zendikar are towering brutes driven by cruelty, greed, and savage ferocity. They favor the jagged mountains of Akoum but can be found on every continent. Their size and strength help protect them from the dangers of Zendikar, so they have little need of walls or roofs—which is good, since they have little skill at building. Ogre society, such as it is, revolves around leaders who gather small gangs (usually six to ten other ogres) to join them in pillaging, extorting, or slaving. The Monster Manual's [ogre](2-Mechanics/CLI/bestiary/giant/ogre.md) statistics work fine for Zendikar ogres.

Despite their low intelligence, some more clever ogres—perhaps represented as [oni](2-Mechanics/CLI/bestiary/giant/oni.md)—master the use of certain kinds of magic. The use of red mana complements an ogre's fierce and angry tendencies, and some ogres can produce fiery spells and manipulate the volcanic forces of Akoum. Other ogres channel black mana to immerse themselves in necromancy and diabolism, accentuating their amoral nature and their willingness to enslave others for their own benefit.

```ad-statblock
title: Ogre Channeler
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Ogre%20Channeler.webp#token)
*Large giant, Lawful Evil*

- **Armor Class** 16 ([chain mail](2-Mechanics/CLI/items/chain-mail.md))
- **Hit Points** 110 (`13d10 + 39`)
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|11 (+0)|16 (+3)|14 (+2)|12 (+1)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +3, Constitution +6, Wisdom +4, Charisma +5
- **Skills** Arcana +5, Deception +8, Perception +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Common, Giant
- **Challenge** 7

## Traits

***Magic Weapons.*** The ogre's weapon attacks are magical.

***Regeneration.*** The ogre regains 10 hit points at the start of its turn if it has at least 1 hit point.

***Innate Spellcasting.*** The ogre's innate spellcasting ability is Charisma (spell save DC 13). The ogre can innately cast the following spells, requiring no material components:

**At will**: [darkness](2-Mechanics/CLI/spells/darkness.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md)

**1/day each**: [charm person](2-Mechanics/CLI/spells/charm-person.md), [cone of cold](2-Mechanics/CLI/spells/cone-of-cold.md), [gaseous form](2-Mechanics/CLI/spells/gaseous-form.md), [sleep](2-Mechanics/CLI/spells/sleep.md)

## Actions

***Multiattack.*** The ogre makes two attacks, either with its claws or its glaive.

***Claw (Oni Form Only).*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) slashing damage.

***Glaive.*** *Melee Weapon Attack:* `dice:1d20+7|noform|text(+7)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+4|noform|avg|text(15)` (`2d10 + 4`) slashing damage, or `dice:1d10+4|noform|avg|text(9)` (`1d10 + 4`) slashing damage in Small or Medium form.

***Change Shape.*** The ogre magically polymorphs into a Small or Medium humanoid, into a Large giant, or back into its true form. Other than its size, its statistics are the same in each form. The only equipment that is transformed is its glaive, which shrinks so that it can be wielded in humanoid form. If the ogre dies, it reverts to its true form, and its glaive reverts to its normal size.
```
^statblock