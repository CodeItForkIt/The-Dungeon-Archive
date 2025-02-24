---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/21
- monster/size/gargantuan
- monster/type/construct
aliases: ["Master Adranach"]
---
# Master Adranach
*Source: Tal'Dorei Campaign Setting Reborn p. 245*  

An adranach is a winged feline construct made of raw arcane energy, fuchsia in hue and flecked with stars. It is an iconic servitor of the "League of Miracles", and the exact method of their creation is a closely guarded secret known only to the "Wonderworker" who guides that organization and the spellwrights who serve them.

## Perfect Obedience

As constructs, adranachs are unfailingly loyal servants to the spellwrights who created them. To the people of Tal'Dorei, they are best known as the creatures that allowed cities razed by the "Chroma Conclave" to be rebuilt in a matter of weeks, rather than years. But adranachs are also mighty combatants that serve their masters as hunters, bodyguards, and even assassins.

## Astral Body

An adranach's body is formed from the energy of the Astral Plane. Their claws and face, as well as a number of rune-inscribed braces on their body, are made of mithral and are necessary to keep their form of pure energy from losing cohesion. The methods for creating these mithral foundations and for binding astral energy to them are known only to the "Wonderworker" (the leader of the "League of Miracles") and the spellwrights who learn from them.

This secret knowledge is granted to worthy spellwrights in the form of an orb of mithral bands, about three feet in diameter, called a dormen. As the bands are removed and forged into the adranach's braces and mask, the dormen speaks aloud the instructions of how to craft an adranach in the magically recorded voice of the "Wonderworker".

## Mithral Mask

Each adranach has a unique mask crafted by its creator as their signature. This mask is crafted from pure mithral, and is the key to summoning and dismissing an adranach to a unique pocket dimension where it can rest and repair itself. When not in use, the mask magically shrinks from its true size to an easily concealable size fit for a humanoid face. Most spellwrights keep this mask in a chest stored on the Ethereal Plane with the [secret chest](2-Mechanics/CLI/spells/leomunds-secret-chest.md) spell, and only produce the mask when it is time to call their adranach forth.

## Master Adranach

The secretive master spellwrights of the "League of Miracles" are taught how to build adranachs of monumental size, with strength to match. These legendary constructs are also inevitably outfitted with unique enhancements of their creators' own devising, from upgraded espionage tools to the ability to sublimate their starry form and travel through the Astral Plane.

## Arcane Nature

An adranach doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Master Adranach
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Master%20Adranach.webp#token)
*Gargantuan construct, Unaligned*

- **Armor Class** 19 (natural armor)
- **Hit Points** 290 (`20d20 + 80`)
- **Speed** 60 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|16 (+3)|19 (+4)|10 (+0)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +7
- **Saving Throws** Strength +14, Dexterity +10, Wisdom +9
- **Skills** Athletics +14, Perception +16
- **Senses** darkvision 360 ft., passive Perception 26
- **Damage Resistances** damage from spells
- **Damage Immunities** poison; bludgeoning, piercing, slashing from non-magical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** the languages spoken by its creator
- **Challenge** 21

## Traits

***Arcane Leak.*** When the adranach is reduced to half its hit point maximum (145 hit points), its mithral mask cracks and its arcane form begins to waver, creating a field of unstable magic around it. Any creature that starts its turn within 20 feet of the adranach or enters that area for the first time on a turn takes `dice:6d6|noform|avg|text(21)` (`6d6`) radiant damage. Additionally, if a creature casts a spell within this area, it must make a DC 18 ability check using its spellcasting ability. On a failure, the spell backfires, consuming the spell slot and dealing `dice:2d6|noform|avg|text(7)` (`2d6`) force damage to the caster for each level of the spell slot that was consumed.

***Immutable Form.*** The adranach is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The adranach has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The adranach's weapon attacks are magical.

***Colossal Build.*** The adranach's carrying capacity is doubled, as is the weight it can push, drag, or lift.

***Slipstream.*** The adranach can cast [invisibility](2-Mechanics/CLI/spells/invisibility.md) on itself at will. While it is [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible), its speed is doubled.

***Legendary Resistance (3/Day).*** If the adranach fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The adranach makes three attacks: two with its claws and one with its tail.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, one target, reach 5 ft. *Hit:* `dice:4d12+7|noform|avg|text(33)` (`4d12 + 7`) slashing damage.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+14|noform|text(+14)` to hit, one target, reach 15 ft. *Hit:* `dice:2d12+7|noform|avg|text(20)` (`2d12 + 7`) bludgeoning damage.

***Force Bolts (Recharge 5-6).*** The adranach targets up to six creatures it can see within 120 feet of it. Each target must succeed on a DC 22 Dexterity saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) force damage.

## Legendary Actions

***Claw Attack.*** The adranach makes one claw attack.

***Vanish (Costs 2 Actions).*** The adranach casts [invisibility](2-Mechanics/CLI/spells/invisibility.md) and moves up to its walking or flying speed. (This movement doesn't benefit from its Slipstream trait.)

***Starry Burst (Costs 3 Actions).*** A burst of astral energy flares from the adranach's body. Each creature within 60 feet of it must make a DC 22 Constitution saving throw. On a failed save, a creature takes `dice:5d10|noform|avg|text(27)` (`5d10`) force damage and is [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded) until the end of its next turn. On a successful save, the creature takes half as much damage and is not [blinded](2-Mechanics/CLI/rules/conditions.md#Blinded). The adranach then turns [invisible](2-Mechanics/CLI/rules/conditions.md#Invisible) until the start of its next turn or until it makes an attack.
```
^statblock