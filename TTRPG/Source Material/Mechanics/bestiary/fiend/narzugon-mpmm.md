---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/13
- monster/size/medium
- monster/type/fiend/devil
statblock: inline
aliases: ["Narzugon"]
---
# [Narzugon](Mechanics\bestiary\fiend/narzugon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 190, Mordenkainen's Tome of Foes p. 167, Adventure Atlas: The Mortuary*  

Paladins who make deals with devils and carry their twisted sense of honor into the afterlife are especially valuable to the archdukes of the Nine Hells. These narzugons act as horrific perversions of knights errant, carrying out their masters' will.

Narzugons wield hell-forged lances that shunt the souls of any they killed to the River Styx for rebirth as [lemures](Mechanics/bestiary/fiend/lemure.md). Every lance bears the marks of both a narzugon and its master.

Each narzugon claims a [nightmare](Mechanics/bestiary/fiend/nightmare.md) as its mount. These steeds are bound by [infernal tack](Mechanics/items/infernal-tack-mtf.md) and must respond to the summons and commands of the spurs' wearer.

```statblock
"name": "Narzugon (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Typically  Lawful Evil"
"ac": !!int "20"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"stats":
- !!int "20"
- !!int "10"
- !!int "17"
- !!int "16"
- !!int "14"
- !!int "19"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Dexterity": !!int "5"
  "Constitution": !!int "8"
"skillsaves":
  "Perception": !!int "12"
"damage_resistances": "acid; cold; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 22"
"languages": "Common, Infernal, telepathy 120 ft."
"cr": "13"
"traits":
- "desc": "The narzugon wears spurs that are part of [infernal tack](Mechanics/items/infernal-tack-mtf.md),\
    \ which allow it to summon its [nightmare](Mechanics/bestiary/fiend/nightmare.md)\
    \ companion as an action."
  "name": "Infernal Tack"
- "desc": "The narzugon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The narzugon makes three Hellfire Lance attacks. It also uses Infernal\
    \ Command or Terrifying Command."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 11\
    \ (1d12 + 5) piercing damage plus 16 (3d10) fire damage. If this damage kills\
    \ a creature with a soul, the soul rises from the River Styx as a [lemure](Mechanics/bestiary/fiend/lemure.md)\
    \ in Avernus in 1d4 hours. If the creature isn't revived before then, only a\
    \ [wish](Mechanics/spells/wish.md) spell or killing the lemure and casting true\
    \ resurrection on the creature's original body can restore it to life. Constructs\
    \ and devils are immune to this effect."
  "name": "Hellfire Lance"
- "desc": "Each ally of the narzugon within 60 feet of it can't be [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ or [frightened](Mechanics/Rules/conditions.md#Frightened) until the end of the\
    \ narzugon's next turn."
  "name": "Infernal Command"
- "desc": "Each creature within 60 feet of the narzugon that isn't a Fiend must succeed\
    \ on a DC 17 Charisma saving throw or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ of the narzugon for 1 minute. A creature can repeat the saving throw at the\
    \ end of each of its turns, ending the effect on itself on a success. A creature\
    \ that makes a successful saving throw is immune to this narzugon's Terrifying\
    \ Command for 24 hours."
  "name": "Terrifying Command"
- "desc": "The narzugon, or one creature it touches, regains 100 hit points."
  "name": "Healing (1/Day)"
"source":
- "MPMM"
- "MTF"
- "AATM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Narzugon.webp"
```
^statblock