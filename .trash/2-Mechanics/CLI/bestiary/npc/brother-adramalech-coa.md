---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/21
- monster/size/medium
- monster/type/fiend/devil
aliases: ["Brother Adramalech"]
---
# Brother Adramalech
*Source: Chains of Asmodeus p. 185*  

```ad-statblock
title: Brother Adramalech
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Brother%20Adramalech.webp#token)
*Medium fiend (devil), Lawful Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 212 (`25d8 + 100`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|16 (+3)|18 (+4)|25 (+7)|25 (+7)|25 (+7)|

- **Proficiency Bonus** +7
- **Saving Throws** Intelligence +14, Wisdom +14, Charisma +14
- **Skills** Arcana +14, Deception +21, Insight +14, Intimidation +14, Persuasion +21, Religion +14
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** fire, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
- **Challenge** 21

## Traits

***Devil's Sight.*** Magical darkness doesn't impede Adramalech's darkvision.

***Magic Resistance.*** Adramalech has advantage on saving throws against spells and other magical effects.

***Unbreakable Bond.*** If Adramalech is reduced to 0 hit points while Brother Morax still lives, Adramalech regenerates 50 hit points at the start of his next turn. This regeneration is interrupted if Brother Morax is reduced to 0 hit points before the start of Adramalech's turn.

## Actions

***Multiattack.*** Adramalech makes four attacks using Mental

***Barrage.*** He can replace one of the attacks with Brain Freeze or Cone of Madness (if available).

***Mental Barrage.*** *Melee or Ranged Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft. or range 60/120 ft., one target. *Hit:* `dice:4d8+7|noform|avg|text(25)` (`4d8 + 7`) psychic damage.

***Brain Freeze.*** Adramalech attempts to overload the brain of a creature he can see within 60 feet of him. The target must make a DC 22 Intelligence saving throw, taking `dice:4d10|noform|avg|text(22)` (`4d10`) psychic damage on a failed save, or half as much on a successful one. Creatures that fail the saving throw have the [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) condition for up to 1 minute. A [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned) creature may repeat the saving throw at the end of each of their turns, ending the effect on a success.

***Cone of Madness (Recharge 4-6).*** Adramalech unleashes visions in a 30-foot cone in front of him. All creatures in the cone must make a DC 22 Wisdom saving throw, taking `dice:5d6|noform|avg|text(17)` (`5d6`) psychic damage on a failed save, or half as much on a successful one. For up to 1 minute, creatures that failed the save can't take reactions and each turn must use their action to make a melee attack against the nearest creature. Creatures may repeat the saving throw at the end of each of their turns, ending the effect on a success.

## Bonus Actions

***Conjure Effigy (Recharge 6).*** Adramalech targets a creature, reading its thoughts and creating an effigy of a loved one in an unoccupied space that he can see within 60 feet of Adramalech. The effigy has `dice:10d10|noform|avg|text(55)` (`10d10`) hit points, an AC of 10, and ability scores of 10. It occasionally shouts for help, but otherwise takes no actions. While the effigy is alive, the target creature has disadvantage on attacks targeting Adramalech and any time the effigy takes damage, the target creature also takes an equal amount as psychic damage. If the effigy is killed, the target creature gains a level of [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion). If Adramalech is killed while effigies exist, they harmlessly melt into a warm sludge.

## Legendary Actions

***Barrage.*** Adramalech makes a Mental Barrage attack.

***Mental Blocker.*** Adramalech fortifies the mind of a creature he can see within 60 feet of him, or himself. The target benefits as if the [Greater Restoration](2-Mechanics/CLI/spells/greater-restoration.md) spell has been cast on them and is granted resistance to psychic damage until the end of Adramalech's next turn.
```
^statblock