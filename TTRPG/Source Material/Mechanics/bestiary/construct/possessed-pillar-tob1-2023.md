---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/7
- monster/environment/urban
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Possessed Pillar"]
---
# [Possessed Pillar](Mechanics\bestiary\construct/possessed-pillar-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 295*  

*This ancient animal-headed pillar is engraved with weathered symbols from ancient empires.*

## Animal Headed

Possessed pillars are carved from enormous blocks of stone to look like animal-headed gods of ancient pantheons or sometimes demonic figures of zealous cults. The most common are the jackal-faced and the ibis-headed variants, but pillars with baboon, crocodile, elephant, or hawk heads also exist.

## Hijacked by Cults

Some such pillars are claimed by various cults and carved anew with blasphemous symbols or smeared with blood, oils, and unguents as sacrificial offerings.

## Weapon Donations

Priests claim the weapons stolen by the pillars and distribute them to temple guards or sell them to fund temple activities.

```statblock
"name": "Possessed Pillar (ToB1-2023)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"stats":
- !!int "20"
- !!int "8"
- !!int "19"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "20 ft."
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "7"
"traits":
- "desc": "The possessed pillar doesn't require air, food, drink, or sleep"
  "name": "Construct Nature"
- "desc": "The possessed pillar's weapon attacks are magical. When the pillar hits\
    \ with a Slam attack, the Slam deals an extra 2d8 necrotic damage or 2d8 radiant\
    \ damage (included in the attack), the pillar's choice."
  "name": "Divine Fists"
- "desc": "While the pillar remains motionless, it is indistinguishable from a statue\
    \ or a carved column."
  "name": "False Appearance"
- "desc": "The pillar is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The pillar has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The eldritch magic powering the possessed pillar causes the pillar's body\
    \ to produce a minor magnetic field. When a creature hits the pillar with a weapon\
    \ made of metal, it must succeed on a DC 15 Strength saving throw or the weapon\
    \ sticks to the pillar. If the creature can't or won't let go of the weapon, it\
    \ is also stuck to the pillar and [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ A stuck weapon can't be used. A creature can take its action to remove one metal\
    \ object from the pillar by succeeding on a DC 15 Strength check. The pillar can\
    \ release one creature or metal object stuck to it as a bonus action. If the pillar\
    \ dies, all creatures and metal objects stuck to it are released."
  "name": "Magnetic Body"
"actions":
- "desc": "The possessed pillar makes two Slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) bludgeoning damage plus 9 (2d8) necrotic damage or (2d8) radiant\
    \ damage (the pillar's choice)."
  "name": "Slam"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Possessed%20Pillar.webp"
```
^statblock

## Environment

urban