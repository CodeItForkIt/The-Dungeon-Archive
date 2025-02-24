---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dodk
- monster/cr/5
- monster/size/large
- monster/type/elemental
statblock: inline
aliases: ["Walking Delerium Geode"]
---
# [Walking Delerium Geode](Mechanics\bestiary\elemental/walking-delerium-geode-dodk.md)
*Source: Dungeons of Drakkenheim p. 205*  

Contaminated Elementals can be found all over Drakkenheim, often in areas where the eldritch magics are especially concentrated. Many who have encountered these elementals have spoken of the city itself coming to life to attack them. Reports of ruins reaching out and crushing adventurers, burning flames moving and hunting with minds of their own, or contaminated pools lurching to engulf passersby have been heard. Even the blowing air itself has mustered parts of the Haze into shifting clouds that stalk adventurers through the streets. These magical creatures are a constant reminder that nothing in the city can be trusted, and that nowhere is truly safe.

```statblock
"name": "Walking Delerium Geode (DoDk)"
"size": "Large"
"type": "elemental"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d10 + 60"
"stats":
- !!int "20"
- !!int "8"
- !!int "20"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "30 ft., burrow 30 ft."
"damage_vulnerabilities": "radiant, thunder"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., tremorsense 60 ft., passive Perception 10"
"languages": "Deep Speech"
"cr": "5"
"traits":
- "desc": "If damage reduces the walking delerium geode to 0 hit points, the delerium\
    \ crystals in its body explode in a burst of contaminated energy, unless the damage\
    \ was force, radiant, or thunder. Each creature within 30 feet of it must succeed\
    \ on a DC 15 Constitution saving throw or take 42 (12d6) necrotic damage and\
    \ gain one level of contamination. In addition, this explosion triggers a random\
    \ arcane anomaly (see Dungeons of Drakkenheim)."
  "name": "Death Burst"
- "desc": "The walking delerium geode can burrow through nonmagical, unworked earth\
    \ and stone. While doing so, the geode doesn't disturb the material it moves through."
  "name": "Earth Glide"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d8 + 5) bludgeoning damage. A target hit by this attack must succeed on\
    \ a DC 15 Constitution saving throw or take 10 (3d6) necrotic damage and gain\
    \ one level of contamination."
  "name": "Shard Slam"
"source":
- "DoDk"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DoDk/Walking%20Delerium%20Geode.webp"
```
^statblock