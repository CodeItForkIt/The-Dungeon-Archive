---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/3
- monster/environment/planar
- monster/environment/urban
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Monolith Footman"]
---
# [Monolith Footman](Mechanics\bestiary\construct/monolith-footman-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 275*  

*A suit of elven parade armor, beautifully ornate but perhaps not terribly functional, stands at attention.*

## Beautiful Construct

Like the monolith champion, a monolith footman is an aesthetic triumph in the construct-builder's craft. Unlike the champion, the footman's visor remains closed, hiding any visage. If anything, form takes a higher priority in the footman than function, since their function is largely to look fine as they stand ready to perform servant's duties for their shadow fey masters.

## More Servant than Warrior

Because it's fashioned as grand armor, the footman looks more ferocious than it is. Its fighting ability is nothing to dismiss, but a secondary function. It's a combination of household servant and watchdog with imposing martial flair. Like the champion, a monolith footman's most alarming power is its ability to replace an opponent with a shadow double. This threat should be taken seriously by strangers to shadow as they weigh the risks of causing trouble in the fey courts.

## Perfect Loyalty

Monolith footmen follow orders to the letter and are unswerving in their loyalty.

```statblock
"name": "Monolith Footman (ToB1-2023)"
"size": "Large"
"type": "construct"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d10 + 16"
"stats":
- !!int "15"
- !!int "12"
- !!int "14"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "40 ft."
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't adamantine"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Elvish, Umbral"
"cr": "3"
"traits":
- "desc": "The monolith footman's weapon attacks are imbued with blue fey fire and\
    \ magical. When the footman hits with any weapon, the weapon deals an extra 1d8\
    \ cold damage or fire damage (included in the attack), the champion's choice."
  "name": "Coldfire Weapons"
- "desc": "The monolith footman doesn't require air, food, drink, or sleep."
  "name": "Construct Nature"
- "desc": "A critical hit against the footman causes it to burst into pieces and be\
    \ destroyed. Each creature within 5 feet of the footman must succeed on a DC 12\
    \ Dexterity saving throw or take 5 (2d4) bludgeoning damage."
  "name": "Simple Construction"
"actions":
- "desc": "The footman makes two Shortsword attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 9 (2d6\
    \ + 2) slashing damage plus 4 (1d8) cold damage or fire damage (the footman's\
    \ choice). If the target is within a fey court or castle, the target must succeed\
    \ on a DC 12 Charisma saving throw or become [invisible](Mechanics/Rules/conditions.md#Invisible),\
    \ silent, and [paralyzed](Mechanics/Rules/conditions.md#Paralyzed) for 1 minute,\
    \ while an illusory version of the target under the footman's control remains\
    \ visible and audible. The illusion shouts to the target's allies for a retreat\
    \ or similar action. The target can repeat the saving throw at the end of each\
    \ of its turns, ending the effect on itself and destroying the illusory double\
    \ on a success."
  "name": "Shortsword"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Monolith%20Footman.webp"
```
^statblock

## Environment

planar, urban