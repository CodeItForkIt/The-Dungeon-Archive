---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/12
- monster/size/huge
- monster/type/construct
aliases: ["Adranach"]
---
# Adranach
*Source: Tal'Dorei Campaign Setting Reborn p. 224*  

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
title: Adranach
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Adranach.webp#token)
*Huge construct, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 170 (`20d12 + 40`)
- **Speed** 40 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|16 (+3)|14 (+2)| 8 (-1)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +11, Dexterity +8
- **Skills** Athletics +11, Perception +7
- **Senses** darkvision 120 ft., passive Perception 17
- **Damage Resistances** damage from spells
- **Damage Immunities** poison; bludgeoning, piercing, slashing from non-magical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands the languages spoken by its creator but can't speak
- **Challenge** 12

## Traits

***Arcane Leak.*** When the adranach is reduced to half its hit point maximum (85 hit points), its mithral mask cracks and its arcane form begins to waver, creating a field of unstable magic around it. Any creature that starts its turn within 10 feet of the adranach or enters that area for the first time on a turn takes `dice:3d6|noform|avg|text(10)` (`3d6`) radiant damage. Additionally, if a creature casts a spell within this area, it must make a DC 14 ability check using its spellcasting ability. On a failure, the spell backfires, consuming the spell slot and dealing `dice:1d6|noform|avg|text(3)` (`1d6`) force damage to the caster for each level of the spell slot that was consumed.

***Immutable Form.*** The adranach is immune to any spell or effect that would alter its form.

***Magic Resistance.*** The adranach has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The adranach's weapon attacks are magical.

***Powerful Build.*** The adranach counts as one size larger when determining its carrying capacity and the weight it can push, drag, or lift.

## Actions

***Multiattack.*** The adranach makes two attacks with its claws.

***Claws.*** *Melee Weapon Attack:* `dice:1d20+11|noform|text(+11)` to hit, one target, reach 5 ft. *Hit:* `dice:4d12+6|noform|avg|text(32)` (`4d12 + 6`) slashing damage.

***Force Bolts (Recharge 5-6).*** The adranach targets up to four creatures it can see within 60 feet of it. Each target must succeed on a DC 18 Dexterity saving throw or take `dice:8d6|noform|avg|text(28)` (`8d6`) force damage.
```
^statblock