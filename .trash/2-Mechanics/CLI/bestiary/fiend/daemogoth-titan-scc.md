---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/16
- monster/size/gargantuan
- monster/type/fiend
aliases: ["Daemogoth Titan"]
---
# Daemogoth Titan
*Source: Strixhaven: A Curriculum of Chaos p. 190*  

Daemogoth titans are towering monsters that blight the land around them. A daemogoth grows in power over the course of decades spent feeding on sorrow and draining life from nature. Eventually that growth turns the daemogoth into a titan.

The titans maintain their lesser cousins' ability to trade magical power for a mortal's pain, but they tend to demand more punishing suffering in exchange for their pacts or knowledge.

## Barbed Gifts

When a supplicant piques a daemogoth titan's interest, the titan can grant a blessing to the supplicant (see "Supernatural Gifts "in the Dungeon Master's Guide). As long as the creature has the blessing, it must expend and roll two of its Hit Dice whenever it finishes a long rest. It takes psychic damage equal to the total rolled, and its hit point maximum is reduced by an amount equal to the psychic damage taken. This reduction lasts until the creature finishes its next long rest. The creature dies if this effect reduces its hit point maximum to 0. The blessing can be removed only by a [wish](2-Mechanics/CLI/spells/wish.md) spell.

## Statblock

```ad-statblock
title: Daemogoth Titan
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Daemogoth%20Titan.webp#token)
*Gargantuan fiend, typically  Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 203 (`11d20 + 88`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|10 (+0)|26 (+8)|24 (+7)|18 (+4)|20 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Intelligence +12, Wisdom +9, Charisma +10
- **Skills** Arcana +17, Deception +15, History +12, Perception +9
- **Senses** truesight 120 ft., passive Perception 19
- **Damage Immunities** psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened)
- **Languages** Abyssal, Infernal, telepathy 120 ft.
- **Challenge** 16

## Traits

***Legendary Resistance (3/Day).*** If the titan fails a saving throw, it can choose to succeed instead.

***Pact of Suffering.*** Using a 10-minute long ritual, the titan can forge a magical bond with a willing creature it touches throughout the ritual. The creature becomes bound by the pact until it dies, the titan dies, or the pact is broken by a [wish](2-Mechanics/CLI/spells/wish.md) spell.

The titan chooses one spell from the necromancy or enchantment school that is 8th level or lower. The bound creature can cast that spell using this pact, requiring no material components and using Intelligence as the spellcasting ability. When it casts the spell, the creature takes `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage, which can't break the creature's [concentration](2-Mechanics/CLI/rules/conditions.md#Concentration) on a spell. Once the bound creature casts the spell in this way, it can't do so again until it finishes a long rest.

## Actions

***Multiattack.*** The titan makes two Agonizing Burst attacks.

***Agonizing Burst.*** *Melee or Ranged Spell Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 15 ft. or range 120 ft., one target. *Hit:* `dice:3d6+7|noform|avg|text(17)` (`3d6 + 7`) force damage. If the target is a creature, the titan regains 5 hit points.

***Teleport.*** The titan teleports to an unoccupied space it can see within 120 feet of itself.

## Legendary Actions

***Attack.*** The titan makes one Agonizing Burst attack.

***Stalking Nightmare (Costs 2 Actions).*** The titan uses Teleport, after which it can target one creature within 20 feet of itself that it can see. The target must make a DC 20 Constitution saving throw. On a failed save, the target takes `dice:4d10|noform|avg|text(22)` (`4d10`) necrotic damage, and the titan regains 10 hit points. On a successful save, the target takes half as much damage, and the titan doesn't heal.

***Terrorize (Costs 3 Actions).*** The titan targets one creature it can see within 120 feet of itself. The target must make a DC 20 Wisdom saving throw. On a failed save, the target takes `dice:7d10|noform|avg|text(38)` (`7d10`) psychic damage and is [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) of the titan until the end of the target's next turn, and the titan regains 15 hit points. On a successful save, the target takes half as much damage and isn't [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), and the titan doesn't heal.
```
^statblock