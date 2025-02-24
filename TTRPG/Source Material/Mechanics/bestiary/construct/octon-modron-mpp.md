---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/11
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Octon Modron"]
---
# [Octon Modron](Mechanics\bestiary\construct/octon-modron-mpp.md)
*Source: Morte's Planar Parade p. 40, Sigil and the Outlands*  

At the head of Mechanus's sectors are the octons, hierarch modrons that oversee daily governance. They provide data to other hierarchs, such as productivity reports to septons and diagnostic data to decatons. Octons have eight mechanical tentacles which they use to manipulate objects and defend themselves, spinning them in a bludgeoning whirlwind.

## Modrons

Constructed on the plane of Mechanus, modrons are partially mechanical beings that belong to a strict hierarchy. Each modron dutifully obeys commands from the rank directly above it and in turn acts as the superior to the rank directly below it, passing down commands from paragons of law to the lowliest monodrone. While most modrons are the lower-ranked base modrons—monodrones, duodrones, tridrones, quadrones, and pentadrones—the upper-tier hierarch modrons hold leadership positions, maintaining order in Mechanus and the realms beyond. For more information on modrons, see the*Monster Manual*.

```statblock
"name": "Octon Modron (MPP)"
"size": "Large"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "187"
"hit_dice": "22d10 + 66"
"stats":
- !!int "18"
- !!int "14"
- !!int "17"
- !!int "17"
- !!int "16"
- !!int "14"
"speed": "30 ft., fly 30 ft. (hover), swim 30 ft."
"saves":
  "Wisdom": !!int "7"
  "Intelligence": !!int "7"
"skillsaves":
  "Perception": !!int "11"
"damage_resistances": "psychic"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "Modron, telepathy 120 ft."
"cr": "11"
"traits":
- "desc": "The octon casts one of the following spells, requiring no material components\
    \ and using Intelligence as the spellcasting ability (spell save DC 15):\n\nAt\
    \ will: [detect magic](Mechanics/spells/detect-magic.md), [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [mending](Mechanics/spells/mending.md) (as an action)\n\n1/day each: [plane\
    \ shift](Mechanics/spells/plane-shift.md) (self only), [protection from evil and\
    \ good](Mechanics/spells/protection-from-evil-and-good.md)"
  "name": "Spellcasting"
- "desc": "The octon can't be compelled to act in a manner contrary to its nature\
    \ or its instructions."
  "name": "Axiomatic Mind"
- "desc": "The octon has advantage on initiative checks."
  "name": "Combat Ready"
- "desc": "If the octon dies, its body disintegrates into dust, leaving behind anything\
    \ it was carrying."
  "name": "Disintegration"
"actions":
- "desc": "The octon makes three Tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 14\
    \ (3d6 + 4) bludgeoning damage plus 9 (2d8) lightning damage."
  "name": "Tentacle"
- "desc": "The octon rapidly extends and spins its ring of tentacles. Each creature\
    \ within 20 feet of the octon must succeed on a DC 16 Strength saving throw or\
    \ be pulled up to 10 feet in a straight line toward the octon. Then, the octon\
    \ makes two Tentacle attacks against each creature within 10 feet of itself."
  "name": "Whirlwind of Tentacles (Recharge 5-6)"
"source":
- "MPP"
- "SatO"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Octon%20Modron.webp"
```
^statblock