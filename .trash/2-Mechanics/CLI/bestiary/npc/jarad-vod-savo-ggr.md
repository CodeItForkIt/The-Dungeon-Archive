---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/22
- monster/size/medium
- monster/type/undead
aliases: ["Jarad Vod Savo"]
---
# Jarad Vod Savo
*Source: Guildmasters' Guide to Ravnica p. 235*  

The Golgari guildmaster is a Devkarin necromancer and lich named Jarad Vod Savo. In life, Jarad was an archer and accomplished hunter, as well as the brother of the previous guildmaster, the ambitious Savra. Jarad mastered the ways of necromancy so he could rise as a lich after he sacrificed himself to save his son from the demon Rakdos.

As head of the Golgari Swarm, Jarad commands elf and medusa assassins, legions of kraul, brutish trolls, and masses of undercity-dwelling creatures. Thanks to the necromantic power he wields-and with the support of his loyal guards and soldiers-he has survived a number of assassination attempts from various upstarts.

## Undead Nature

Jarad doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Jarad Vod Savo
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Jarad%20Vod%20Savo.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 180 (`24d8 + 72`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|16 (+3)|16 (+3)|20 (+5)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +7
- **Saving Throws** Constitution +10, Intelligence +12, Wisdom +10
- **Skills** Arcana +12, Insight +10, Perception +10
- **Senses** darkvision 120 ft., passive Perception 20
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Common, Elvish, Kraul
- **Challenge** 22

## Traits

***Legendary Resistance (3/Day).*** If Jarad fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Jarad has advantage on saving throws against spells and other magical effects.

***Regeneration.*** Jarad regains 25 hit points at the start of his turn. If he takes fire or radiant damage, this trait doesn't function at the start of his next turn. He dies only if he starts its turn with 0 hit points and doesn't regenerate.

***Spore Infusion.*** Jarad is surrounded by a cloud of spores. As a bonus action, he can cause the spores to deal `dice:2d10|noform|avg|text(11)` (`2d10`) poison damage to a creature he can see within 10 feet of him.

***Turn Resistance.*** Jarad has advantage on saving throws against any effect that turns undead.

***Undead Fortitude.*** If damage reduces Jarad to 0 hit points, he must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, he drops to 1 hit point instead.

***Spellcasting.*** Jarad is a 14th-level Golgari spellcaster. His spellcasting ability is Intelligence (spell save DC 20, `dice:1d20+12|noform|text(+12)` to hit with spell attacks). Jarad has the following wizard spells prepared:

**Cantrips (at will)**: [acid splash](2-Mechanics/CLI/spells/acid-splash.md), [chill touch](2-Mechanics/CLI/spells/chill-touch.md), [mage hand](2-Mechanics/CLI/spells/mage-hand.md), [poison spray](2-Mechanics/CLI/spells/poison-spray.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1st level (4 slots)**: [entangle](2-Mechanics/CLI/spells/entangle.md), [ray of sickness](2-Mechanics/CLI/spells/ray-of-sickness.md), [sleep](2-Mechanics/CLI/spells/sleep.md)

**2nd level (3 slots)**: [Melf's acid arrow](2-Mechanics/CLI/spells/melfs-acid-arrow.md), [ray of enfeeblement](2-Mechanics/CLI/spells/ray-of-enfeeblement.md), [spider climb](2-Mechanics/CLI/spells/spider-climb.md), [web](2-Mechanics/CLI/spells/web.md)

**3rd level (3 slots)**: [animate dead](2-Mechanics/CLI/spells/animate-dead.md), [plant growth](2-Mechanics/CLI/spells/plant-growth.md), [vampiric touch](2-Mechanics/CLI/spells/vampiric-touch.md)

**4th level (3 slots)**: [blight](2-Mechanics/CLI/spells/blight.md), [giant insect](2-Mechanics/CLI/spells/giant-insect.md), [grasping vine](2-Mechanics/CLI/spells/grasping-vine.md)

**5th level (2 slots)**: [cloudkill](2-Mechanics/CLI/spells/cloudkill.md), [insect plague](2-Mechanics/CLI/spells/insect-plague.md)

**6th level (1 slots)**: [circle of death](2-Mechanics/CLI/spells/circle-of-death.md), [create undead](2-Mechanics/CLI/spells/create-undead.md)

**7th level (1 slots)**: [finger of death](2-Mechanics/CLI/spells/finger-of-death.md), [forcecage](2-Mechanics/CLI/spells/forcecage.md)

## Actions

***Multiattack.*** Jarad makes two attacks: one with his Noxious Touch and one with his Staff of Svogthir. He can cast a spell with a casting time of 1 action in place of one of these attacks.

***Noxious Touch.*** *Melee Spell Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one creature. *Hit:* `dice:8d6|noform|avg|text(28)` (`8d6`) poison damage, and the target must succeed on a DC 20 Constitution saving throw or be [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Staff of Svogthir.*** *Melee Weapon Attack:* `dice:1d20+12|noform|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:2d6+5|noform|avg|text(12)` (`2d6 + 5`) bludgeoning damage plus `dice:3d8|noform|avg|text(13)` (`3d8`) poison damage and `dice:3d8|noform|avg|text(13)` (`3d8`) necrotic damage.

## Legendary Actions

***Cantrip.*** Jarad casts one of his cantrips.

***Noxious Touch (Costs 2 Actions).*** Jarad uses Noxious Touch.

***Disrupt Life (Costs 3 Actions).*** Each creature within 30 feet of Jarad must make a DC 20 Constitution saving throw, taking `dice:10d6|noform|avg|text(35)` (`10d6`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock