---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/imr
- monster/cr/6
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Brain in Iron"]
---
# [Brain in Iron](Mechanics\bestiary\construct/brain-in-iron-imr.md)
*Source: Infernal Machine Rebuild p. 48*  

```statblock
"name": "Brain in Iron (IMR)"
"size": "Large"
"type": "construct"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"stats":
- !!int "1"
- !!int "1"
- !!int "15"
- !!int "19"
- !!int "10"
- !!int "15"
"speed": "20 ft."
"saves":
  "Charisma": !!int "5"
  "Intelligence": !!int "7"
"damage_immunities": "necrotic, poison, psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "6"
"traits":
- "desc": "The brain in iron's innate spellcasting ability is Intelligence (spell\
    \ save DC 15). It can innately cast the following spells, requiring no components:\n\
    \nAt will: [detect thoughts](Mechanics/spells/detect-thoughts.md), [mage hand](Mechanics/spells/mage-hand.md),\
    \ [zone of truth](Mechanics/spells/zone-of-truth.md)\n\n1/day each: [compulsion](Mechanics/spells/compulsion.md),\
    \ [hold monster](Mechanics/spells/hold-monster.md), [sleep](Mechanics/spells/sleep.md)\
    \ (cast at 3rd level), [Tasha's hideous laughter](Mechanics/spells/tashas-hideous-laughter.md)\n\
    \n3/day each: [charm person](Mechanics/spells/charm-person.md), [command](Mechanics/spells/command.md),\
    \ [hold person](Mechanics/spells/hold-person.md)"
  "name": "Innate Spellcasting (Psionics)"
- "desc": "The brain in iron can sense the presence and location of any creature within\
    \ 300 feet of it that has an Intelligence of 3 or higher, regardless of interposing\
    \ barriers, unless the creature is protected by a [mind blank](Mechanics/spells/mind-blank.md)\
    \ spell."
  "name": "Detect Sentience"
- "desc": "The brain in iron has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The brain in iron magically emits psychic energy in a 60-foot cone. Each\
    \ creature in that area must succeed on a DC 15 Intelligence saving throw or take\
    \ 13 (2d8 + 4) psychic damage and be [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Mind Blast (Recharge 5-6)"
"source":
- "IMR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/IMR/Brain%20in%20Iron.webp"
```
^statblock