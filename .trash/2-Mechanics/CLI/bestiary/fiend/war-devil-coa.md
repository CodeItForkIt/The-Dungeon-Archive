---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/16
- monster/size/huge
- monster/type/fiend/devil
aliases: ["War Devil"]
---
# War Devil
*Source: Chains of Asmodeus p. 260*  

Created through the sacrifice of other devils, both alive and dead, war devils vary in size and shape, but not personality. They crave combat and are highly aggressive, often commanding legions of lesser devils in wars. While they greatly enjoy bullying weaker creatures and exerting their dominance, they're highly submissive towards more powerful creatures and higher ranked devils.

## Battle Commanders

War devils are also extremely loyal to their creators, following practically any order given to them. When not taking orders, war devils are clever enough to command and make decisions on their own, making them extremely talented generals.

## Mighty Devils

Because of their construction, the appearance of war devils varies. That said, there are a few features that are common among most of their kind. Almost all war devils have thick, leathery wings, as well as massive, curved horns and sharpened teeth. They're also usually massive in size, having been created from multiple other devils, with the larger ones usually having higher-ranked positions. Though they prefer to use polearms of all kinds, war devils are also fully capable unarmed.

## Statblock

```ad-statblock
title: War Devil
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/War%20Devil.webp#token)
*Huge fiend (devil), Lawful Evil*

- **Armor Class** 11 (natural armor)
- **Hit Points** 237 (`19d12 + 114`)
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)| 9 (-1)|23 (+6)| 7 (-2)|13 (+1)| 9 (-1)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +12, Constitution +11
- **Skills** Athletics +12, Insight +6, Intimidation +4, Perception +6
- **Senses** darkvision 120 ft., passive Perception 16
- **Damage Resistances** cold
- **Damage Immunities** fire; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Condition Immunities** [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Infernal, telepathy 120 ft.
- **Challenge** 16

## Traits

***Devil's Sight.*** Magical darkness doesn't impede the war devil's darkvision.

***Fear Aura.*** Any hostile creature that starts its turn within 20 feet of the war devil must succeed on a DC 18 Wisdom saving throw or have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of the creature's next turn. If a creature's saving throw is successful, the creature is immune to the war devil's Fear Aura for the next 24 hours. This ability doesn't function if the war devil is [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious).

***Magic Resistance.*** The war devil has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The war devil makes two attacks using its Cold- Iron Ranseur, Claws, or a combination of the two.

***Cold-Iron Ranseur.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:3d10+7|noform|avg|text(23)` (`3d10 + 7`) force damage plus `dice:4d6|noform|avg|text(14)` (`4d6`) cold damage.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:3d8+7|noform|avg|text(20)` (`3d8 + 7`) slashing damage. If the target is a Large or smaller creature, it has the [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 20). While a creature is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled), the war devil can't make Claws attacks.
```
^statblock