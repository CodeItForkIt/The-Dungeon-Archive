---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/any
aliases: ["Remnant Cultist"]
---
# Remnant Cultist
*Source: Tal'Dorei Campaign Setting Reborn p. 252*  

## Remnants

The "Remnants" is a foul cult dedicated to seeing their lich leader, The Whispered One, ascend to godhood. Cultists believe that self-mutilation and transitory failings are requirements to pierce the veil and see the world for the lie it is—including accepting that the true hidden world already belongs to The Whispered One.

### Bitter Victory

The "Remnants" have both won and failed in their dire goal, as The Whispered One ascended but was banished beyond the Divine Gate. Yet they name him the Ascendant One, the Banished One, or—because all others gods are pretenders—simply the One, and prepare patiently for his final ascension.

## Remnant Cultist

All cultists of The Whispered One endure horrific rites of initiation that force them to remove one of their own eyes and forever shackle themselves to the will of the cult's leaders. Every cultist can feel the presence of their foul god just beyond the fabric of the physical world, and many claim to hear him speaking to them when all else is silent.

The cultists of The Whispered One still venerate their wrathful master with offerings of secrets and unwilling souls to gain his favor, learning what they can and keeping hidden that which they know. Cultists believe in cultivating evil in themselves and recognizing it in others, encouraging them to express it. They hope to seed the ruin of all who worship other deities until only those who kneel before The Whispered One remain.

## Statblock

```ad-statblock
title: Remnant Cultist
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Remnant%20Cultist.webp#token)
*Medium humanoid (any), Unaligned*

- **Armor Class** 13
- **Hit Points** 60 (`11d8 + 11`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|12 (+1)|18 (+4)| 8 (-1)| 8 (-1)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +2
- **Skills** Deception +5, Stealth +6
- **Senses** passive Perception 9
- **Damage Resistances** necrotic, psychic
- **Languages** Common, Infernal
- **Challenge** 7

## Traits

***Unknowable Secrets.*** Any attempt to form a mental link with the cultist, cast [scrying](2-Mechanics/CLI/spells/scrying.md) on the cultist, or cast [speak with dead](2-Mechanics/CLI/spells/speak-with-dead.md) on the cultist automatically fails, and the creature that initiated the attempt takes `dice:6d6|noform|avg|text(21)` (`6d6`) psychic damage.

***One-Eyed.*** The cultist has disadvantage on any attack roll made against a target more than 30 feet away.

***Spellsteal.*** If the cultist successfully uses [counterspell](2-Mechanics/CLI/spells/counterspell.md) to negate another creature's spell, it can cast the countered spell once before the end of its next turn using one of its spell slots of the same level or higher, and requiring no material components.

***Spellcasting.*** The remnant cultist is an 11th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 15, `dice:1d20+7|noform|text(+7)` to hit with spell attacks). The cultist has the following wizard spells prepared:

**Cantrips (at will)**: [chill touch](2-Mechanics/CLI/spells/chill-touch.md) (`dice:3d8|noform|avg` (`3d8`)), [message](2-Mechanics/CLI/spells/message.md), [minor illusion](2-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](2-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](2-Mechanics/CLI/spells/ray-of-frost.md) (`dice:3d8|noform|avg` (`3d8`))

**1st level (4 slots)**: [detect magic](2-Mechanics/CLI/spells/detect-magic.md), [Tasha's hideous laughter](2-Mechanics/CLI/spells/tashas-hideous-laughter.md), [mage armor](2-Mechanics/CLI/spells/mage-armor.md), [shield](2-Mechanics/CLI/spells/shield.md)

**2nd level (3 slots)**: [detect thoughts](2-Mechanics/CLI/spells/detect-thoughts.md), [suggestion](2-Mechanics/CLI/spells/suggestion.md)

**3rd level (3 slots)**: [counterspell](2-Mechanics/CLI/spells/counterspell.md), [fear](2-Mechanics/CLI/spells/fear.md), [vampiric touch](2-Mechanics/CLI/spells/vampiric-touch.md)

**4th level (3 slots)**: [greater invisibility](2-Mechanics/CLI/spells/greater-invisibility.md), [phantasmal killer](2-Mechanics/CLI/spells/phantasmal-killer.md)

**5th level (2 slots)**: [dream](2-Mechanics/CLI/spells/dream.md), [mislead](2-Mechanics/CLI/spells/mislead.md)

**6th level (1 slots)**: [circle of death](2-Mechanics/CLI/spells/circle-of-death.md)

## Actions

***Dagger of Wounding.*** *Melee or Ranged Weapon Attack:* `dice:1d20+6|noform|text(+6)` to hit, reach 5 ft., range 20/60 ft., one target. *Hit:* `dice:1d4+3|noform|avg|text(5)` (`1d4 + 3`) piercing damage. Hit points lost to [this weapon's](2-Mechanics/CLI/items/sword-of-wounding.md) damage can be regained only through a short or long rest, rather than by regeneration, magic, or any other means.

Once per turn when the cultist hits a creature with an attack using this weapon, it can wound its target. At the start of each of the wounded creature's turns, it takes `dice:1d4|noform|avg|text(2)` (`1d4`) necrotic damage for each time it's been wounded by this weapon. It can then make a DC 15 Constitution saving throw, ending the effect of all such wounds on itself on a success. Alternatively, the wounded creature, or a creature within 5 feet of it, can use an action to make a DC 15 Wisdom ([Medicine](2-Mechanics/CLI/rules/skills.md#Medicine)) check, ending the effect of such wounds on it on a success.
```
^statblock