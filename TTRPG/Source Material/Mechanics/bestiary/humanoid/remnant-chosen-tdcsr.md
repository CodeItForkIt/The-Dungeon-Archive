---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/12
- monster/size/medium
- monster/type/humanoid/any
statblock: inline
aliases: ["Remnant Chosen"]
---
# [Remnant Chosen](Mechanics\bestiary\humanoid/remnant-chosen-tdcsr.md)
*Source: Tal'Dorei Campaign Setting Reborn p. 251*  

## Remnants

The "Remnants" is a foul cult dedicated to seeing their lich leader, The Whispered One, ascend to godhood. Cultists believe that self-mutilation and transitory failings are requirements to pierce the veil and see the world for the lie it is—including accepting that the true hidden world already belongs to The Whispered One.

### Bitter Victory

The "Remnants" have both won and failed in their dire goal, as The Whispered One ascended but was banished beyond the Divine Gate. Yet they name him the Ascendant One, the Banished One, or—because all others gods are pretenders—simply the One, and prepare patiently for his final ascension.

## Remnant Chosen

All devotees of The Whispered One are zealous followers, spending hours in silent meditation hoping to hear their long-dead master whisper a commandment from beyond. However, only a rare few hear the spectral voice of The Whispered One as it worms its way into their minds, emptying out other thought and filling their heads with clarity and direction. Much of this direction involves the "Remnants'" plans to leverage secrets stolen from the Plane of Shadow to increase the cult's power in Tal'Dorei.

```statblock
"name": "Remnant Chosen (TDCSR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"stats":
- !!int "10"
- !!int "14"
- !!int "14"
- !!int "15"
- !!int "16"
- !!int "20"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "7"
"skillsaves":
  "Deception": !!int "9"
  "Arcana": !!int "10"
"damage_resistances": "damage from spells"
"damage_immunities": "necrotic"
"senses": "truesight 60 ft., passive Perception 13"
"languages": "Abyssal, Common, Infernal"
"cr": "12"
"traits":
- "desc": "The chosen is an 18th-level spellcaster. Its spellcasting ability is Charisma\
    \ (spell save DC 17, +9 to hit with spell attacks). It has the following sorcerer\
    \ spells prepared:\n\nCantrips (at will): [chill touch](Mechanics/spells/chill-touch.md)\
    \ (4d8), [dancing lights](Mechanics/spells/dancing-lights.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [message](Mechanics/spells/message.md), [shocking grasp](Mechanics/spells/shocking-grasp.md)\
    \ (4d8)\n\n1st level (4 slots): [charm person](Mechanics/spells/charm-person.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md), [shield](Mechanics/spells/shield.md)\n\
    \n2nd level (3 slots): [blindness/deafness](Mechanics/spells/blindness-deafness.md),\
    \ [detect thoughts](Mechanics/spells/detect-thoughts.md)\n\n3rd level (3 slots):\
    \ [counterspell](Mechanics/spells/counterspell.md), [fly](Mechanics/spells/fly.md),\
    \ [hypnotic pattern](Mechanics/spells/hypnotic-pattern.md)\n\n4th level (3 slots):\
    \ [greater invisibility](Mechanics/spells/greater-invisibility.md)\n\n5th level\
    \ (3 slots): [dominate person](Mechanics/spells/dominate-person.md), [seeming](Mechanics/spells/seeming.md)\n\
    \n6th level (1 slots): [eyebite](Mechanics/spells/eyebite.md)\n\n7th level\
    \ (1 slots): [finger of death](Mechanics/spells/finger-of-death.md)\n\n8th\
    \ level (1 slots): [power word stun](Mechanics/spells/power-word-stun.md)\n\n\
    9th level (1 slots): [power word kill](Mechanics/spells/power-word-kill.md)"
  "name": "Spellcasting"
- "desc": "The chosen has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "When the chosen casts a spell of 1st level or higher, the next Withered\
    \ Hand attack it makes before the end of its next turn deals extra damage equal\
    \ to 1d6 per level of the spell cast."
  "name": "Withering Spells"
"actions":
- "desc": "Melee Spell Attack: +9 to hit, reach 5 ft., one target. Hit: 17 (5d6)\
    \ force damage plus extra damage from the Withering Touch trait. If this damage\
    \ reduces a creature to 0 hit points, the creature and everything it is wearing\
    \ and carrying, except magic items, are reduced to a pile of fine gray dust. The\
    \ creature can be restored to life only by means of a [true resurrection](Mechanics/spells/true-resurrection.md)\
    \ or a [wish](Mechanics/spells/wish.md) spell."
  "name": "Withering Touch"
"bonus_actions":
- "desc": "The Chosen selects a creature or object under the effect of an illusion\
    \ spell of 4th level or lower. One illusion of the Chosen's choice affecting the\
    \ target is dispelled."
  "name": "Inescapable Sight"
"source":
- "TDCSR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Remnant%20Chosen.webp"
```
^statblock