---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tdcsr
- monster/cr/
- monster/size/medium
- monster/type/plant
statblock: inline
aliases: ["Blighted Sapling"]
---
# [Blighted Sapling](Mechanics\bestiary\plant/blighted-sapling-tdcsr.md)
*Source: Tal'Dorei Campaign Setting Reborn p. 172*  

```statblock
"name": "Blighted Sapling (TDCSR)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac_class": "10 + PB (natural armor)"
"stats":
- !!int "8"
- !!int "13"
- !!int "12"
- !!int "4"
- !!int "8"
- !!int "3"
"speed": "30 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "necrotic, poison"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 9"
"languages": "understands the languages you speak"
"traits":
- "desc": "The creature has immunity to necrotic and poison damage and to the [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ condition."
  "name": "Blighted Resilience (10th level or higher)"
- "desc": "When the creature is reduced to 0 hit points, it explodes in a burst of\
    \ toxic mulch or fetid viscera. Each creature within 5 feet of the exploding creature\
    \ must succeed on a Constitution saving throw against your spell save DC or take\
    \ necrotic damage based on the creature's challenge rating (see the table below).\
    \ As an action, you can also cause a summoned creature to explode, immediately\
    \ killing it.\n\nToxic Demise Damage\n\n| Creature CR | Damage |\n|-------------|--------|\n\
    | 1/4 or lower | 1d4 necrotic damage |\n| 1/2 | 1d6 necrotic damage |\n| 1\
    \ or higher | A number of  d8s of necrotic damage equal to the creature's challenge\
    \ rating |\n| No challenge rating | A number of d6s of necrotic damage equal to\
    \ your proficiency bonus |\n^toxic-demise-damage"
  "name": "Toxic Demise (10th level or higher)"
"actions":
- "desc": "When you reach 14th level in this class, the blighted sapling makes two\
    \ claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: YourSpellAttack to hit, reach 5 ft., one target.\
    \ Hit:  2d4 + PB piercing damage."
  "name": "Claws"
"source":
- "TDCSR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TDCSR/Blighted%20Sapling.webp"
```
^statblock