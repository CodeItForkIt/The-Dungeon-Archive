---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bgg
- monster/cr/14
- monster/size/gargantuan
- monster/type/monstrosity/dinosaur
statblock: inline
aliases: ["Regisaur"]
---
# [Regisaur](Mechanics\bestiary\monstrosity/regisaur-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 130*  

Aptly called "the ruler of dinosaurs," a regisaur is an enormous predator large enough to swallow a giant whole. Fiery veins of elemental energy course through its skin and glow in its eyes and nostrils.

## Dinosaurs

When Annam's children first began to populate the worlds of the Material Plane, the All-Father created behemoth dinosaurs to live alongside them as companions. The primeval magic used to create the dinosaurs still thrums through their being and manifests in colorful, scar-like lines on their towering bodies. Some of these ancient dinosaurs persist in timeless jungles, hidden enclaves, and other lands untouched by the rest of the world.

```statblock
"name": "Regisaur (BGG)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "181"
"hit_dice": "11d20 + 66"
"stats":
- !!int "27"
- !!int "8"
- !!int "23"
- !!int "4"
- !!int "12"
- !!int "6"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "14"
"traits":
- "desc": "The regisaur has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The regisaur makes one Bite attack and one Tail attack. The regisaur can't\
    \ target the same creature with both attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 47\
    \ (6d12 + 8) piercing damage, and the target has the [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ condition (escape DC 18). Until this grapple ends, the target has the [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ condition, and the regisaur can't Bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +13 to hit, reach 20 ft., one target. Hit: 26\
    \ (4d8 + 8) bludgeoning damage."
  "name": "Tail"
"bonus_actions":
- "desc": "Melee Weapon Attack: +13 to hit, reach 5 ft., one Huge or smaller creature\
    \ [grappled](Mechanics/Rules/conditions.md#Grappled) by the regisaur. Hit: The\
    \ regisaur swallows the target, and the grapple ends. A swallowed creature has\
    \ the [blinded](Mechanics/Rules/conditions.md#Blinded) and [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ conditions, it has total cover against attacks and other effects outside the\
    \ regisaur, and it takes 7 (2d6) acid damage at the start of each of its turns.\
    \ The regisaur can have up to two creatures swallowed at a time.\n\nIf the regisaur\
    \ takes 25 damage or more on a single turn from a swallowed creature, the regisaur\
    \ must succeed on a DC 16 Constitution saving throw at the end of that turn or\
    \ regurgitate the creature, which falls in a space within 5 feet of the regisaur\
    \ and has the [prone](Mechanics/Rules/conditions.md#Prone) condition; the creature\
    \ no longer has the [blinded](Mechanics/Rules/conditions.md#Blinded) and [restrained](Mechanics/Rules/conditions.md#Restrained)\
    \ conditions."
  "name": "Swallow"
"source":
- "BGG"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BGG/Regisaur.webp"
```
^statblock