---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/kftgv
- monster/cr/1
- monster/size/medium
- monster/type/elemental
statblock: inline
aliases: ["Ashen Animated Armor"]
---
# [Ashen Animated Armor](Mechanics\bestiary\elemental/ashen-animated-armor-kftgv.md)
*Source: Keys from the Golden Vault p. 157*  

This suit of magically animated plate armor clamors as it moves, banging and grinding like the vengeful spirit of a fallen knight.

```statblock
"name": "Ashen Animated Armor (KftGV)"
"size": "Medium"
"type": "elemental"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"stats":
- !!int "14"
- !!int "11"
- !!int "13"
- !!int "1"
- !!int "3"
- !!int "1"
"speed": "25 ft."
"damage_immunities": "fire, poison, psychic"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [deafened](Mechanics/Rules/conditions.md#Deafened), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "1"
"traits":
- "desc": "The armor is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ while in the area of an [antimagic field](Mechanics/spells/antimagic-field.md).\
    \ If targeted by [dispel magic](Mechanics/spells/dispel-magic.md), the armor must\
    \ succeed on a Constitution saving throw against the caster's spell save DC or\
    \ fall [unconscious](Mechanics/Rules/conditions.md#Unconscious) for 1 minute."
  "name": "Antimagic Susceptibility"
- "desc": "While the armor remains motionless, it is indistinguishable from a normal\
    \ suit of armor."
  "name": "False Appearance"
- "desc": "When the armor drops to 0 hit points, it is reduced to a pile of ash, and\
    \ any equipment it was wearing or carrying falls to the ground."
  "name": "Ashen Creature"
"actions":
- "desc": "The armor makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Slam"
"source":
- "KftGV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/KftGV/Ashen%20Animated%20Armor.webp"
```
^statblock