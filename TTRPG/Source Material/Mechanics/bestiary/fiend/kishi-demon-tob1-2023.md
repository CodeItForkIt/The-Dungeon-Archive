---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/8
- monster/environment/planar
- monster/environment/urban
- monster/size/medium
- monster/type/fiend/demon
statblock: inline
aliases: ["Kishi Demon"]
---
# [Kishi Demon](Mechanics\bestiary\fiend/kishi-demon-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 84*  

*This strong and handsome warrior has a snarling hyena's face at the back of its head.*

## Dark Appetites

Kishi are two-faced male demons perpetually driven by their voracious appetites, carnal or otherwise, with a predilection for female humanoids. Kishi frequently behead, scalp, or skin their conquests and decorate their shields with their trophies.

## Hats and Veils

Kishi demons typically masquerade as muscular warriors or glib storytellers, wearing elaborate headdresses or clan veils to hide the demonic hyena face on the back of their head.

## Deadly Charmers

They use magical and nonmagical means of persuasion to inveigle women into their embrace, but their trysts always end in a grisly feast upon their victim's flesh.

```statblock
"name": "Kishi Demon (ToB1-2023)"
"size": "Medium"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor, [shield](Mechanics/items/shield.md)"
"hp": !!int "119"
"hit_dice": "14d8 + 56"
"stats":
- !!int "19"
- !!int "20"
- !!int "19"
- !!int "15"
- !!int "11"
- !!int "22"
"speed": "50 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "3"
  "Constitution": !!int "7"
"skillsaves":
  "Deception": !!int "9"
  "Perception": !!int "3"
  "Performance": !!int "9"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Abyssal, Celestial, Common, Draconic, telepathy 120 ft."
"cr": "8"
"traits":
- "desc": "The kishi casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 17):\n\nAt will:\
    \ [detect evil and good](Mechanics/spells/detect-evil-and-good.md), [detect magic](Mechanics/spells/detect-magic.md),\
    \ [suggestion](Mechanics/spells/suggestion.md)\n\n1/day: [dominate person](Mechanics/spells/dominate-person.md)\n\
    \n3/day: [glibness](Mechanics/spells/glibness.md)"
  "name": "Spellcasting"
- "desc": "The kishi's weapon attacks are magical. When the kishi hits with any weapon,\
    \ the weapon deals an extra 2d8 cold damage (included in the attack)."
  "name": "Fiendish Weapons"
- "desc": "The kishi has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks and on saving throws against being [blinded](Mechanics/Rules/conditions.md#Blinded),\
    \ [charmed](Mechanics/Rules/conditions.md#Charmed), [deafened](Mechanics/Rules/conditions.md#Deafened),\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [stunned](Mechanics/Rules/conditions.md#Stunned),\
    \ and knocked [unconscious](Mechanics/Rules/conditions.md#Unconscious)."
  "name": "Two Heads"
- "desc": "The kishi has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The kishi makes one Bite attack and two Spear attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 11\
    \ (2d6 + 4) piercing damage plus 9 (2d8) cold damage."
  "name": "Bite"
- "desc": "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing\
    \ damage if used with two hands to make a melee attack, plus 9 (2d8) cold damage."
  "name": "Spear"
"bonus_actions":
- "desc": "The kishi absorbs some of the essence of a creature it killed since the\
    \ end of its previous turn and magically creates a grisly trophy of the creature\
    \ on its shield or spear. For 1 hour, its Armor Class becomes 20, and creatures\
    \ of the same type as the slain creature have disadvantage on attack rolls against\
    \ the kishi."
  "name": "Trophy Shield"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Kishi%20Demon.webp"
```
^statblock

## Environment

planar, urban