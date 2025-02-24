---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/aitfr-thp
- monster/cr/5
- monster/size/medium
- monster/type/aberration/shapeshifter
aliases: ["Usagt"]
---
# Usagt
*Source: Adventures in the Forgotten Realms: The Hidden Page p. 14*  

These peculiar creatures originate on a tranquil, lawful plane where they lead gentle, languid existences. They enjoy the experiences of life—in memory and in practice—but have curiously few ambitions. Their natural lifespan is centuries long, and they give little thought to the passage of time.

Some scholars of the planes believe usagt are not organisms in any traditional sense but a kind of intelligent being made of notions and psychic matter.

## Curiously Shy

An usagt's true form is amorphous and [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible). They change shape based on the thoughts and memories they observe in other creatures' memories. Each usagt thus has a peculiar sense of itself and its peers, based on what shapes it can take in what order, rather than any visual cues of its own.

## Cunning Observers

The favorite pastime of most usagt is putting on little improvised plays with others of its kind, changing shapes throughout. Usagt observe other creatures and detect their thoughts to broaden the catalog of characters they can portray.

## Strange Nature

Usagt do not reproduce. An usagt requires no food, drink, or sleep, but enjoys them when it can. It does require air.

## Statblock

```ad-statblock
title: Usagt
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AitFR-THP/Usagt.webp#token)
*Medium aberration (shapeshifter), Lawful Neutral*

- **Armor Class** 12
- **Hit Points** 97 (`13d8 + 39`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|16 (+3)|15 (+2)|20 (+5)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +5, Wisdom +8, Charisma +4
- **Skills** History +5, Insight +8, Perception +8, Performance +7, Stealth +5
- **Senses** darkvision 100 ft., passive Perception 18
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** all, telepathy 30 ft.
- **Challenge** 5

## Traits

***Invisibility.*** The usagt's true form is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible).

***Shapechanger.*** The usagt can use its action to polymorph into a Small, Medium, or Large humanoid it has seen in person or telepathically, or back into its true form. Its statistics, other than its size, are the same in each form. While polymorphed, the usagt is not [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible). Its new form appears to wear clothes, carry equipment, and even wield weapons, but these are all parts of the usagt itself; they vanish if dropped or removed from the creature. It can't activate, use, wield, or otherwise benefit from any of its apparent equipment. It reverts to its true form if it dies.

***Innate Spellcasting.*** The usagt's innate spellcasting ability is Charisma (spell save DC 15). It can cast the following spells, requiring no spell components:

**At will**: [banishment](2-Mechanics/CLI/spells/banishment.md), [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [disguise self](2-Mechanics/CLI/spells/disguise-self.md)

## Actions

***Multiattack.*** The usagt makes two attacks with its claws.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) slashing damage plus 11 (2d6 + 4) psychic damage.

***Personal Insight.*** The usagt targets one creature it can see within 30 feet of it. The target must contest its Charisma ([Deception](2-Mechanics/CLI/rules/skills.md#Deception)) check against the usagt's Wisdom ([Insight](2-Mechanics/CLI/rules/skills.md#Insight)) check.

The target has advantage on the roll if it is immune to being [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed). A target can choose to fail this check.

If the usagt wins, it magically learns the identity of a creature from the target's past, someone the target wishes it could speak to again or with whom the target has left something unsaid. If somehow no such creature exists in the target's past, the usagt learns that instead.

## Reactions

***Invisibility Response (Recharges When the Usagt Uses Its Shapechanger Ability).*** When the usagt takes damage, it can choose to revert to its default, [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) form and move up to 15 feet without provoking opportunity attacks.
```
^statblock