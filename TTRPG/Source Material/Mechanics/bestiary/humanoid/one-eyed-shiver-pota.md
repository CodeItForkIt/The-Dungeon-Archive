---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pota
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["One-Eyed Shiver"]
---
# [One-Eyed Shiver](Mechanics\bestiary\humanoid/one-eyed-shiver-pota.md)
*Source: Princes of the Apocalypse p. 207*  

A one-eyed shiver is a fearsome cultist who wields powers of ice and cold. To gain the frigid power of elemental water, the shiver removes one eye and replaces it with a frosty white orb that can blast foes with an icy ray. When the orb isn't in use, the shiver covers its magical eye with an eye patch. Even when hidden, the orb's magical power makes itself felt-a one-eyed shiver has ice-cold blood and is constantly surrounded by an aura of thin, cold fog.

One-eyed shivers inspire dread and fear in all who meet them, including their fellow cultists. Only the leaders of the Crushing Wave cult dare to give commands to these masters of icy magic.

```statblock
"name": "One-Eyed Shiver (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "49"
"hit_dice": "9d8 + 9"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "13"
- !!int "13"
- !!int "17"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "5"
  "Perception": !!int "3"
  "Arcana": !!int "3"
"damage_immunities": "cold"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "3"
"traits":
- "desc": "The one-eyed shiver is a 5th-level spellcaster. Its spellcasting ability\
    \ is Charisma (spell save DC 13, +5 to hit with spell attacks). It knows the\
    \ following sorcerer spells:\n\nCantrips (at will): [chill touch](Mechanics/spells/chill-touch.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md)\n\n1st level (4 slots): [fog\
    \ cloud](Mechanics/spells/fog-cloud.md), [mage armor](Mechanics/spells/mage-armor.md),\
    \ [thunderwave](Mechanics/spells/thunderwave.md)\n\n2nd level (3 slots): [mirror\
    \ image](Mechanics/spells/mirror-image.md), [misty step](Mechanics/spells/misty-step.md)\n\
    \n3rd level (2 slots): [fear](Mechanics/spells/fear.md)"
  "name": "Spellcasting"
- "desc": "While it is alive, the one-eyed shiver projects an aura of cold mist within\
    \ 10 feet of itself. If the one-eyed shiver deals damage to a creature in this\
    \ area, the creature also takes 5 (1d10) cold damage."
  "name": "Chilling Mist"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one\
    \ target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "The one-eyed shiver casts [ray of frost](Mechanics/spells/ray-of-frost.md)\
    \ from its missing eye. If it hits, the target is also [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ A target [restrained](Mechanics/Rules/conditions.md#Restrained) in this way\
    \ can end the condition by using an action, succeeding on a DC 13 Strength check."
  "name": "Eye of Frost"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PotA/One-Eyed%20Shiver.webp"
```
^statblock