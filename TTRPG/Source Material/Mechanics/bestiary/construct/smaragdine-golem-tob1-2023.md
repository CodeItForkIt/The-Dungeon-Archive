---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/14
- monster/environment/urban
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Smaragdine Golem"]
---
# [Smaragdine Golem](Mechanics\bestiary\construct/smaragdine-golem-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 219*  

*This large statue of emerald-green crystal has a humanoid body with the head of an ibis. Tiny symbols and runes are etched into it, and portions of it are inlaid with bits of gold.*

## Occult Initiates

Smaragdine golems are crafted by disciples of occult esoterica to guard their secret meeting halls, sacred texts, and the arcane books of power.

## Emerald Body

Though they seem to be made entirely of emeralds (and some are used in their construction), a smaragdine golem's body is closer to enchanted glass than to gemstones, a sad truth that has disappointed many plunderers.

## A Maker's Privilege

Though smaragdine golems are sometimes given to powerful mages, scholars, theurgists, and hierophants as a token of esteem, they are always subject first to the magic and orders of their creators.

```statblock
"name": "Smaragdine Golem (ToB1-2023)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "231"
"hit_dice": "22d10 + 110"
"stats":
- !!int "24"
- !!int "11"
- !!int "21"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "14"
"traits":
- "desc": "The golem doesn't require air, food, drink, or sleep."
  "name": "Construct Nature"
- "desc": "The golem's weapon attacks are magical. When the golem hits with any weapon,\
    \ the weapon deals an extra 5d8 force damage (included in the attack)."
  "name": "Enchanted Weapons"
- "desc": "The golem is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The golem has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "When the smaragdine golem counters or ends a spell with Absorb Spell, it\
    \ holds the spell's magical energy within its body and becomes Charged for 1 minute.\
    \ While Charged, the golem sheds dim light in a 10-foot radius."
  "name": "Magic Vessel"
"actions":
- "desc": "The smaragdine golem makes two Slam attacks. It can replace one attack\
    \ with a use of Release Spell."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 20\
    \ (3d8 + 7) bludgeoning damage plus 22 (5d8) force damage."
  "name": "Slam"
- "desc": "The smaragdine golem releases an absorbed spell's energy in a green burst\
    \ centered on a point the golem can see within 60 feet of it. Each creature, other\
    \ than the smaragdine golem, within 5 feet of that point per level of the absorbed\
    \ spell must make a DC 18 Dexterity saving throw. On a failure, a creature takes\
    \ 10 (3d6) force damage per level of the absorbed spell and is [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)\
    \ until the end of its next turn. On a success, a creature takes half the damage\
    \ and isn't [incapacitated](Mechanics/Rules/conditions.md#Incapacitated). The\
    \ golem can use this action only if it is Charged (see the Magic Vessel trait)."
  "name": "Release Spell (Recharge Special)"
"reactions":
- "desc": "When a creature the smaragdine golem can see within 30 feet of it casts\
    \ a spell, the golem can absorb the spell's energy, countering it. This works\
    \ like the [counterspell](Mechanics/spells/counterspell.md) spell, except the\
    \ golem must always make a spellcasting ability check, no matter the spell's level.\
    \ Alternatively, when a creature the golem can see within 30 feet of the golem\
    \ starts its turn while under the effects of a spell, such as bless or heroes'\
    \ feast, the golem can absorb the spell's magic, ending the effect. In either\
    \ case, the golem's ability check for this is +10. If it successfully counters\
    \ or ends the spell, it becomes Charged (see the Magic Vessel trait). The golem\
    \ can't use Absorb Spell while it is Charged."
  "name": "Absorb Spell"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Smaragdine%20Golem.webp"
```
^statblock

## Environment

urban