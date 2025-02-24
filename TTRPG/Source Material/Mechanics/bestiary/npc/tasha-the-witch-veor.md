---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/19
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/wizard
statblock: inline
aliases: ["Tasha the Witch"]
---
# [Tasha the Witch](Mechanics\bestiary\npc/tasha-the-witch-veor.md)
*Source: Vecna: Eve of Ruin p. 252*  

Tasha's path to greatness began when she was adopted by the arch-hag Baba Yaga, who named her Natasha. Tasha went on to create various spells, including Tasha's Hideous Laughter, and her magic-fueled ambitions brought her into contact with demons and demon lords, which she subjugated and used against her enemies. On the Material Plane, she became known as Iggwilv the Witch Queen and wrote the Demonomicon of Iggwilv, the greatest of all treatises on the Abyss and its demonic inhabitants. In recent years, Tasha sequestered herself in the Feywild, achieving incredible power and slowly turning into a Fey creature. Tasha became Zybilna, archfey of the domain of Prismeer.

## Answering the Summons

When Zybilna received Alustriel Silverhand's summons to combat Vecna, the archfey was sorely needed in Prismeer. As a compromise, and to honor Tasha's friendship with Alustriel, Zybilna sent a version of herself from the past to Alustriel's side. The Tasha who appears in*Vecna: Eve of Ruin*is a powerful wizard, though she is not yet a witch queen or an archfey.

```statblock
"name": "Tasha the Witch (VEoR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Chaotic Neutral"
"ac": !!int "19"
"ac_class": "[robe of the archmagi](Mechanics/items/robe-of-the-archmagi.md)"
"hp": !!int "210"
"hit_dice": "28d8 + 84"
"stats":
- !!int "10"
- !!int "18"
- !!int "17"
- !!int "23"
- !!int "12"
- !!int "22"
"speed": "30 ft."
"saves":
  "Charisma": !!int "12"
  "Wisdom": !!int "7"
  "Intelligence": !!int "12"
"skillsaves":
  "History": !!int "12"
  "Arcana": !!int "18"
  "Persuasion": !!int "12"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "passive Perception 11"
"languages": "Abyssal, Celestial, Common, Draconic, Elvish, Infernal, Sylvan"
"cr": "19"
"traits":
- "desc": "Tasha casts one of the following spells, using Intelligence as the spellcasting\
    \ ability (spell save DC 22, +14 to hit with spell attacks):\n\nAt will:\
    \ [Detect Magic](Mechanics/spells/detect-magic.md), [Disguise Self](Mechanics/spells/disguise-self.md),\
    \ [Dispel Magic](Mechanics/spells/dispel-magic.md), [Light](Mechanics/spells/light.md),\
    \ [Mage Hand](Mechanics/spells/mage-hand.md), [Message](Mechanics/spells/message.md),\
    \ [Prestidigitation](Mechanics/spells/prestidigitation.md), [Tasha's Hideous Laughter](Mechanics/spells/tashas-hideous-laughter.md)\n\
    \n1/day each: [Maze](Mechanics/spells/maze.md), [Telekinesis](Mechanics/spells/telekinesis.md)\n\
    \n2/day: [Polymorph](Mechanics/spells/polymorph.md)"
  "name": "Spellcasting"
- "desc": "If Tasha fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Tasha has advantage on saving throws against spells and other magical effects.\
    \ (This trait is bestowed by her Robe of the Archmagi.)"
  "name": "Magic Resistance"
- "desc": "Tasha wears a Robe of the Archmagi."
  "name": "Special Equipment"
"actions":
- "desc": "Tasha makes two Caustic Blast attacks and uses Psychic Whip once."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +14 to hit, reach 5 ft. or range 120\
    \ ft., one target. Hit: 21 (6d4 + 6) acid damage."
  "name": "Caustic Blast"
- "desc": "Tasha psychically lashes out at one creature she can see within 90 feet\
    \ of herself. The target must make a DC 20 Intelligence saving throw. On a failed\
    \ save, the target takes 21 (6d6) psychic damage and has the [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ condition until the start of Tasha's next turn. On a successful save, the target\
    \ takes half as much damage only."
  "name": "Psychic Whip"
"bonus_actions":
- "desc": "For 1 minute, Tasha gains a flying speed of 30 feet, is immune to poison\
    \ damage and the [poisoned](Mechanics/Rules/conditions.md#Poisoned) condition,\
    \ and has advantage on attack rolls against any creature that doesn't have all\
    \ its hit points. These benefits end early if Tasha has the [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ condition or if she uses another bonus action to dismiss them."
  "name": "Abyssal Visage (2/Day)"
"reactions":
- "desc": "Immediately after Tasha takes damage, she unleashes arcane energy in a\
    \ 10-foot-radius sphere centered on herself. All other creatures in that area\
    \ must make a DC 20 Dexterity saving throw, taking 19 (3d12) lightning damage\
    \ on a failed save or half as much damage on a successful one. Tasha then teleports,\
    \ along with any equipment she is wearing or carrying, to an unoccupied space\
    \ she can see within 60 feet of herself."
  "name": "Arcane Rebuff"
"source":
- "VEoR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Tasha%20the%20Witch.webp"
```
^statblock