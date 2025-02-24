---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psi
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Necro-Alchemist"]
---
# [Necro-Alchemist](Mechanics\bestiary\humanoid/necro-alchemist-psi.md)
*Source: Plane Shift: Innistrad p. 20*  

Some bizarre and eccentric scientists use geists—the spirits of the dead—as an energy source to conduct strange experiments on living creatures and fuel crazed technological inventions. Necro-alchemists sometimes call themselves geistmages, but different practitioners identify themselves in different ways. What all have in common, however, is their use of elaborate contraptions to capture, bind, and draw the energy from geists.

This technology is often employed to power sprawling laboratories. But some necro-alchemists have managed to bind geists to smaller containers, including tubelike canisters that are strapped to the back and attached to weapons that hurl lightning. At their best, necro-alchemists use their technological advances to fight the crazed angels. However, even the most true-hearted geistmages have been known to capture the spirits of fallen allies to recharge a geist-lightning weapon that has run out of fuel.

Necro-alchemists are best described using the [mage](Mechanics/bestiary/humanoid/mage.md) statistics in the Monster Manual, with the assumption that their spellcasting is facilitated by the use of geist-powered devices.

```statblock
"name": "Necro-Alchemist (PSI)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "40"
"hit_dice": "9d8"
"stats":
- !!int "9"
- !!int "14"
- !!int "11"
- !!int "17"
- !!int "12"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "4"
  "Intelligence": !!int "6"
"skillsaves":
  "History": !!int "6"
  "Arcana": !!int "6"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "6"
"traits":
- "desc": "The Necro-Alchemist is a 9th-level spellcaster. Its spellcasting ability\
    \ is Intelligence (spell save DC 14, +6 to hit with spell attacks). The Necro-Alchemist\
    \ has the following wizard spells prepared:\n\nCantrips (at will): [fire bolt](Mechanics/spells/fire-bolt.md),\
    \ [light](Mechanics/spells/light.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md)\n\n1st level (4 slots):\
    \ [detect magic](Mechanics/spells/detect-magic.md), [mage armor](Mechanics/spells/mage-armor.md),\
    \ [magic missile](Mechanics/spells/magic-missile.md), [shield](Mechanics/spells/shield.md)\n\
    \n2nd level (3 slots): [misty step](Mechanics/spells/misty-step.md), [suggestion](Mechanics/spells/suggestion.md)\n\
    \n3rd level (3 slots): [counterspell](Mechanics/spells/counterspell.md), [fireball](Mechanics/spells/fireball.md),\
    \ [fly](Mechanics/spells/fly.md)\n\n4th level (3 slots): [greater invisibility](Mechanics/spells/greater-invisibility.md),\
    \ [ice storm](Mechanics/spells/ice-storm.md)\n\n5th level (1 slots): [cone\
    \ of cold](Mechanics/spells/cone-of-cold.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "PSI"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSI/Necro-Alchemist.webp"
```
^statblock