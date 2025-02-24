---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgdia
- monster/cr/25
- monster/size/large
- monster/type/fiend/devil
aliases: ["Bel"]
---
# Bel
*Source: Baldur's Gate: Descent Into Avernus p. 115*  

From his bastion, Zariel's second-in-command and the former lord of Avernus oversees the forges that furnish weapons and armor for the Blood War. Though Asmodeus has instructed Zariel to accept Bel as her advisor, Bel and Zariel loathe each other and invent distractions to keep them apart.

Bel outwardly plays the role of Zariel's loyal vassal. However, Bel rankles at Zariel's rulership of the layer of the Nine Hells that was once his, but he won't challenge her directly as long as he thinks Asmodeus supports Zariel.

```ad-statblock
title: Bel
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGDIA/Bel.webp#token)
*Large fiend (devil), Lawful Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 364 (`27d10 + 216`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|14 (+2)|26 (+8)|25 (+7)|19 (+4)|26 (+8)|

- **Proficiency Bonus** +8
- **Saving Throws** Dexterity +10, Constitution +16, Wisdom +12
- **Skills** Arcana +15, Deception +16, Insight +12, Persuasion +16
- **Senses** truesight 120 ft., passive Perception 14
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Infernal, telepathy 120 ft.
- **Challenge** 25

## Traits

***Fear Aura.*** Any creature hostile to Bel that starts its turn within 20 feet of him must make a DC 23 Wisdom saving throw, unless Bel is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). Unless the save succeeds, the creature is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the start of its next turn. If a creature's saving throw is successful, the creature is immune to Bel's Fear Aura for the next 24 hours.

***Legendary Resistance (3/Day).*** If Bel fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Bel has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** Bel's weapon attacks are magical.

***Innate Spellcasting.*** Bel's spellcasting ability is Charisma (spell save DC 23). Bel can innately cast the following spells, requiring no material components:

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [fireball](2-Mechanics/CLI/spells/fireball.md)

**1/day each**: [imprisonment](2-Mechanics/CLI/spells/imprisonment.md), [meteor swarm](2-Mechanics/CLI/spells/meteor-swarm.md)

**3/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [hold monster](2-Mechanics/CLI/spells/hold-monster.md), [mirror image](2-Mechanics/CLI/spells/mirror-image.md), [mislead](2-Mechanics/CLI/spells/mislead.md), [raise dead](2-Mechanics/CLI/spells/raise-dead.md), [teleport](2-Mechanics/CLI/spells/teleport.md), [wall of fire](2-Mechanics/CLI/spells/wall-of-fire.md)

## Actions

***Multiattack.*** Bel makes three attacks: two with his greatsword and one with his tail.

***Greatsword.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 10 ft., one target. *Hit:* `dice:4d6+9|noform|avg|text(23)` (`4d6 + 9`) slashing damage plus `dice:6d6|noform|avg|text(21)` (`6d6`) fire damage. If the target is a flammable object that is not being held or worn, it catches fire.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+9|noform|avg|text(25)` (`3d10 + 9`) bludgeoning damage. If the target is a creature, it must succeed on a DC 23 Constitution saving throw or be [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) until the end of its next turn.

## Legendary Actions

***Fireball.*** Bel casts [fireball](2-Mechanics/CLI/spells/fireball.md).

***Tactical Edge (Costs 2 Actions).*** Roll a `dice:d6|noform|avg` (`d6`) for Bel. The number rolled on the die is subtracted from the next attack roll made against Bel or an ally of his choice within the next minute.

***Summon Ice Devil (Costs 3 Actions).*** Bel magically summons an ice devil with an ice spear (as described in the ice devil's entry in the Monster Manual). The ice devil appears in an unoccupied space within 60 feet of Bel, acts as Bel's ally, and can summon other devils if it has such power. The ice devil remains until Bel dies or until he dismisses it as an action.
```
^statblock