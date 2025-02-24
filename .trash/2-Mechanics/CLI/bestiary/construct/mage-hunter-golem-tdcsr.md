---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/15
- monster/size/large
- monster/type/construct
aliases: ["Mage Hunter Golem"]
---
# Mage Hunter Golem
*Source: Tal'Dorei Campaign Setting Reborn p. 242*  

Ageless and unstoppable guardians, golems are expertly crafted to execute their owners' every command without question. Vaguely humanoid in appearance and unfailingly loyal, these powerful constructs feel no agony or sympathy, require no sustenance or sleep, ignore bribes and bargains, and do as they are told without remorse or hesitation.

## Covetous Origins

During the "Age of Arcanum", magic inspired a deep arrogance in many of the gods' children, who assumed arcane gifts were proof of inevitable divinity. In response, many mortal folk experimented with manufacturing "life" of their own. The "dwarves" succeeded first, marrying divine gifts with technical skill to animate autonomous wardens as protectors of their ancestral halls. The "dwarves'" knowledge was quickly stolen and expanded upon by other folk, and creating golems eventually became less about proving that mortals can shape life as the gods do, and more about protecting life, wealth, and secrets from others.

## Mage Hunter Golem

The gods cursed mortals with free will, but also blessed them with the means to survive the Primordials' wrath—the arts of magic. With magic, the people of Exandria fend off droughts, famines, volcanic flame, slashing ice, and angry earth. But knowing that the power of magic might inevitably tear Exandria apart, the gods also created the ultimate magical failsafe—antimagic.

### Hunter of Magic

For many heroes who employ magic, the most terrifying nightmare is facing a hulking creature whose mere presence can strip away the power of spells and magic relics alike. Mage hunter golems are brutally efficient in their tactics, sweeping the battlefield with their disruptive antimagic, devouring spells used against them, and fitting collars to spellcasters that can leave them at the golem's mercy.

## Statblock

```ad-statblock
title: Mage Hunter Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Mage%20Hunter%20Golem.webp#token)
*Large construct, Unaligned*

- **Armor Class** 20 (natural armor)
- **Hit Points** 243 (`18d10 + 144`)
- **Speed** 30 ft., fly 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)| 9 (-1)|26 (+8)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +5
- **Saving Throws** Wisdom +5, Charisma +0
- **Skills** Perception +5
- **Senses** darkvision 120 ft., truesight 30 ft., passive Perception 15
- **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical weapons that aren't adamantine
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 15

## Traits

***Antimagic Cone.*** The golem creates an area of antimagic, as in the [antimagic field](2-Mechanics/CLI/spells/antimagic-field.md) spell, in a 60-foot cone originating from it. At the start of each of its turns, the golem decides which way the cone faces and whether the cone is active.

***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.

***Magic Absorption.*** Whenever the golem is subjected to a damage-dealing spell of 4th level or lower, it takes no damage and instead regains a number of hit points equal to the damage dealt.

***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The golem's weapon attacks are magical.

## Actions

***Multiattack.*** The golem uses its Antimagic Jolt and makes two melee attacks, or it makes three melee attacks.

***Slam.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) bludgeoning damage.

***Claw (Recharge 5-6).*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+7|noform|avg|text(11)` (`1d8 + 7`) bludgeoning damage, and the target must succeed on a DC 16 Dexterity saving throw or have a magic collar placed upon its neck. While the target wears the collar, it is magically prevented from speaking and cannot cast any spell. A successful DC 25 Dexterity check using [thieves' tools](2-Mechanics/CLI/items/thieves-tools.md) removes the collar.

***Antimagic Jolt.*** Each creature within the golem's Antimagic Cone that has the ability to cast a spell of 1st level or higher must make a DC 18 Wisdom saving throw, taking `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage on a failed save, or half as much damage on a successful one.
```
^statblock