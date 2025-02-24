---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/desert
- monster/size/large
- monster/type/plant
statblock: inline
aliases: ["Cactid"]
---
# [Cactid](Mechanics\bestiary\plant/cactid-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 48*  

*Rootlike tendrils explode from the sand at the base of this tall cactus bristling with needles. Its tendrils reach out, seeking prey.*

## Needled Sentients

Cactids are semi-sentient cacti that grow in a myriad of shapes and sizes, from ground-hugging barrels and spheroid clumps that pin their victims to the ground to towering saguaros with clublike arms that yank victims off their feet. Most cactids are green or brown with distinct ribs; all are lined with countless needles.

## Drain Fluids

In addition to gathering water, a cactid's tendril-roots can snag nearby creatures and pull them into a deadly embrace. Once a creature is pinned, the cactid's spines siphon off the victim's bodily fluids, until little but a dried husk remains. Many cactids are adorned with bright flowers or succulent fruit to lure prey into reach. Some scatter shiny objects within reach to attract sentient creatures. For those traveling the desert, however, a cactid's greatest treasure is the water stored within its flesh. A slain cactid's body yields up to four gallons of water.

## Slow Packs

Cactids were created by a nomadic sect of druids, but their original purpose is lost. They have limited mobility, and they often congregate in stands or travel together in a pack to better hunting grounds.

```statblock
"name": "Cactid (ToB1-2023)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "76"
"hit_dice": "8d10 + 32"
"stats":
- !!int "16"
- !!int "8"
- !!int "18"
- !!int "5"
- !!int "10"
- !!int "9"
"speed": "15 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [deafened](Mechanics/Rules/conditions.md#Deafened)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": "understands Sylvan but can't speak"
"cr": "3"
"actions":
- "desc": "The cactid makes two Tendril attacks and uses Reel."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 15 ft., one creature. Hit:\
    \ 10 (2d6 + 3) bludgeoning damage plus 3 (1d6) piercing damage, and the target\
    \ is [grappled](Mechanics/Rules/conditions.md#Grappled) (escape DC 13) if it is\
    \ a Medium or smaller creature. Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and if it isn't a Construct or Undead, the cactid begins draining fluid from\
    \ the target's body. At the start of each of the [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ creature's turns, the creature must make a DC 13 Constitution saving throw.\
    \ On a failure, its hp maximum is reduced by 3 (1d6). This reduction lasts until\
    \ the creature finishes a long rest after drinking at least one gallon of water.\
    \ The [grappled](Mechanics/Rules/conditions.md#Grappled) creature dies if this\
    \ effect reduces its hp maximum to 0. The cactid has two tendrils, each of which\
    \ can grapple only one target."
  "name": "Tendril"
- "desc": "The cactid pulls each creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by it up to 10 feet straight toward it."
  "name": "Reel"
"reactions":
- "desc": "When reduced to below half its hp maximum, the cactid releases a hail of\
    \ needles. Each creature within 15 feet of the cactid must make a DC 14 Dexterity\
    \ saving throw, taking 10 (3d6) piercing damage on a failed save, or half as\
    \ much damage on a successful one."
  "name": "Hail of Needles (1/Day)"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Cactid.webp"
```
^statblock

## Environment

desert