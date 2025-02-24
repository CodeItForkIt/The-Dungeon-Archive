---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/12
- monster/environment/any
- monster/size/large
- monster/type/undead
aliases: ["Flutterflesh"]
---
# Flutterflesh
*Source: Tome of Beasts 1 (2023 Edition) p. 189*  

*This mass of fused corpses resembles a butterfly with wings of skin, limbs of bone, and a head formed of several different skulls. The dark magic that formed this abomination swirls around it hungrily.*

## Bound by Necromancy

Flutterfleshes are created in terrible necromantic rituals. Cultists gather in the name of a dark god, powerful lich, or crazed madman, and forever bind themselves body and soul into a single evil being. Flutterfleshes take recently severed limbs and fuse these new pieces to themselves in accordance with some unknowable aesthetic.

## Dilemma of Flesh

The most horrifying thing about a flutterflesh, however, is its devious nature. A flutterflesh offers its prey the choice to either die or lose a limb. If it accepts the limb, the flutterflesh then leaves the victim alone. One can always tell where a flutterflesh resides because so many of the locals are missing appendages.

## Statblock

```ad-statblock
title: Flutterflesh
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Flutterflesh.webp#token)
*Large undead, Chaotic Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 187 (`22d10 + 66`)
- **Speed** 10 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|18 (+4)|17 (+3)|12 (+1)|16 (+3)|10 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +4, Wisdom +7
- **Skills** Deception +4, Perception +7, Stealth +8
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Vulnerabilities** radiant
- **Damage Resistances** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** Common, Darakhul
- **Challenge** 12

## Traits

***Merciful Exchange.*** If the flutterflesh reduces a creature to 0 hp with a melee attack, it can cut off one of the creature's limbs. If it does so, the target is reduced to 1 hp instead.

***Necrotic Weapons.*** The flutterflesh's weapon attacks are magical. When the flutterflesh hits with any weapon, the weapon deals an extra `dice:2d8|noform|avg` (`2d8`) necrotic damage (included in the attack).

***Regeneration.*** The flutterflesh regains 10 hp at the start of its turn. If the flutterflesh takes fire or radiant damage, this trait doesn't function at the start of the flutterflesh's next turn. The flutterflesh dies only if it starts its turn with 0 hp and doesn't regenerate.

***Turn Resistance.*** The flutterflesh has advantage on saving throws against any effect that turns undead.

***Undead Nature.*** The flutterflesh doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The flutterflesh makes three Bone Spur or Tormenting Gaze attacks. If two Tormenting Gaze attacks hit one creature, the target must succeed on a DC 16 Wisdom saving throw or be [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for 1 minute. A [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Bone Spur.*** *Melee Weapon Attack:* `dice:1d20+8|noform|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:2d12+4|noform|avg|text(17)` (`2d12 + 4`) piercing damage plus `dice:2d8|noform|avg|text(9)` (`2d8`) necrotic damage, and the flutterflesh impales the target on one of its bone spurs, grappling the target (escape DC 16). The flutterflesh can have no more than two creatures impaled at a time.

***Tormenting Gaze.*** *Ranged Spell Attack:* `dice:1d20+7|noform|text(+7)` to hit, range 120 ft., one creature. *Hit:* `dice:4d8+3|noform|avg|text(21)` (`4d8 + 3`) psychic damage.

***Creeping Death (Recharge 5-6).*** The flutterflesh emits a wave of necromantic energy, hastening the journey toward death. Each creature within 20 feet of the flutterflesh must make a DC 16 Constitution saving throw, taking `dice:10d8|noform|avg|text(45)` (`10d8`) necrotic damage on a failed save, or half as much damage on a successful one. A creature below half its hp maximum has disadvantage on this saving throw.
```
^statblock

## Environment

any