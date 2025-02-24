---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/8
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Decaton Modron"]
---
# [Decaton Modron](Mechanics\bestiary\construct/decaton-modron-mpp.md)
*Source: Morte's Planar Parade p. 36, Sigil and the Outlands, Turn of Fortune's Wheel*  

The least of the hierarchs, decatons monitor the physical well-being of base modrons. Two stubby legs support their spherical bodies, and ten mechanical tentacles sprout out from their rounded frames in all directions. Their heads contain ten eyes to readily observe the operations of surrounding base modrons. In emergencies, a decaton can discharge a bolt of electricity from each of its ten eyes, synchronizing them to deadly effect.

## Modrons

Constructed on the plane of Mechanus, modrons are partially mechanical beings that belong to a strict hierarchy. Each modron dutifully obeys commands from the rank directly above it and in turn acts as the superior to the rank directly below it, passing down commands from paragons of law to the lowliest monodrone. While most modrons are the lower-ranked base modrons—monodrones, duodrones, tridrones, quadrones, and pentadrones—the upper-tier hierarch modrons hold leadership positions, maintaining order in Mechanus and the realms beyond. For more information on modrons, see the*Monster Manual*.

```statblock
"name": "Decaton Modron (MPP)"
"size": "Large"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "144"
"hit_dice": "17d10 + 51"
"stats":
- !!int "18"
- !!int "12"
- !!int "16"
- !!int "15"
- !!int "15"
- !!int "11"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "5"
"skillsaves":
  "Perception": !!int "8"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 18"
"languages": "Modron, telepathy 120 ft."
"cr": "8"
"traits":
- "desc": "The decaton casts one of the following spells, requiring no material components\
    \ and using Intelligence as the spellcasting ability (spell save DC 13):\n\nAt\
    \ will: [detect magic](Mechanics/spells/detect-magic.md), [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [mending](Mechanics/spells/mending.md) (as an action)\n\n1/day each: [plane\
    \ shift](Mechanics/spells/plane-shift.md) (self only), [protection from evil and\
    \ good](Mechanics/spells/protection-from-evil-and-good.md)"
  "name": "Spellcasting"
- "desc": "The decaton can't be compelled to act in a manner contrary to its nature\
    \ or its instructions."
  "name": "Axiomatic Mind"
- "desc": "The decaton has advantage on initiative rolls."
  "name": "Combat Ready"
- "desc": "If the decaton dies, its body disintegrates into dust, leaving behind anything\
    \ it was carrying."
  "name": "Disintegration"
"actions":
- "desc": "The decaton makes three Tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d10 + 4) piercing damage, and if the target is a Medium or smaller creature,\
    \ it has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 14). Until this grapple ends, the decaton can't use this tentacle against\
    \ other targets. The decaton has ten tentacles, each of which can grapple one\
    \ target."
  "name": "Tentacle"
- "desc": "The decaton unleashes a barrage of lightning bolts from its eyes. Each\
    \ creature within 30 feet of the decaton must make a DC 13 Dexterity saving throw,\
    \ taking 38 (7d10) lightning damage on a failed save, or half as much damage\
    \ on a successful save."
  "name": "Lightning Rays (Recharge 6)"
"source":
- "MPP"
- "SatO"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Decaton%20Modron.webp"
```
^statblock