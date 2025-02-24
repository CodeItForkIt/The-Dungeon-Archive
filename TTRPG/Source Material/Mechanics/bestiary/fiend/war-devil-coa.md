---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/16
- monster/size/huge
- monster/type/fiend/devil
statblock: inline
aliases: ["War Devil"]
---
# [War Devil](Mechanics\bestiary\fiend/war-devil-coa.md)
*Source: Chains of Asmodeus p. 260*  

Created through the sacrifice of other devils, both alive and dead, war devils vary in size and shape, but not personality. They crave combat and are highly aggressive, often commanding legions of lesser devils in wars. While they greatly enjoy bullying weaker creatures and exerting their dominance, they're highly submissive towards more powerful creatures and higher ranked devils.

## Battle Commanders

War devils are also extremely loyal to their creators, following practically any order given to them. When not taking orders, war devils are clever enough to command and make decisions on their own, making them extremely talented generals.

## Mighty Devils

Because of their construction, the appearance of war devils varies. That said, there are a few features that are common among most of their kind. Almost all war devils have thick, leathery wings, as well as massive, curved horns and sharpened teeth. They're also usually massive in size, having been created from multiple other devils, with the larger ones usually having higher-ranked positions. Though they prefer to use polearms of all kinds, war devils are also fully capable unarmed.

```statblock
"name": "War Devil (CoA)"
"size": "Huge"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "237"
"hit_dice": "19d12 + 114"
"stats":
- !!int "24"
- !!int "9"
- !!int "23"
- !!int "7"
- !!int "13"
- !!int "9"
"speed": "40 ft., fly 60 ft."
"saves":
  "Strength": !!int "12"
  "Constitution": !!int "11"
"skillsaves":
  "Intimidation": !!int "4"
  "Athletics": !!int "12"
  "Insight": !!int "6"
  "Perception": !!int "6"
"damage_resistances": "cold"
"damage_immunities": "fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"condition_immunities": "[frightened](Mechanics/Rules/conditions.md#Frightened), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Infernal, telepathy 120 ft."
"cr": "16"
"traits":
- "desc": "Magical darkness doesn't impede the war devil's darkvision."
  "name": "Devil's Sight"
- "desc": "Any hostile creature that starts its turn within 20 feet of the war devil\
    \ must succeed on a DC 18 Wisdom saving throw or have the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition until the start of the creature's next turn. If a creature's saving\
    \ throw is successful, the creature is immune to the war devil's Fear Aura for\
    \ the next 24 hours. This ability doesn't function if the war devil is [unconscious](Mechanics/Rules/conditions.md#Unconscious)."
  "name": "Fear Aura"
- "desc": "The war devil has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The war devil makes two attacks using its Cold- Iron Ranseur, Claws, or\
    \ a combination of the two."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 10 ft., one target. Hit: 23\
    \ (3d10 + 7) force damage plus 14 (4d6) cold damage."
  "name": "Cold-Iron Ranseur"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 20\
    \ (3d8 + 7) slashing damage. If the target is a Large or smaller creature, it\
    \ has the [grappled](Mechanics/Rules/conditions.md#Grappled) condition (escape\
    \ DC 20). While a creature is [grappled](Mechanics/Rules/conditions.md#Grappled),\
    \ the war devil can't make Claws attacks."
  "name": "Claws"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/War%20Devil.webp"
```
^statblock