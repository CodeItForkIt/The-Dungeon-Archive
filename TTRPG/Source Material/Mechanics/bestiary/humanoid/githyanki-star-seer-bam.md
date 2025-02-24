---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/gith
- monster/type/humanoid/warlock
statblock: inline
aliases: ["Githyanki Star Seer"]
---
# [Githyanki Star Seer](Mechanics\bestiary\humanoid/githyanki-star-seer-bam.md)
*Source: Boo's Astral Menagerie p. 27*  

Githyanki star seers believe that the stars are the eyes of the multiverse. They use their magic to contact ancient stellar entities such as Acamar, Caiphon, and Hadar, hoping to learn their secrets, then record these secrets in journals. They scour Wildspace in search of new entities as well, hoping to be the first to contact them.

Some of the secrets learned are so cryptic that they require years of research to decipher, but time is of little concern to a star seer, who resides mainly on the Astral Plane.

```statblock
"name": "Githyanki Star Seer (BAM)"
"size": "Medium"
"type": "humanoid"
"subtype": "gith, warlock"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"stats":
- !!int "11"
- !!int "11"
- !!int "14"
- !!int "19"
- !!int "16"
- !!int "14"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
  "Constitution": !!int "5"
"skillsaves":
  "History": !!int "10"
  "Arcana": !!int "10"
"damage_resistances": "radiant"
"senses": "passive Perception 13"
"languages": "Common, Gith"
"cr": "7"
"traits":
- "desc": "The githyanki casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\nAt\
    \ will: [light](Mechanics/spells/light.md), [mage hand](Mechanics/spells/mage-hand.md)\
    \ (the hand is invisible)\n\n1/day each: [contact other plane](Mechanics/spells/contact-other-plane.md)\
    \ (as an action), [plane shift](Mechanics/spells/plane-shift.md), [telekinesis](Mechanics/spells/telekinesis.md)\n\
    \n2/day each: [detect magic](Mechanics/spells/detect-magic.md), [invisibility](Mechanics/spells/invisibility.md)\
    \ (self only), [mage armor](Mechanics/spells/mage-armor.md) (self only), [tongues](Mechanics/spells/tongues.md)"
  "name": "Spellcasting (Psionics)"
"actions":
- "desc": "The githyanki makes three Astral Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 20 (3d10 + 4) radiant damage."
  "name": "Astral Bolt"
"bonus_actions":
- "desc": "The githyanki teleports, along with any equipment it is wearing or carrying,\
    \ up to 30 feet to an unoccupied space it can see."
  "name": "Astral Step (Recharge 4-6)"
"source":
- "BAM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Githyanki%20Star%20Seer.webp"
```
^statblock