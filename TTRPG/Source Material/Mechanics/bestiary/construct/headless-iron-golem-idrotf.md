---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/idrotf
- monster/cr/10
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Headless Iron Golem"]
---
# [Headless Iron Golem](Mechanics\bestiary\construct/headless-iron-golem-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 244*  

The mightiest of the golems, the iron golem is a massive, towering giant wrought of heavy metal. An iron golem's shape can be worked into any form, though most are fashioned to look like giant suits of armor. Its fist can destroy creatures with a single blow, and its clanging steps shake the earth beneath its feet. Iron golems wield enormous blades to extend their reach, and all can belch clouds of deadly poison.

An iron golem's body is smelted with rare tinctures and admixtures. Though other golems bear weaknesses inherent in their materials or the power of the elemental spirit bound within them, iron golems were designed to be nearly invulnerable. Their iron bodies imprison the spirits that drive them, and are susceptible only to weapons imbued with magic or the strength of adamantine.

```statblock
"name": "Headless Iron Golem (IDRotF)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "10d10 + 50"
"stats":
- !!int "24"
- !!int "9"
- !!int "20"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "fire; poison; psychic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks that aren't adamantine"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "10"
"traits":
- "desc": "The golem is [blinded](Mechanics/Rules/conditions.md#Blinded) and [deafened](Mechanics/Rules/conditions.md#Deafened),\
    \ giving it disadvantage on all its attack rolls, and it can't use its Poison\
    \ Breath."
  "name": "Headless"
- "desc": "Whenever the golem is subjected to fire damage, it takes no damage and\
    \ instead regains a number of hit points equal to the fire damage dealt."
  "name": "Fire Absorption"
- "desc": "The golem is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The golem has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The golem's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The golem makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +13 to hit, reach 5 ft., one target. Hit: 20\
    \ (3d8 + 7) bludgeoning damage."
  "name": "Slam"
- "desc": "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 23\
    \ (3d10 + 7) slashing damage."
  "name": "Sword"
"source":
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IDRotF/Headless%20Iron%20Golem.webp"
```
^statblock