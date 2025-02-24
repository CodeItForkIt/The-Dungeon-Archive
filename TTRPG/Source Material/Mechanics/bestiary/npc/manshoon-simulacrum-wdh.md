---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdh
- monster/cr/8
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Manshoon Simulacrum"]
---
# [Manshoon Simulacrum](Mechanics\bestiary\npc/manshoon-simulacrum-wdh.md)
*Source: Waterdeep: Dragon Heist p. 208*  

Manshoon uses the [simulacrum](Mechanics/spells/simulacrum.md) spell to create a magical duplicate of himself as needed. He has customized the spell to increase his simulacrum's hit points at the expense of its spellcasting ability.

Manshoon can have only one simulacrum at any given time, and he uses it as a subordinate to command his Zhentarim minions in the field. If his simulacrum is destroyed, Manshoon creates another. Each simulacrum has the statistics of Manshoon, with these changes:

- The simulacrum has no special equipment. Consequently, it has AC 12 and lacks the Magic Resistance trait and the Staff of Power action option.  
- It loses all spell slots of 6th level and higher.  
- It has a challenge rating of 8 (3,900 XP).  

```statblock
"name": "Manshoon Simulacrum (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "12"
"hp": !!int "126"
"hit_dice": "23d8 + 23"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "23"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "7"
  "Intelligence": !!int "11"
"skillsaves":
  "History": !!int "12"
  "Arcana": !!int "12"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Draconic, Goblin, Infernal, Orc, Undercommon"
"cr": "8"
"traits":
- "desc": "Manshoon is an 18th-level spellcaster. His spellcasting ability is Intelligence\
    \ (spell save DC 19, +11 to hit with spell attacks). He has the following wizard\
    \ spells prepared:\n\nCantrips (at will): [fire bolt](Mechanics/spells/fire-bolt.md),\
    \ [light](Mechanics/spells/light.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md), [shocking grasp](Mechanics/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [detect magic](Mechanics/spells/detect-magic.md), [mage\
    \ armor](Mechanics/spells/mage-armor.md), [magic missile](Mechanics/spells/magic-missile.md),\
    \ [shield](Mechanics/spells/shield.md)\n\n2nd level (3 slots): [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [mirror image](Mechanics/spells/mirror-image.md), [misty step](Mechanics/spells/misty-step.md)\n\
    \n3rd level (3 slots): [counterspell](Mechanics/spells/counterspell.md), [lightning\
    \ bolt](Mechanics/spells/lightning-bolt.md), [sending](Mechanics/spells/sending.md)\n\
    \n4th level (3 slots): [fire shield](Mechanics/spells/fire-shield.md), [greater\
    \ invisibility](Mechanics/spells/greater-invisibility.md), [polymorph](Mechanics/spells/polymorph.md)\n\
    \n5th level (3 slots): [Bigby's hand](Mechanics/spells/bigbys-hand.md), [scrying](Mechanics/spells/scrying.md),\
    \ [wall of force](Mechanics/spells/wall-of-force.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) bludgeoning damage."
  "name": "Metal Fist"
"source":
- "WDH"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDH/Manshoon%20Simulacrum.webp"
```
^statblock