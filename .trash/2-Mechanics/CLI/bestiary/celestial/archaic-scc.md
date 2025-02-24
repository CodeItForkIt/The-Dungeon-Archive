---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/18
- monster/size/gargantuan
- monster/type/celestial
aliases: ["Archaic"]
---
# Archaic
*Source: Strixhaven: A Curriculum of Chaos p. 184*  

Archaics are towering, multi-armed creatures overflowing with magic. Despite their solitude, archaics carry vast understanding of magic and the world's history, as well as the ability to warp the fabric of the world around them. Sages who seek out archaics for their knowledge receive confusing and often contradictory answers to questions. If a supplicant successfully unwinds the tangle, the answer they seek is revealed.

In truth, archaics are the reincarnated souls of the oracles of Strixhaven. When an oracle dies, their soul travels back through time to the explosion of magic that brought the Founder Dragons into being. In that outrush of creative force, the oracle's soul can be caught in the tide and clad in the very substance of the world, becoming an archaic. Because their knowledge cuts across the flow of time, archaics are careful how much they reveal to mortals and thus tend to speak in riddles.

```ad-statblock
title: Archaic
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/SCC/Archaic.webp#token)
*Gargantuan celestial, typically  Neutral*

- **Armor Class** 20 (natural armor)
- **Hit Points** 245 (`14d20 + 98`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|10 (+0)|24 (+7)|27 (+8)|24 (+7)|20 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Intelligence +14, Wisdom +13, Charisma +11
- **Skills** Arcana +20, Deception +11, History +20, Perception +13
- **Senses** truesight 120 ft., passive Perception 23
- **Damage Resistances** force
- **Damage Immunities** poison, psychic
- **Condition Immunities** [charmed](2-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](2-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](2-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](2-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](2-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](2-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](2-Mechanics/CLI/rules/conditions.md#Stunned)
- **Languages** all
- **Challenge** 18

## Traits

***Enigmatic Mind.*** The archaic's mind can't be read, creatures can communicate telepathically with the archaic only if it allows, and magic can't determine whether the archaic is lying.

***Legendary Resistance (3/Day).*** If the archaic fails a saving throw, it can choose to succeed instead.

***Unusual Nature.*** The archaic doesn't require air, food, drink, or sleep.

***Spellcasting.*** The archaic casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 22):

**At will**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [divination](2-Mechanics/CLI/spells/divination.md), [sending](2-Mechanics/CLI/spells/sending.md)

**1/day each**: [banishment](2-Mechanics/CLI/spells/banishment.md), [forcecage](2-Mechanics/CLI/spells/forcecage.md)

## Actions

***Multiattack.*** The archaic makes two Force Strike attacks. It can also use Gravity Shift, if available.

***Force Strike.*** *Melee or Ranged Spell Attack:* `dice:1d20+14|noform|text(+14)` to hit, reach 15 ft. or range 120 ft., one target. *Hit:* `dice:2d10+8|noform|avg|text(19)` (`2d10 + 8`) force damage, and the target is pulled up to 10 feet toward the archaic or pushed 10 feet away from it, as the archaic chooses.

***Gravity Shift (Recharge 5-6).*** The archaic reverses gravity for one creature it can see within 100 feet of itself. The creature must succeed on a DC 22 Wisdom saving throw or fall 100 feet upward. If the falling creature encounters a solid object (such as a ceiling) in this fall, it strikes the object just as it would during a downward fall. If the creature reaches the top of the area without striking anything, it hovers there until the start of the archaic's next turn, at which time gravity returns to normal and the creature falls.

***Teleport.*** The archaic teleports to an unoccupied space that it can see within 120 feet of itself.

## Reactions

***Spell Mimicry (1/Day).*** Immediately after a creature the archaic can see casts a spell of 5th level or lower, that creature must succeed on a DC 22 Charisma saving throw, or the archaic immediately casts the same spell at the same level (`dice:1d20+14|noform|text(+14)` to hit with spell attacks, spell save DC 22), requiring no material components and choosing the spell's targets.

## Legendary Actions

***Strike.*** The archaic makes one Force Strike attack.

***Teleport.*** The archaic uses Teleport.

***Unravel Magic (Costs 2 Actions).*** The archaic targets one creature it can see within 120 feet of itself. The target must succeed on a DC 22 Constitution saving throw or take `dice:10d6|noform|avg|text(35)` (`10d6`) force damage, and each spell of 5th level or lower on the target ends.
```
^statblock