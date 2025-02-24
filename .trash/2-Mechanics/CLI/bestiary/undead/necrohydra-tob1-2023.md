---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/9
- monster/environment/any
- monster/size/huge
- monster/type/undead
aliases: ["Necrohydra"]
---
# Necrohydra
*Source: Tome of Beasts 1 (2023 Edition) p. 283*  

*Five snaking necks sprout from this decayed, draconic body. However, instead of reptilian heads, each neck ends in a humanoid head.*

Necrohydras are created by powerful, evil necromancers and often used as guardians or placed at the vanguard of an undead army to strike fear and despair into the enemy. The wordless, heart-wrenching dirge the creature produces can drain all hope from listeners. The necrohydra can speak, though the few words it croaks out are usually only in response to questions by its master.

## Familiar Heads

Sometimes a necrohydra is created as an instrument of revenge or a tool to further damage the morale of a necromancer's enemies. In these instances, the necromancer uses the heads of humanoids that are familiar to those that will face the necrohydra—heroes, beloved leaders or officers, loved ones, or close allies. A necromancer may coach the necrohydra to say certain mocking phrases to strike at the hearts of the necromancer's enemies.

## Statblock

```ad-statblock
title: Necrohydra
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Necrohydra.webp#token)
*Huge undead, Neutral Evil*

- **Armor Class** 13 (natural armor)
- **Hit Points** 207 (`18d12 + 90`)
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)| 6 (-2)|20 (+5)| 3 (-4)|10 (+0)| 7 (-2)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +4
- **Skills** Perception +8
- **Senses** darkvision 60 ft., passive Perception 18
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages its heads knew in life
- **Challenge** 9

## Traits

***Multiple Heads.*** The necrohydra has five fleshy heads. While it has more than one head, the necrohydra has advantage on saving throws against being [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](2-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned), and knocked [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious). Whenever the necrohydra takes 25 or more damage in a single turn, one of its fleshy heads dies. If all its fleshy heads die, the necrohydra can't use or maintain Dreadful Dirge. At the end of its turn, it grows two skeletal heads for each of its fleshy heads that died since its last turn, unless it has taken radiant damage since its last turn. The necrohydra regains 10 hp for each skeletal head regrown in this way.

***Reactive Heads.*** For each head the necrohydra has beyond one, it gets an extra reaction that can be used only for opportunity attacks.

***Undead Nature.*** The necrohydra doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The necrohydra makes as many Bite attacks as it has heads.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:1d4+5|noform|avg|text(7)` (`1d4 + 5`) piercing damage plus `dice:1d8|noform|avg|text(4)` (`1d8`) necrotic damage.

***Dreadful Dirge.*** The necrohydra's heads emit a cacophonous, moaning wail. Each creature that isn't a Construct or Undead within 30 feet of the necrohydra that can hear the wail must succeed on a DC 17 Wisdom saving throw or be [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the wail ends. The necrohydra must take a bonus action on its subsequent turns to continue wailing. It can stop wailing at any time. The wail ends if the necrohydra is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated). A [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Necrotic Bile (Recharge 6).*** The necrohydra spews rotten bile soaked in necrotic energy in a 30-foot cone. Each creature in that area must make a DC 17 Dexterity saving throw, taking `dice:6d6|noform|avg|text(21)` (`6d6`) poison damage and `dice:4d8|noform|avg|text(18)` (`4d8`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock

## Environment

any