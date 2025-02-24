---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psa
- monster/cr/3
- monster/size/medium
- monster/type/undead
aliases: ["Amonkhet Mummy"]
---
# Amonkhet Mummy
*Source: Plane Shift: Amonkhet p. 34*  

Not every citizen of Naktamun proves to be worthy of the afterlife. Acolytes sometimes die before the Ceremony of Measurement, perhaps in training accidents. Many [initiates](2-Mechanics/CLI/backgrounds/initiate-psa.md) perish in one of the first four trials, before earning their five cartouches. [Viziers](2-Mechanics/CLI/backgrounds/vizier-psa.md) sometimes die before they have truly earned a place in the afterlife serving their gods. Without having proven themselves worthy, these poor souls have no place as Eternals in the afterlife—but neither have they committed a grievous sin that would warrant abandoning them to the Curse of Wandering as marauding [mummies](2-Mechanics/CLI/bestiary/undead/amonkhet-mummy-psa.md).

Fortunately, the beneficence of the God-Pharaoh is great enough to provide a role for these people. Called the anointed, they are carefully embalmed, protected from the Curse of Wandering, and allowed to spend another lifetime in service to the worthy. The God-Pharaoh promises that those who faithfully serve as the anointed will earn a place as attendants in the afterlife as well, and even an eternity of service in the afterlife is prefera-ble to an eternity subjected to the Curse of Wandering.

The bodies of the anointed are carefully wrapped in cloth and adorned with cartouches. In contrast to the cartouches of [initiates](2-Mechanics/CLI/backgrounds/initiate-psa.md) and [viziers](2-Mechanics/CLI/backgrounds/vizier-psa.md), these do not harbor the life essence of the deceased at their best. Instead, they coach the anointed for a particular form of service. With their cartouches in place, the anointed rise and join the ranks of serving [mummies](2-Mechanics/CLI/bestiary/undead/amonkhet-mummy-psa.md) who attend to the needs of daily life in Amonkhet.

## The Curse of Wandering

The Curse of Wandering is the greatest danger of the desert lands. A creature killed in the desert rises again as a [zombie](2-Mechanics/CLI/bestiary/undead/zombie.md) as soon as the moisture has dried from its flesh. As a result, the corpses of every kind of desert creature shamble across the dunes alongside the humanoid [zombies](2-Mechanics/CLI/bestiary/undead/zombie.md) of dissenters and would-be explorers. Most of these former humanoids are mindless marauders, though some tales speak of [mummies](2-Mechanics/CLI/bestiary/undead/amonkhet-mummy-psa.md) that have retained a sinister intelligence and even magical ability, becoming [mummy lords](2-Mechanics/CLI/bestiary/undead/amonkhet-mummy-lord-psa.md).

## Statblock

```ad-statblock
title: Amonkhet Mummy
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSA/Amonkhet%20Mummy.webp#token)
*Medium undead, Lawful Evil*

- **Armor Class** 11 (natural armor)
- **Hit Points** 58 (`9d8 + 18`)
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 8 (-1)|15 (+2)| 6 (-2)|10 (+0)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +2
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 3

## Actions

***Multiattack.*** The mummy can use its Dreadful Glare and makes one attack with its rotting fist.

***Rotting Fist.*** *Melee Weapon Attack:* `dice:1d20+5|noform|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+3|noform|avg|text(10)` (`2d6 + 3`) bludgeoning damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. If the target is a creature, it must succeed on a DC 12 Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by `dice:3d6|noform|avg|text(10)` (`3d6`) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies, and its body turns to dust. The curse lasts until removed by the [remove curse](2-Mechanics/CLI/spells/remove-curse.md) spell or other magic.

***Dreadful Glare.*** The mummy targets one creature it can see within 60 feet of it. If the target can see the mummy, it must succeed on a DC 11 Wisdom saving throw against this magic or become [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) until the end of the mummy's next turn. If the target fails the saving throw by 5 or more, it is also [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) for the same duration. A target that succeeds on the saving throw is immune to the Dreadful Glare of all mummies (but not mummy lords) for the next 24 hours.
```
^statblock