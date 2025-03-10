---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/22
- monster/size/huge
- monster/type/fiend/devil
aliases: ["Geryon"]
---
# Geryon
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 136, Mordenkainen's Tome of Foes p. 173*  

Geryon is locked in an endless struggle with Levistus for control of Stygia. The two have fought for centuries, each displacing the other innumerable times. Currently, Levistus claims lordship over Stygia, but he has been trapped in an enormous block of ice at the command of Asmodeus. In response, Geryon is marshaling his followers, hoping to use this opportunity to replace his hated rival.

Among the archdevils, Geryon is known for his martial prowess. He is a ferocious hunter and a relentless tracker. He often joins his troops in battle; he loves to feel flesh and steel sundered beneath his claws and to taste his foes' blood. Yet Geryon's ferocity has also limited his ability to collect souls and forge an effective hierarchy. Sages who study the Nine Hells believe the battle for control of Stygia is a test staged by Asmodeus in hopes of purging the worst impulses from both Geryon and Levistus—or discovering a competent replacement for both.

## Cultists of Geryon

> [!note]
> See the Cult of Geryon entry.

## Geryon's Lair

Geryon has recently reclaimed his ancient fortress, Coldsteel, a sprawling complex that rises from the icy center of Stygia. He roams the passages, spitting oaths of vengeance against Asmodeus and hatching schemes to reclaim his standing from Levistus. The challenge rating of Geryon is 23 (50,000 XP) when he's encountered in his lair.

## Statblock

```ad-statblock
title: Geryon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Geryon.webp#token)
*Huge fiend (devil), Lawful Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 300 (`24d12 + 144`)
- **Speed** 30 ft., fly 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|29 (+9)|17 (+3)|22 (+6)|19 (+4)|16 (+3)|23 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +10, Constitution +13, Wisdom +10, Charisma +13
- **Skills** Deception +13, Intimidation +13, Perception +10
- **Senses** truesight 120 ft., passive Perception 20
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** cold, fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 22

## Traits

***Legendary Resistance (3/Day).*** If Geryon fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Geryon has advantage on saving throws against spells and other magical effects.

***Regeneration.*** Geryon regains 20 hit points at the start of his turn. If he takes radiant damage, this trait doesn't function at the start of his next turn. Geryon dies only if he starts his turn with 0 hit points and doesn't regenerate.

***Spellcasting.*** Geryon casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 21):

**At will**: [alter self](2-Mechanics/CLI/spells/alter-self.md) (can become Medium when changing his appearance), [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [ice storm](2-Mechanics/CLI/spells/ice-storm.md), [invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only), [locate object](2-Mechanics/CLI/spells/locate-object.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md), [wall of ice](2-Mechanics/CLI/spells/wall-of-ice.md)

**1/day**: [banishment](2-Mechanics/CLI/spells/banishment.md)

## Actions

***Multiattack.*** Geryon makes one Claw attack and one Stinger attack.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 15 ft., one target. *Hit:* `dice:4d6+9|noform|avg|text(23)` (`4d6 + 9`) cold damage. If the target is Large or smaller, it is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) (DC 24), and it is [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained) until the grapple ends. Geryon can grapple one creature at a time. If the target is already [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Geryon, the target takes an extra `dice:6d8|noform|avg|text(27)` (`6d8`) cold damage.

***Stinger.*** *Melee Weapon Attack:* `dice:1d20+16|noform|text(+16)` to hit, reach 20 ft., one creature. *Hit:* `dice:2d4+9|noform|avg|text(14)` (`2d4 + 9`) force damage, and the target must succeed on a DC 21 Constitution saving throw or take `dice:2d12|noform|avg|text(13)` (`2d12`) poison damage and become [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) until it finishes a short or long rest. The target's hit point maximum is reduced by an amount equal to half the poison damage taken. This reduction lasts until the [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) condition is removed. The target dies if its hit point maximum is reduced to 0.

***Teleport.*** Geryon teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.

## Legendary Actions

***Infernal Glare.*** Geryon targets one creature he can see within 60 feet of him. The target must succeed on a DC 23 Wisdom saving throw or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of Geryon until the end of its next turn.

***Teleport.*** Geryon uses Teleport.

***Swift Sting (Costs 2 Actions).*** Geryon makes one Stinger attack.

![Geryon](2-Mechanics/CLI/bestiary/legendary-group/geryon-mpmm.md)
```
^statblock