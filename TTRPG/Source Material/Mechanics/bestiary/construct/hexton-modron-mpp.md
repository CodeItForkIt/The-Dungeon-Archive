---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpp
- monster/cr/13
- monster/size/huge
- monster/type/construct
statblock: inline
aliases: ["Hexton Modron"]
---
# [Hexton Modron](Mechanics\bestiary\construct/hexton-modron-mpp.md)
*Source: Morte's Planar Parade p. 37, Turn of Fortune's Wheel*  

When the armies of Mechanus mobilize against the forces of chaos, hextons are the field generals who command modron troops. These hulking hierarchs lead groups of modrons in endeavors outside Mechanus, with the most notable example being the Great Modron March. Hextons have solid frames that bristle with six shining flanges. They boast a pair of arms and tentacles, both of which end in powerful pincers.

## Modrons

Constructed on the plane of Mechanus, modrons are partially mechanical beings that belong to a strict hierarchy. Each modron dutifully obeys commands from the rank directly above it and in turn acts as the superior to the rank directly below it, passing down commands from paragons of law to the lowliest monodrone. While most modrons are the lower-ranked base modrons—monodrones, duodrones, tridrones, quadrones, and pentadrones—the upper-tier hierarch modrons hold leadership positions, maintaining order in Mechanus and the realms beyond. For more information on modrons, see the*Monster Manual*.

```statblock
"name": "Hexton Modron (MPP)"
"size": "Huge"
"type": "construct"
"alignment": "typically  Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "209"
"hit_dice": "22d12 + 66"
"stats":
- !!int "19"
- !!int "16"
- !!int "17"
- !!int "19"
- !!int "17"
- !!int "15"
"speed": "40 ft., fly 40 ft. (hover)"
"saves":
  "Wisdom": !!int "8"
  "Intelligence": !!int "9"
"skillsaves":
  "Perception": !!int "13"
"damage_resistances": "lightning, psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 23"
"languages": "all, telepathy 120 ft."
"cr": "13"
"traits":
- "desc": "The hexton casts one of the following spells, requiring no material components\
    \ and using Intelligence as the spellcasting ability (spell save DC 17):\n\nAt\
    \ will: [detect magic](Mechanics/spells/detect-magic.md), [dispel magic](Mechanics/spells/dispel-magic.md),\
    \ [mending](Mechanics/spells/mending.md) (as an action)\n\n1/day each: [plane\
    \ shift](Mechanics/spells/plane-shift.md) (self only), [protection from evil and\
    \ good](Mechanics/spells/protection-from-evil-and-good.md)"
  "name": "Spellcasting"
- "desc": "The hexton can't be compelled to act in a manner contrary to its nature\
    \ or its instructions."
  "name": "Axiomatic Mind"
- "desc": "The hexton has advantage on initiative rolls."
  "name": "Combat Ready"
- "desc": "If the hexton dies, its body disintegrates into dust, leaving behind anything\
    \ it was carrying."
  "name": "Disintegration"
- "desc": "If the hexton fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (4/Day)"
"actions":
- "desc": "The hexton makes one Pincer attack and two Tentacle attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 13\
    \ (2d8 + 4) bludgeoning damage plus 10 (3d6) force damage. If the target is\
    \ a creature, it must succeed on a DC 17 Constitution saving throw or have the\
    \ [incapacitated](Mechanics/Rules/conditions.md#Incapacitated) condition until\
    \ the end of its next turn."
  "name": "Pincer"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d10 + 4) piercing damage, and if the target is a Medium or smaller creature,\
    \ it has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 14). Until this grapple ends, the hexton can't use this tentacle against\
    \ other targets. The hexton has six tentacles, each of which can grapple one target."
  "name": "Tentacle"
"reactions":
- "desc": "The hexton can take up to three reactions per round but only one per turn."
  "name": ""
- "desc": "The hexton attempts to interrupt a creature it can see that is casting\
    \ a spell. If the spell is 3rd level or lower, it fails and has no effect. If\
    \ the spell is 4th level or higher, the hexton makes an Intelligence check (DC\
    \ 10 + the spell's level). On a success, the spell fails and has no effect."
  "name": "Counter Magic"
- "desc": "When a creature within 120 feet of the hexton damages it, the hexton magically\
    \ retaliates with an arc of lightning. The creature must make a DC 17 Dexterity\
    \ saving throw, taking 11 (2d10) lightning damage on a failed save, or half\
    \ as much damage on a successful one."
  "name": "Lightning Rebuke"
"source":
- "MPP"
- "ToFW"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Hexton%20Modron.webp"
```
^statblock