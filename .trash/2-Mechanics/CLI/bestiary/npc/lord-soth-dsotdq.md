---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/19
- monster/size/medium
- monster/type/undead/paladin
aliases: ["Lord Soth"]
---
# Lord Soth
*Source: Dragonlance: Shadow of the Dragon Queen p. 206, Vecna: Eve of Ruin*  

Lord Soth is the most powerful death knight on Krynn. Once a Solamnic Knight of the Order of the Rose, Soth was a paragon of virtue and justice who allowed his pride to lead him down an evil path. The gods gave Soth a chance at redemption, charging him with confronting the Kingpriest of Istar and averting the Cataclysm. However, he was undone by his pride, abandoned his quest, and allowed the Cataclysm to devastate Krynn. Soth perished during the Cataclysm but then rose from the ashes as an Undead horror. In his cursed castle, Dargaard Keep, Soth long ignored the ruined world, but the Dragon Queen's summons has called his evil forth once more.

In battle, Soth is a terror, wielding the last remnant of the Cataclysm's fires to devastating effect. He usually uses his spellcasting ability only as part of his legendary actions.

```ad-statblock
title: Lord Soth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Lord%20Soth.webp#token)
*Medium undead (paladin), Lawful Evil*

- **Armor Class** 18 ([plate](2-Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 228 (`24d8 + 120`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|11 (+0)|20 (+5)|12 (+1)|16 (+3)|20 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Wisdom +9, Charisma +11
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Infernal, Solamnic
- **Challenge** 19

## Traits

***Legendary Resistance (3/Day).*** If Soth fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Soth has advantage on saving throws against spells and other magical effects.

***Marshal Undead.*** Unless Soth is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), he and Undead creatures of his choice within 60 feet of him are immune to features that turn Undead.

***Unusual Nature.*** Soth doesn't require air, food, drink, or sleep.

***Spellcasting.*** Soth casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 19):

**At will**: [command](2-Mechanics/CLI/spells/command.md) (cast at 3rd level)

**1/day**: [banishment](2-Mechanics/CLI/spells/banishment.md) (cast at 6th level)

**2/day each**: [dispel magic](2-Mechanics/CLI/spells/dispel-magic.md), [hold person](2-Mechanics/CLI/spells/hold-person.md) (cast at 3rd level)

## Actions

***Multiattack.*** Soth makes three Forsaken Brand attacks.

***Forsaken Brand.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:1d8+6|noform|avg|text(10)` (`1d8 + 6`) bludgeoning damage plus `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage, and if the target is a creature, it can't regain hit points until the start of Soth's next turn.

***Cataclysmic Fire (1/Day).*** Soth hurls a magical ball of fire that explodes at a point he can see within 120 feet of himself. Each creature in a 20-foot-radius sphere centered on that point must make a DC 19 Dexterity saving throw. A creature takes `dice:10d6|noform|avg|text(35)` (`10d6`) fire damage and `dice:10d6|noform|avg|text(35)` (`10d6`) necrotic damage on a failed save, or half as much damage on a successful one.

Additionally, any Medium or smaller Humanoid killed by this damage, as well as every corpse of such a creature within the sphere, becomes a skeleton (see the Monster Manual) under Soth's control. The skeleton acts on Soth's initiative but immediately after his turn. Absent any other command, the skeleton tries to kill any non-Undead creature it encounters.

***Word of Death (1/Day).*** Soth points at a creature he can see within 60 feet of himself and magically commands it to die. The target must make a DC 19 Constitution saving throw, taking 100 necrotic damage on a failed save, or half as much damage on a successful one. If this damage reduces the target to 0 hit points, the target dies.

## Legendary Actions

***Implacable Maneuver.*** Soth moves up to his speed or commands a mount he is riding to move up to its speed. The movement from this action doesn't provoke opportunity attacks. If he or his mount moves within 5 feet of a creature during this movement, he can force the creature to make a DC 20 Strength saving throw. The creature is knocked [prone](2-Mechanics/CLI/rules/conditions.md#Prone) unless it succeeds on the saving throw.

***Strike (Costs 2 Actions).*** Soth makes one Forsaken Brand attack.

***Cast a Spell (Costs 3 Actions).*** Soth uses Spellcasting.
```
^statblock