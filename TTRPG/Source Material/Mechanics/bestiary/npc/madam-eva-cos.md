---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/cos
- monster/cr/10
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Madam Eva"]
---
# [Madam Eva](Mechanics\bestiary\npc/madam-eva-cos.md)
*Source: Curse of Strahd p. 233*  

The fortune-teller Madam Eva lives among the Vistani but isn't truly one of them. She appears to be in her seventies, but she is, in fact, much older.

## Royal Blood

Madam Eva is Strahd's half-sister, though Strahd is unaware of this fact. Her real name is Katarina, and she is the daughter of a Vistani woman whom King Barov, Strahd's father, took to his bed during one of his many crusades. Madam Eva knows she is Strahd's half-sister but has told no one of the royal blood flowing through her veins.

## Mother Night

Over four hundred years ago, Katarina came to Barovia and insinuated herself into Strahd's court, working as a maid in Castle Ravenloft. She came to know the castle like the back of her hand, and she was present for the wedding of Sergei and Tatyana. After Strahd went mad and murdered his brother, she fled the castle and took refuge with the Vistani. Later, she forged a pact with the goddess Mother Night, trading her youth for the power to undo the evil that Strahd had wrought. Mother Night transformed Katarina into an ageless crone gifted with the power of magical foresight. In the guise of Madam Eva, she uses this ability to help Strahd. She can send her Vistani out in their wagons to visit other worlds and bring adventurers to Strahd's domain, in hopes that they will find a way to destroy the vampire or set Strahd free.

## For the Love of Strahd

The Dark Powers of Ravenloft would consider Madam Eva a worthy choice to replace Strahd as the master of Ravenloft, but she has all the power she desires and doesn't seek to supplant him. She would rather help Strahd find someone else to succeed him, although she has grave doubts about her ability to locate such an individual.

None of Madam Eva's Vistani kin know her true identity or purpose. They puzzle over her desire to remain in Barovia.

## Madam Eva's Traits

### Ideal

"I wish Strahd to be free of his curse."

### Bond

"The Vistani are my people now."

### Flaw

"The people whose fates I divine aren't important. They are but the means to an end."

```statblock
"name": "Madam Eva (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "10"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"stats":
- !!int "8"
- !!int "11"
- !!int "12"
- !!int "17"
- !!int "20"
- !!int "18"
"speed": "20 ft."
"saves":
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "8"
  "Deception": !!int "8"
  "Religion": !!int "7"
  "Insight": !!int "13"
  "Perception": !!int "9"
  "Arcana": !!int "7"
"senses": "passive Perception 19"
"languages": "Abyssal, Common, Elvish, Infernal"
"cr": "10"
"traits":
- "desc": "Madam Eva is a 16th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (spell save DC 17, +9 to hit with spell attacks). Madam Eva has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [light](Mechanics/spells/light.md),\
    \ [mending](Mechanics/spells/mending.md), [sacred flame](Mechanics/spells/sacred-flame.md),\
    \ [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\n1st level (4 slots): [bane](Mechanics/spells/bane.md),\
    \ [command](Mechanics/spells/command.md), [detect evil and good](Mechanics/spells/detect-evil-and-good.md),\
    \ [protection from evil and good](Mechanics/spells/protection-from-evil-and-good.md)\n\
    \n2nd level (3 slots): [lesser restoration](Mechanics/spells/lesser-restoration.md),\
    \ [protection from poison](Mechanics/spells/protection-from-poison.md), [spiritual\
    \ weapon](Mechanics/spells/spiritual-weapon.md)\n\n3rd level (3 slots): [create\
    \ food and water](Mechanics/spells/create-food-and-water.md), [speak with dead](Mechanics/spells/speak-with-dead.md),\
    \ [spirit guardians](Mechanics/spells/spirit-guardians.md)\n\n4th level (3 slots):\
    \ [divination](Mechanics/spells/divination.md), [freedom of movement](Mechanics/spells/freedom-of-movement.md),\
    \ [guardian of faith](Mechanics/spells/guardian-of-faith.md)\n\n5th level (2\
    \ slots): [greater restoration](Mechanics/spells/greater-restoration.md), [raise\
    \ dead](Mechanics/spells/raise-dead.md)\n\n6th level (1 slots): [find the\
    \ path](Mechanics/spells/find-the-path.md), [harm](Mechanics/spells/harm.md),\
    \ [true seeing](Mechanics/spells/true-seeing.md)\n\n7th level (1 slots): [fire\
    \ storm](Mechanics/spells/fire-storm.md), [regenerate](Mechanics/spells/regenerate.md)\n\
    \n8th level (1 slots): [earthquake](Mechanics/spells/earthquake.md)"
  "name": "Spellcasting"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ piercing damage."
  "name": "Dagger"
- "desc": "Madam Eva targets one creature that she can see within 30 feet of her.\
    \ The target must succeed on a DC 17 Wisdom saving throw or be cursed. While cursed,\
    \ the target is [blinded](Mechanics/Rules/conditions.md#Blinded) and [deafened](Mechanics/Rules/conditions.md#Deafened).\
    \ The curse lasts until ended with a [greater restoration](Mechanics/spells/greater-restoration.md)\
    \ spell, a [remove curse](Mechanics/spells/remove-curse.md) spell, or similar\
    \ magic. When the curse ends, Madam Eva takes 5d6 psychic damage."
  "name": "Curse (Recharges after a Long Rest)"
- "desc": "Madam Eva targets one creature that she can see within 10 feet of her and\
    \ casts one of the following spells on the target (save DC 17), requiring neither\
    \ somatic nor material components to do so: [animal friendship](Mechanics/spells/animal-friendship.md),\
    \ [charm person](Mechanics/spells/charm-person.md), or [hold person](Mechanics/spells/hold-person.md).\
    \ If the target succeeds on the initial saving throw, Madam Eva is [blinded](Mechanics/Rules/conditions.md#Blinded)\
    \ until the end of her next turn. Once a target succeeds on a saving throw against\
    \ this effect, it is immune to the Evil Eye power of all Vistani for 24 hours."
  "name": "Evil Eye (Recharges after a Short or Long Rest)"
"source":
- "CoS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoS/Madam%20Eva.webp"
```
^statblock