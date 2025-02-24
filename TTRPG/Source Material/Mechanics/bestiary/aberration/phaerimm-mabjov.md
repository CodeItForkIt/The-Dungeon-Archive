---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mabjov
- monster/cr/15
- monster/size/large
- monster/type/aberration
statblock: inline
aliases: ["Phaerimm"]
---
# [Phaerimm](Mechanics\bestiary\aberration/phaerimm-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 145*  

Highly intelligent, phaerimms are malevolent aberrations that dwell deep beneath the surface of the world. Natural spellcasters, they delight in bringing pain and suffering to others. It is said phaerimms would willingly wipe every other being from existence, save for the fact they would then lack slaves to torture for sport.

## Monstrous Horrors

Phaerimms are hideous looking creatures—bulbous bodies with spindly arms and legs, topped by a gaping maw filled with row upon row of razor-sharp teeth. Their evil magic drains life and moisture from the natural world, and the Anauroch Desert was created through extensive use of their powers.

## Mental Enslavement

A phaerimm's mind-controlling abilities rival those of any mind flayer or beholder. Extremely solitary beings, they surround themselves with a retinue of mentally dominated creatures that serve as bodyguards, soldiers, and hunters. When these thralls cease to be useful, they are slaughtered and devoured by their phaerimm master. The phaerimm language is incomprehensible to humanoids, even with the use of magical assistance. However, a phaerimm can use telepathic magic to communicate with other beings through its slaves, though due to their solitary existence they seldom have need to communicate at all. The only real exception occurs on those rare occasions when several phaerimm will work together to defeat an enemy that is too strong for them to face individually.

## An Endangered Species

Phaerimms were pushed to the edge of extinction thousands of years ago by the ancient Netherese wizards. Only a few isolated pockets still exist, typically sealed away in deep chambers by their enemies. Phaerimms still have a particular hatred for tomb tappers, a Netherese construct that is immune to their mind control. Their population has been slow to recover from this purge, as a phaerimm is only capable of producing a single egg every century. This egg must be injected into a host through a stinger on the phaerimm's tail, which paralyzes the victim. The larva then consumes the host—still alive—from the inside.

```statblock
"name": "Phaerimm (MaBJoV)"
"size": "Large"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "170"
"hit_dice": "20d10 + 60"
"stats":
- !!int "20"
- !!int "13"
- !!int "16"
- !!int "19"
- !!int "20"
- !!int "23"
"speed": "15 ft., fly 30 ft. (hover)"
"saves":
  "Charisma": !!int "11"
  "Intelligence": !!int "9"
"skillsaves":
  "Insight": !!int "10"
  "Arcana": !!int "9"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[petrified](Mechanics/Rules/conditions.md#Petrified)"
"senses": "truesight 120 ft., passive Perception 15"
"languages": "Undercommon, understands Common, telepathy 100 ft."
"cr": "15"
"traits":
- "desc": "The phaerimm casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 19):\n\nAt will:\
    \ [mage hand](Mechanics/spells/mage-hand.md), [minor illusion](Mechanics/spells/minor-illusion.md),\
    \ [telekinesis](Mechanics/spells/telekinesis.md)\n\n1/day each: [chain lightning](Mechanics/spells/chain-lightning.md),\
    \ [confusion](Mechanics/spells/confusion.md), [dominate monster](Mechanics/spells/dominate-monster.md),\
    \ [greater invisibility](Mechanics/spells/greater-invisibility.md), [hold monster](Mechanics/spells/hold-monster.md),\
    \ [mass suggestion](Mechanics/spells/mass-suggestion.md), [prismatic spray](Mechanics/spells/prismatic-spray.md),\
    \ [reverse gravity](Mechanics/spells/reverse-gravity.md)\n\n2/day each: [crown\
    \ of madness](Mechanics/spells/crown-of-madness.md), [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [dominate person](Mechanics/spells/dominate-person.md), [fear](Mechanics/spells/fear.md),\
    \ [fireball](Mechanics/spells/fireball.md), [phantasmal force](Mechanics/spells/phantasmal-force.md),\
    \ [magic missile](Mechanics/spells/magic-missile.md), [shield](Mechanics/spells/shield.md)"
  "name": "Spellcasting"
- "desc": "The phaerimm discerns the location of all magical auras within sight and\
    \ knows which creatures within 60 feet are spellcasters."
  "name": "Arcane Sight"
- "desc": "The phaerimm can concentrate on two different spells at the same time.\
    \ If [concentration](Mechanics/Rules/conditions.md#Concentration) is broken, then\
    \ both spells fade immediately."
  "name": "Extended Concentration"
- "desc": "The phaerimm is immune to any spell or effect that would alter its form."
  "name": "Immutable Form"
- "desc": "The phaerimm has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The phaerimm makes four Claw attacks and then makes a Bite or Stinger attack.\
    \ Alternatively, it uses Spellcasting and then makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 18\
    \ (2d12 + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 12\
    \ (2d6 + 5) piercing damage. If the target fails a DC 18 Constitution saving\
    \ throw, they have the [paralyzed](Mechanics/Rules/conditions.md#Paralyzed) condition\
    \ for 1 minute. The phaerimm's poison forces the [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ target to float 5 feet above the ground. The target may repeat the saving throw\
    \ at the end of each of it's turns."
  "name": "Stinger"
- "desc": "The phaerimm makes a Stinger attack against a [paralyzed](Mechanics/Rules/conditions.md#Paralyzed)\
    \ target. If the stinger hits, an egg is implanted in the target. This egg can\
    \ only be removed by spells that cure disease, such as lesser restoration. If\
    \ the egg is not removed within 90 days, the larva emerges, and the host is killed.\
    \ A phaerimm has a single egg so may only use this ability once."
  "name": "Implant"
"source":
- "MaBJoV"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MaBJoV/Phaerimm.webp"
```
^statblock