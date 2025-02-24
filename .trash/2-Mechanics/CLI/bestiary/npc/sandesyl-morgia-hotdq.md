---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hotdq
- monster/cr/13
- monster/size/medium
- monster/type/undead/shapechanger
aliases: ["Sandesyl Morgia"]
---
# Sandesyl Morgia
*Source: Hoard of the Dragon Queen p. 81, Tyranny of Dragons p. 98*  

```ad-statblock
title: Sandesyl Morgia
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HotDQ/Sandesyl%20Morgia.webp#token)
*Medium undead (shapechanger), Lawful Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 144 (`17d8 + 68`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|18 (+4)|18 (+4)|17 (+3)|15 (+2)|18 (+4)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +9, Wisdom +7, Charisma +9
- **Skills** Perception +7, Stealth +9
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Languages** the languages it knew in life
- **Challenge** 13

## Traits

***Shapechanger.*** If Sandesyl isn't in sunlight or running water, it can use its action to polymorph into a Tiny bat or a Medium cloud of mist, or back into its true form.

While in bat form, Sandesyl can't speak, its walking speed is 5 feet, and it has a flying speed of 30 feet. Its statistics, other than its size and speed, are unchanged. Anything it is wearing transforms with it, but nothing it is carrying does. It reverts to its true form if it dies.

While in mist form, Sandesyl can't take any actions, speak, or manipulate objects. It is weightless, has a flying speed of 20 feet, can hover, and can enter a hostile creature's space and stop there. In addition, if air can pass through a space, the mist can do so without squeezing, and it can't pass through water. It has advantage on Strength, Dexterity, and Constitution saving throws, and it is immune to all nonmagical damage, except the damage it takes from sunlight.

***Legendary Resistance (3/Day).*** If Sandesyl fails a saving throw, it can choose to succeed instead.

***Misty Escape.*** When it drops to 0 hit points outside its resting place, Sandesyl transforms into a cloud of mist (as in the Shapechanger trait) instead of falling [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious), provided that it isn't in sunlight or running water. If it can't transform, it is destroyed.

While it has 0 hit points in mist form, it can't revert to its vampire form, and it must reach its resting place within 2 hours or be destroyed. Once in its resting place, it reverts to its vampire form. It is then [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until it regains at least 1 hit point. After spending 1 hour in its resting place with 0 hit points, it regains 1 hit point.

***Regeneration.*** Sandesyl regains 20 hit points at the start of its turn if it has at least 1 hit point and isn't in sunlight or running water. If Sandesyl takes radiant damage or damage from holy water, this trait doesn't function at the start of Sandesyl's next turn.

***Spider Climb.*** Sandesyl can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

***Vampire Weaknesses.*** Sandesyl has the following flaws:

*Forbiddance.* Sandesyl can't enter a residence without an invitation from one of the occupants.

*Harmed by Running Water.* Sandesyl takes 20 acid damage if it ends its turn in running water.

*Stake to the Heart.* If a piercing weapon made of wood is driven into Sandesyl's heart while Sandesyl is [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated) in its resting place, Sandesyl is [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed) until the stake is removed.

*Sunlight Hypersensitivity.* Sandesyl takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.

## Actions

***Multiattack (Vampire Form Only).*** Sandesyl makes two attacks, only one of which can be a bite attack.

***Unarmed Strike (Vampire Form Only).*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+4|noform|avg|text(8)` (`1d8 + 4`) bludgeoning damage. Instead of dealing damage, Sandesyl can grapple the target (escape DC 18).

***Bite (Bat or Vampire Form Only).*** *Melee Weapon Attack:* `dice:1d20+9|noform|text(+9)` to hit, reach 5 ft., one willing creature, or a creature that is [grappled](2-Mechanics/CLI/rules/conditions.md#Grappled) by Sandesyl, [incapacitated](2-Mechanics/CLI/rules/conditions.md#Incapacitated), or [restrained](2-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* `dice:1d6+4|noform|avg|text(7)` (`1d6 + 4`) piercing damage plus `dice:3d6|noform|avg|text(10)` (`3d6`) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and Sandesyl regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if this effect reduces its hit point maximum to 0. A humanoid slain in this way and then buried in the ground rises the following night as a [vampire spawn](2-Mechanics/CLI/bestiary/undead/vampire-spawn.md) under Sandesyl's control.

***Charm.*** Sandesyl targets one humanoid it can see within 30 feet of it. If the target can see Sandesyl, the target must succeed on a DC 17 Wisdom saving throw against this magic or be [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) by Sandesyl. The [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed) target regards Sandesyl as a trusted friend to be heeded and protected. Although the target isn't under Sandesyl's control, it takes Sandesyl's requests or actions in the most favorable way it can, and it is a willing target for Sandesyl's bite attack.

Each time Sandesyl or Sandesyl's companions do anything harmful to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until Sandesyl is destroyed, is on a different plane of existence than the target, or takes a bonus action to end the effect.

***Children of the Night (1/Day).*** Sandesyl magically calls `dice:2d4|noform|avg` (`2d4`) swarms of [bats](2-Mechanics/CLI/bestiary/beast/swarm-of-bats.md) or [rats](2-Mechanics/CLI/bestiary/beast/swarm-of-rats.md), provided that the sun isn't up. While outdoors, Sandesyl can call `dice:3d6|noform|avg` (`3d6`) [wolves](2-Mechanics/CLI/bestiary/beast/wolf.md) instead. The called creatures arrive in `dice:1d4|noform|avg` (`1d4`) rounds, acting as allies of Sandesyl and obeying its spoken commands. The beasts remain for 1 hour, until Sandesyl dies, or until Sandesyl dismisses them as a bonus action.

## Legendary Actions

***Move.*** Sandesyl moves up to its speed without provoking opportunity attacks.

***Unarmed Strike.*** Sandesyl makes one unarmed strike.

***Bite (Costs 2 Actions).*** Sandesyl makes one bite attack.
```
^statblock