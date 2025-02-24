---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1-4
- monster/environment/urban
- monster/size/small
- monster/type/construct
statblock: inline
aliases: ["Living Wick"]
---
# [Living Wick](Mechanics\bestiary\construct/living-wick-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 257*  

*The small, rough wax sculpture of a human stands at attention, a halo of light flickering around its head from some source behind it.*

## Enchanted Wicks

Living wicks are obedient wax statues brought to life by an enchanted wick that runs from the nape of their neck to their lower back. When new, a living wick looks and moves like a human. However, as the wick burns, the wax features melt, and the statue takes on a twisted, hunchbacked appearance.

## Short-Lived as a Candle

Living wicks are powered by flames, and therefore they have a predetermined life cycle. They are typically reduced to formless lumps in a month, but some say a living wick's affordability more than makes up for its inevitable obsolescence. Individuals looking to quickly construct a building or fortification without the expense of paid labor or the questionable ethics of necromancy find living wicks obedient and efficient, as do those needing an army for a single battle. They are active only when their wicks are lit, and they respond only to the commands of whoever lit them. This makes it easy to transfer living wicks between owners, even those not well-versed in the use of magic.

## Explosive Ends

The amount of magical energy contained within a living wick, paired with the manner in which it is released, gives them a remarkable capability for self-destruction. If their controller demands it, all living wicks can release the magic contained within their form all at once, engulfing themselves and anyone nearby in flames. This can make storing them a gamble, but many see it as an asset, especially those seeking to destroy evidence or anonymously attack their enemies.

```statblock
"name": "Living Wick (ToB1-2023)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "28"
"hit_dice": "8d6"
"stats":
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "5"
- !!int "5"
- !!int "5"
"speed": "20 ft."
"damage_vulnerabilities": "fire"
"damage_immunities": "poison, psychic"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [deafened](Mechanics/Rules/conditions.md#Deafened), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "passive Perception 7"
"languages": "understands the languages of its creator but can't speak"
"cr": "1/4"
"traits":
- "desc": "The living wick doesn't require air, food, drink, or sleep."
  "name": "Construct Nature"
- "desc": "The living wick is inactive and [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ while its wick is unlit. When its wick is lit, it obeys the commands of the\
    \ creature that lit the wick, and it sheds bright light in a 20-foot radius and\
    \ dim light for an additional 20 feet. The living wick's hp maximum is reduced\
    \ by 2 (1d4) for every 24 hours it remains lit and active, and no effect short\
    \ of a [wish](Mechanics/spells/wish.md) spell can remove this reduction. The living\
    \ wick dies when its hp maximum is reduced to 0.\n\nA creature grappling the active\
    \ living wick can take its action to extinguish the wick by succeeding on a DC\
    \ 12 Dexterity check. A creature within 5 feet of a living wick that is dormant\
    \ from an unlit wick can take an action to light the wick, gaining command of\
    \ the living wick."
  "name": "Wick-Powered"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage."
  "name": "Slam"
- "desc": "The living wick's controller can command the living wick to rapidly burn\
    \ through the remains of its wick, creating a devastating ball of fire. Each creature\
    \ within 20 feet of the living wick must make a DC 12 Dexterity saving throw,\
    \ taking 7 (2d6) fire damage on a failed save, or half as much damage on a successful\
    \ one. Flammable objects in the area and that aren't being worn or carried ignite.\
    \ The living wick then dies, becoming a lifeless puddle of wax."
  "name": "Consuming Inferno"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Living%20Wick.webp"
```
^statblock

## Environment

urban