---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/vrgr
- monster/cr/3
- monster/size/small
- monster/type/undead
statblock: inline
aliases: ["Brain in a Jar"]
---
# [Brain in a Jar](Mechanics\bestiary\undead/brain-in-a-jar-vrgr.md)
*Source: Van Richten's Guide to Ravenloft p. 278, Icewind Dale: Rime of the Frostmaiden p. 278*  

Through an eldritch ritual combining alchemy, necromancy, and grim surgical precision, the brain of a mortal being (willing or unwilling) is encased in a glass jar filled with preserving fluids and the liquefied goop of their body's flesh. The transformation renders the brain immortal and imbues it with psionic power, so that it can spend eternity plotting and executing its desires.

A brain in a jar can speak without vocal cords, psionically projecting its disembodied voice outward for all to hear. It enjoys conversation so much that it is prone to talking for hours on end, sometimes to itself if there are no others with whom it can speak. It also likes to think out loud and reflect on the events and decisions that led to its great transformation.

Being divorced from one's body can tax the mind, and the longer a brain in a jar exists, the more likely some form of insanity will take hold of it. A brain in a jar is particularly susceptible to dementia, schizophrenia, and paranoia.

## Immortal Vessels

The brain floats in a jar of solution, pulsating as it reacts to its surroundings. Some brains have been known to thump against the walls of their containers when excited or vexed. A jar's metal casing might be rusty but serviceable, or an elegantly wrought masterwork, depending on its creator. A brain in a jar weighs roughly 125 pounds.

```statblock
"name": "Brain in a Jar (VRGR)"
"size": "Small"
"type": "undead"
"alignment": "Any alignment"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "55"
"hit_dice": "10d6 + 20"
"stats":
- !!int "1"
- !!int "3"
- !!int "15"
- !!int "19"
- !!int "10"
- !!int "15"
"speed": "0 ft., fly 10 ft. (hover)"
"saves":
  "Charisma": !!int "4"
  "Intelligence": !!int "6"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [prone](Mechanics/Rules/conditions.md#Prone)"
"senses": "blindsight 120 ft. (blind beyond this radius); see also \"detect sentience\"\
  \ below, passive Perception 10"
"languages": "the languages it knew in life"
"cr": "3"
"traits":
- "desc": "The brain's innate spellcasting ability is Intelligence (spell save DC\
    \ 14, +6 to hit with spell attacks). It can innately cast the following spells,\
    \ requiring no components:\n\nAt will: [chill touch](Mechanics/spells/chill-touch.md)\
    \ (see \"Actions\" below), [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md), [zone of truth](Mechanics/spells/zone-of-truth.md)\n\
    \n1/day each: [compulsion](Mechanics/spells/compulsion.md), [hold monster](Mechanics/spells/hold-monster.md),\
    \ [sleep](Mechanics/spells/sleep.md) (3rd-level version), [Tasha's hideous laughter](Mechanics/spells/tashas-hideous-laughter.md)\n\
    \n3/day each: [charm person](Mechanics/spells/charm-person.md), [hold person](Mechanics/spells/hold-person.md)"
  "name": "Innate Spellcasting (Psionics)"
- "desc": "The brain can sense the presence and location of any creature within 300\
    \ feet of it that has an Intelligence of 3 or higher, regardless of interposing\
    \ barriers, unless the creature is protected by a [mind blank](Mechanics/spells/mind-blank.md)\
    \ spell."
  "name": "Detect Sentience"
- "desc": "The brain has advantage on saving throws against spells and other magic\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The brain doesn't require air, food, drink, or sleep."
  "name": "Unusual Nature"
"actions":
- "desc": "Ranged Spell Attack: +6 to hit, range 120 ft., one creature. Hit:\
    \ 13 (3d8) necrotic damage, and the target can't regain hit points until the\
    \ start of the brain's next turn. If the target is undead, it also has disadvantage\
    \ on attack rolls against the brain until the end of the brain's next turn."
  "name": "Chill Touch (Cantrip)"
- "desc": "The brain magically emits psychic energy in a 60-foot cone. Each creature\
    \ in that area must succeed on a DC 14 Intelligence saving throw or take 17 (3d8\
    \ + 4) psychic damage and be [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Mind Blast (Recharge 5-6)"
"source":
- "VRGR"
- "IDRotF"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VRGR/Brain%20in%20a%20Jar.webp"
```
^statblock