---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/pota
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Flamewrath"]
---
# [Flamewrath](Mechanics\bestiary\humanoid/flamewrath-pota.md)
*Source: Princes of the Apocalypse p. 201*  

A flamewrath is a spellcaster that has earned the favor of Imix, the Prince of Elemental Fire, through a series of painful rites. A flamewrath's skin is burned and scarred. Inured to pain, the flamewrath revels in battle, using an array of fire spells to incinerate enemies who would try to douse the power of elemental fire. Melee combatants who draw too close face fires that can dance across the flamewrath's skin and burn attackers.

```statblock
"name": "Flamewrath (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"stats":
- !!int "10"
- !!int "14"
- !!int "16"
- !!int "11"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Religion": !!int "3"
  "Arcana": !!int "3"
"damage_immunities": "fire"
"senses": "passive Perception 10"
"languages": "Common, Ignan"
"cr": "6"
"traits":
- "desc": "The flamewrath is a 7th-level spellcaster. Its spellcasting ability is\
    \ Charisma (spell save DC 14, +6 to hit with spell attacks). It knows the following\
    \ sorcerer spells:\n\nCantrips (at will): [control flames](Mechanics/spells/control-flames-xge.md),\
    \ [fire bolt](Mechanics/spells/fire-bolt.md), [friends](Mechanics/spells/friends.md),\
    \ [light](Mechanics/spells/light.md), [minor illusion](Mechanics/spells/minor-illusion.md)\n\
    \n1st level (4 slots): [burning hands](Mechanics/spells/burning-hands.md),\
    \ [color spray](Mechanics/spells/color-spray.md), [mage armor](Mechanics/spells/mage-armor.md)\n\
    \n2nd level (3 slots): [scorching ray](Mechanics/spells/scorching-ray.md),\
    \ [suggestion](Mechanics/spells/suggestion.md)\n\n3rd level (3 slots): [fireball](Mechanics/spells/fireball.md),\
    \ [hypnotic pattern](Mechanics/spells/hypnotic-pattern.md)\n\n4th level (1 slots):\
    \ [fire shield](Mechanics/spells/fire-shield.md) (see Wreathed in Flame)"
  "name": "Spellcasting"
- "desc": "For the flamewrath, the warm version of the [fire shield](Mechanics/spells/fire-shield.md)\
    \ spell has a duration of \"until dispelled.\" The fire shield burns for 10 minutes\
    \ after the flamewrath dies, consuming its body."
  "name": "Wreathed in Flame"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "PotA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PotA/Flamewrath.webp"
```
^statblock