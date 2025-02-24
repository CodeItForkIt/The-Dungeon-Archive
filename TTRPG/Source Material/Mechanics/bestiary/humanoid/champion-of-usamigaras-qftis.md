---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/2
- monster/size/medium
- monster/type/humanoid
statblock: inline
aliases: ["Champion of Usamigaras"]
---
# [Champion of Usamigaras](Mechanics\bestiary\humanoid/champion-of-usamigaras-qftis.md)
*Source: Quests from the Infinite Staircase p. 206*  

Champions are blessed by Usamigaras to advance the faction by any means necessary. They boast a greater repertoire of spells than their fellows and can radiate an aura of illusions to confuse their foes.

## Mages of Usamigaras

The Mages of Usamigaras are Cynidicean spellcasters who worship Usamigaras, a god of magic, messengers, and lies. They hide their identities and intentions behind silver masks depicting the face of their god. Secrecy is key among the Mages of Usamigaras. Members whisper in the presence of outsiders and pepper their speech with lies, even obvious ones. Such behavior isn't rude among members, who view deceit as worthy of celebration, not chastisement.

```statblock
"name": "Champion of Usamigaras (QftIS)"
"size": "Medium"
"type": "humanoid"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "17"
- !!int "14"
- !!int "15"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Intelligence": !!int "5"
"skillsaves":
  "Sleight of Hand": !!int "4"
  "Deception": !!int "6"
  "Arcana": !!int "5"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "The champion casts one of the following spells, using Intelligence as the\
    \ spellcasting ability (spell save DC 13):\n\nAt will: [Light](Mechanics/spells/light.md),\
    \ [Mage Armor](Mechanics/spells/mage-armor.md) (self only), [Mage Hand](Mechanics/spells/mage-hand.md),\
    \ [Minor Illusion](Mechanics/spells/minor-illusion.md)\n\n1/day each: [Crown\
    \ of Madness](Mechanics/spells/crown-of-madness.md), [Shatter](Mechanics/spells/shatter.md)\n\
    \n2/day each: [Charm Person](Mechanics/spells/charm-person.md), [Disguise\
    \ Self](Mechanics/spells/disguise-self.md), [Silent Image](Mechanics/spells/silent-image.md)"
  "name": "Spellcasting"
"actions":
- "desc": "The champion makes two Arcane Burst attacks or makes one Arcane Burst attack\
    \ and uses Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 8 (1d10 + 3) force damage."
  "name": "Arcane Burst"
"bonus_actions":
- "desc": "The champion emits an aura of ghostly illusions that fills a 10-foot-radius\
    \ sphere centered on itself. While this aura is active, creatures have disadvantage\
    \ on attack rolls against the champion and any of the champion's allies that are\
    \ in the aura. The aura moves with the champion and lasts for 1 minute, until\
    \ the champion has the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition, or until the champion uses another bonus action to end the aura."
  "name": "Aura of Deception (1/Day)"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Champion%20of%20Usamigaras.webp"
```
^statblock