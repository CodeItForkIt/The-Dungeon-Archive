---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/any
statblock: inline
aliases: ["Remnant Cultist"]
---
# [Remnant Cultist](Mechanics\bestiary\humanoid/remnant-cultist-tdcsr.md)
*Source: Tal'Dorei Campaign Setting Reborn p. 252*  

## Remnants

The "Remnants" is a foul cult dedicated to seeing their lich leader, The Whispered One, ascend to godhood. Cultists believe that self-mutilation and transitory failings are requirements to pierce the veil and see the world for the lie it is—including accepting that the true hidden world already belongs to The Whispered One.

### Bitter Victory

The "Remnants" have both won and failed in their dire goal, as The Whispered One ascended but was banished beyond the Divine Gate. Yet they name him the Ascendant One, the Banished One, or—because all others gods are pretenders—simply the One, and prepare patiently for his final ascension.

## Remnant Cultist

All cultists of The Whispered One endure horrific rites of initiation that force them to remove one of their own eyes and forever shackle themselves to the will of the cult's leaders. Every cultist can feel the presence of their foul god just beyond the fabric of the physical world, and many claim to hear him speaking to them when all else is silent.

The cultists of The Whispered One still venerate their wrathful master with offerings of secrets and unwilling souls to gain his favor, learning what they can and keeping hidden that which they know. Cultists believe in cultivating evil in themselves and recognizing it in others, encouraging them to express it. They hope to seed the ruin of all who worship other deities until only those who kneel before The Whispered One remain.

```statblock
"name": "Remnant Cultist (TDCSR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "60"
"hit_dice": "11d8 + 11"
"stats":
- !!int "10"
- !!int "16"
- !!int "12"
- !!int "18"
- !!int "8"
- !!int "8"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
"skillsaves":
  "Deception": !!int "5"
  "Stealth": !!int "6"
"damage_resistances": "necrotic, psychic"
"senses": "passive Perception 9"
"languages": "Common, Infernal"
"cr": "7"
"traits":
- "desc": "The remnant cultist is an 11th-level spellcaster. Its spellcasting ability\
    \ is Intelligence (spell save DC 15, +7 to hit with spell attacks). The cultist\
    \ has the following wizard spells prepared:\n\nCantrips (at will): [chill\
    \ touch](Mechanics/spells/chill-touch.md) (3d8), [message](Mechanics/spells/message.md),\
    \ [minor illusion](Mechanics/spells/minor-illusion.md), [prestidigitation](Mechanics/spells/prestidigitation.md),\
    \ [ray of frost](Mechanics/spells/ray-of-frost.md) (3d8)\n\n1st level (4 slots):\
    \ [detect magic](Mechanics/spells/detect-magic.md), [Tasha's hideous laughter](Mechanics/spells/tashas-hideous-laughter.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md), [shield](Mechanics/spells/shield.md)\n\
    \n2nd level (3 slots): [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [suggestion](Mechanics/spells/suggestion.md)\n\n3rd level (3 slots): [counterspell](Mechanics/spells/counterspell.md),\
    \ [fear](Mechanics/spells/fear.md), [vampiric touch](Mechanics/spells/vampiric-touch.md)\n\
    \n4th level (3 slots): [greater invisibility](Mechanics/spells/greater-invisibility.md),\
    \ [phantasmal killer](Mechanics/spells/phantasmal-killer.md)\n\n5th level (2\
    \ slots): [dream](Mechanics/spells/dream.md), [mislead](Mechanics/spells/mislead.md)\n\
    \n6th level (1 slots): [circle of death](Mechanics/spells/circle-of-death.md)"
  "name": "Spellcasting"
- "desc": "Any attempt to form a mental link with the cultist, cast [scrying](Mechanics/spells/scrying.md)\
    \ on the cultist, or cast [speak with dead](Mechanics/spells/speak-with-dead.md)\
    \ on the cultist automatically fails, and the creature that initiated the attempt\
    \ takes 21 (6d6) psychic damage."
  "name": "Unknowable Secrets"
- "desc": "The cultist has disadvantage on any attack roll made against a target more\
    \ than 30 feet away."
  "name": "One-Eyed"
- "desc": "If the cultist successfully uses [counterspell](Mechanics/spells/counterspell.md)\
    \ to negate another creature's spell, it can cast the countered spell once before\
    \ the end of its next turn using one of its spell slots of the same level or higher,\
    \ and requiring no material components."
  "name": "Spellsteal"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft., range 20/60\
    \ ft., one target. Hit: 5 (1d4 + 3) piercing damage. Hit points lost to [this\
    \ weapon's](Mechanics/items/sword-of-wounding.md) damage can be regained only\
    \ through a short or long rest, rather than by regeneration, magic, or any other\
    \ means.\n\nOnce per turn when the cultist hits a creature with an attack using\
    \ this weapon, it can wound its target. At the start of each of the wounded creature's\
    \ turns, it takes 2 (1d4) necrotic damage for each time it's been wounded by\
    \ this weapon. It can then make a DC 15 Constitution saving throw, ending the\
    \ effect of all such wounds on itself on a success. Alternatively, the wounded\
    \ creature, or a creature within 5 feet of it, can use an action to make a DC\
    \ 15 Wisdom ([Medicine](Mechanics/Rules/skills.md#Medicine)) check, ending the\
    \ effect of such wounds on it on a success."
  "name": "Dagger of Wounding"
"source":
- "TDCSR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Remnant%20Cultist.webp"
```
^statblock