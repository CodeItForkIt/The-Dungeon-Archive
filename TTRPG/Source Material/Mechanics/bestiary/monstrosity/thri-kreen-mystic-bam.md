---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/5
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Thri-kreen Mystic"]
---
# [Thri-kreen Mystic](Mechanics\bestiary\monstrosity/thri-kreen-mystic-bam.md)
*Source: Boo's Astral Menagerie p. 61, Light of Xaryxis*  

Thri-kreen mystics use psionics to navigate difficult terrain in Wildspace, turn invisible, and drain life from their prey. They often serve as spelljammers aboard thri-kreen ships.

```statblock
"name": "Thri-kreen Mystic (BAM)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "99"
"hit_dice": "18d8 + 18"
"stats":
- !!int "12"
- !!int "15"
- !!int "13"
- !!int "12"
- !!int "16"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "6"
  "Survival": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "telepathy 60 ft., Thri-kreen"
"cr": "5"
"traits":
- "desc": "The thri-kreen casts one of the following spells, requiring no spell components\
    \ and using Wisdom as the spellcasting ability:\n\nAt will: [levitate](Mechanics/spells/levitate.md)\
    \ (self only), [mage hand](Mechanics/spells/mage-hand.md) (the hand is invisible)\n\
    \n1/day each: [freedom of movement](Mechanics/spells/freedom-of-movement.md)\
    \ (self only), [invisibility](Mechanics/spells/invisibility.md) (self only)"
  "name": "Spellcasting (Psionics)"
"actions":
- "desc": "The thri-kreen makes two Gythka attacks or four Psychic Bolt attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d8 + 1) slashing damage."
  "name": "Gythka"
- "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one creature. Hit:\
    \ 6 (1d6 + 3) psychic damage."
  "name": "Psychic Bolt"
- "desc": "The thri-kreen targets one creature it can see within 30 feet of itself.\
    \ The target must make a DC 14 Constitution saving throw, taking 32 (5d12) necrotic\
    \ damage on a failed save, or half as much damage on a successful one. The thri-kreen\
    \ regains hit points equal to the damage dealt."
  "name": "Drain Vitality (Recharges after a Short or Long Rest)"
"bonus_actions":
- "desc": "The thri-kreen changes the color of its carapace to match the color and\
    \ texture of its surroundings, gaining advantage on Dexterity ([Stealth](Mechanics/Rules/skills.md#Stealth))\
    \ checks it makes to hide in those surroundings."
  "name": "Chameleon Carapace"
"source":
- "BAM"
- "LoX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Thri-kreen%20Mystic.webp"
```
^statblock