---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pabtso
- monster/cr/2
- monster/size/small
- monster/type/aberration/goblinoid
aliases: ["Goblin Psi Brawler"]
---
# Goblin Psi Brawler
*Source: Phandelver and Below: The Shattered Obelisk p. 215*  

Goblin psi brawlers use their psionic talents to heighten their physical might. Their strikes crackle with psychic energy, and while angered, goblin psi brawlers can unleash a telekinetic thrust strong enough to knock enemies to the ground.

## Psionic Goblins

The specifics of how a psionic goblin comes to exist vary. Some are born, changed by energy leaking from the Far Realm. Others transform themselves with their psionic power or enter into agreements with other Aberrations, which help them transform in return for their service as shock troops. Regardless, the result is the same: a goblin with unnatural and barely contained psychic power.

Psionic goblins often struggle to handle the turbulent psychic energy within their minds and bodies. Those psionic goblins who learn how to safely tap into this psychic power are formidable forces in combat. Psionic goblins often augment their martial skills with telekinesis, and stealthy squads of psionic goblin warriors can communicate via telepathy, making them excellent infiltrators and ambushers.

## Statblock

```ad-statblock
title: Goblin Psi Brawler
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Goblin%20Psi%20Brawler.webp#token)
*Small aberration (goblinoid), Any alignment*

- **Armor Class** 15 ([studded leather armor](2-Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 31 (`7d6 + 7`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|17 (+3)|12 (+1)|16 (+3)|15 (+2)|10 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Intelligence +5, Wisdom +4
- **Skills** Stealth +7
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Resistances** psychic
- **Languages** Common, Goblin, telepathy 30 ft.
- **Challenge** 2

## Traits

***Mental Burst.*** When the goblin dies, its pent-up mental energy explodes in a psychic blast. Each creature within 5 feet of it must succeed on a DC 13 Intelligence saving throw or take `dice:2d4|noform|avg|text(5)` (`2d4`) psychic damage.

***Mental Fortitude.*** The goblin has advantage on saving throws against effects that would make it have the [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition.

## Actions

***Multiattack.*** The goblin makes two Unarmed Strike attacks.

***Unarmed Strike.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) bludgeoning damage plus `dice:1d6|noform|avg|text(3)` (`1d6`) psychic damage.

## Bonus Actions

***Nimble Escape.*** The goblin takes the Disengage or Hide action.

***Telekinetic Shove.*** The goblin targets one creature it can see within 30 feet of itself with a thrust of telekinetic force. The target must succeed on a DC 13 Strength saving throw or have the [prone](2-Mechanics/CLI/rules/conditions.md#Prone) condition.
```
^statblock