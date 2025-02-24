---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/21
- monster/size/medium
- monster/type/undead
aliases: ["Rerak"]
---
# Rerak
*Source: Vecna: Eve of Ruin*  

```ad-statblock
title: Rerak
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Rerak.webp#token)
*Medium undead, typically  Neutral Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 199 (`21d8 + 105`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|20 (+5)|25 (+7)|19 (+4)|15 (+2)|

- **Proficiency Bonus** +7
- **Saving Throws** Constitution +12, Intelligence +14, Wisdom +11, Charisma +9
- **Skills** ⏤
- **Senses** truesight 60 ft., passive Perception 14
- **Damage Immunities** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** Abyssal, Common, Draconic, Dwarvish, Elvish, Giant, Infernal, Primordial, Undercommon
- **Challenge** 21

## Traits

***Legendary Resistance (3/Day).*** If Rerak fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** Rerak has advantage on saving throws against spells and magical effects.

***Spellcasting.*** Rerak casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 22):

**At will**: [Detect Magic](2-Mechanics/CLI/spells/detect-magic.md), [Fly](2-Mechanics/CLI/spells/fly.md), [Mage Hand](2-Mechanics/CLI/spells/mage-hand.md), [Prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md)

**1/day each**: [Globe of Invulnerability](2-Mechanics/CLI/spells/globe-of-invulnerability.md), [Hold Monster](2-Mechanics/CLI/spells/hold-monster.md)

**3/day each**: [Dispel Magic](2-Mechanics/CLI/spells/dispel-magic.md), [Invisibility](2-Mechanics/CLI/spells/invisibility.md) (self only)

## Actions

***Multiattack.*** Rerak makes two Death Rend attacks and uses Bloodcurdling Lament if available.

***Death Rend.*** *Melee Spell Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 5 ft., one target. *Hit:* `dice:3d10+7|noform|avg|text(23)` (`3d10 + 7`) necrotic damage.

***Bloodcurdling Lament (Recharge 5-6).*** Rerak emits a hideous shriek charged with malignant energy. Each creature within 30 feet of Rerak must succeed on a DC 22 Wisdom saving throw or have the [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) condition for 1 minute. While [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened) in this way, a creature also has the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition. An affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Bonus Actions

***Soul Siphon.*** Rerak targets one creature it can see within 120 feet of itself. The target must make a DC 22 Charisma saving throw; if the target has the [unconscious](2-Mechanics/CLI/rules/conditions.md#Unconscious) condition, it has disadvantage on this saving throw. The target takes `dice:6d6|noform|avg|text(21)` (`6d6`) force damage on a failed save or half as much damage on a successful one. Rerak then regains a number of hit points equal to the amount of force damage taken.

If this damage reduces the target to 0 hit points, the target immediately dies, its body disappears, and its soul is trapped inside one of the soul gems within Rerak's skull. After 24 hours, the gem transfers the soul to Rerak's creator.

When Rerak is reduced to 0 hit points, it is destroyed and disintegrates, leaving behind the gems. Crushing a gem releases any souls trapped within, at which point the soul's body re-forms in an unoccupied space nearest to the gem and in the same state as it was when its soul was trapped.

## Legendary Actions

***Spiteful Teleport.*** Rerak, along with anything it is wearing or carrying, teleports to an unoccupied space it can see within 60 feet of itself. It then makes one Death Rend attack if possible.

***Cast a Spell (Costs 2 Actions).*** Rerak uses Spellcasting.
```
^statblock