---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/17
- monster/size/large
- monster/type/monstrosity
statblock: inline
aliases: ["Sphinx (Type 1)"]
---
# [Sphinx (Type 1)](Mechanics\bestiary\monstrosity/sphinx-type-1-psz.md)
*Source: Plane Shift: Zendikar p. 24*  

Utterly inscrutable, sphinxes are mysterious creatures known for their wisdom and knowledge. Closely aligned with blue mana, they are utterly devoted to gaining and possessing knowledge—but not to sharing or acting upon it. Sphinxes are content to search out the mysteries of Zendikar, then sit in quiet contemplation of what they have learned. To them, everything is an intellectual exercise, including conversation. They are famously oblique, answering questions with questions and posing riddles to test the acuity of others.

Sphinxes choose remote locations for their lairs, preferring sites of great natural beauty such as waterfalls, high promontories, and small islands. They jealously protect their lairs from other sphinxes and large predators, such as dragons, but they pay little attention to smaller visitors. A sphinx's lair is often difficult to reach, and typically involves treacherous climbing for creatures without the ability to fly. A visitor who can reach the spot is often rewarded with an audience—but those who come in search of answers are likely to leave disappointed.

Either sphinx in the Monster Manual can represent the various sphinxes of Zendikar.

```statblock
"name": "Sphinx (Type 1) (PSZ)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "199"
"hit_dice": "19d10 + 95"
"stats":
- !!int "22"
- !!int "10"
- !!int "20"
- !!int "16"
- !!int "18"
- !!int "23"
"speed": "40 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "6"
  "Wisdom": !!int "10"
  "Intelligence": !!int "9"
  "Constitution": !!int "11"
"skillsaves":
  "Religion": !!int "15"
  "Perception": !!int "10"
  "Arcana": !!int "9"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 20"
"languages": "Common, Sphinx"
"cr": "17"
"traits":
- "desc": "The sphinx is a 12th-level spellcaster. Its spellcasting ability is Wisdom\
    \ (spell save DC 18, +10 to hit with spell attacks). It requires no material\
    \ components to cast its spells. The sphinx has the following cleric spells prepared:\n\
    \nCantrips (at will): [sacred flame](Mechanics/spells/sacred-flame.md), [spare\
    \ the dying](Mechanics/spells/spare-the-dying.md), [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](Mechanics/spells/command.md), [detect evil\
    \ and good](Mechanics/spells/detect-evil-and-good.md), [detect magic](Mechanics/spells/detect-magic.md)\n\
    \n2nd level (3 slots): [lesser restoration](Mechanics/spells/lesser-restoration.md),\
    \ [zone of truth](Mechanics/spells/zone-of-truth.md)\n\n3rd level (3 slots):\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [tongues](Mechanics/spells/tongues.md)\n\
    \n4th level (3 slots): [banishment](Mechanics/spells/banishment.md), [freedom\
    \ of movement](Mechanics/spells/freedom-of-movement.md)\n\n5th level (2 slots):\
    \ [flame strike](Mechanics/spells/flame-strike.md), [greater restoration](Mechanics/spells/greater-restoration.md)\n\
    \n6th level (1 slots): [heroes' feast](Mechanics/spells/heroes-feast.md)"
  "name": "Spellcasting"
- "desc": "The sphinx is immune to any effect that would sense its emotions or read\
    \ its thoughts, as well as any divination spell that it refuses. Wisdom ([Insight](Mechanics/Rules/skills.md#Insight))\
    \ checks made to ascertain the sphinx's intentions or sincerity have disadvantage."
  "name": "Inscrutable"
- "desc": "The sphinx's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The sphinx makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 17\
    \ (2d10 + 6) slashing damage."
  "name": "Claw"
- "desc": "The sphinx emits a magical roar. Each time it roars before finishing a\
    \ long rest, the roar is louder and the effect is different, as detailed below.\
    \ Each creature within 500 feet of the sphinx and able to hear the roar must make\
    \ a saving throw.\n\n- First Roar. Each creature that fails a DC 18 Wisdom\
    \ saving throw is [frightened](Mechanics/Rules/conditions.md#Frightened) for 1\
    \ minute. A [frightened](Mechanics/Rules/conditions.md#Frightened) creature can\
    \ repeat the saving throw at the end of each of its turns, ending the effect on\
    \ itself on a success.  \n- Second Roar. Each creature that fails a DC 18\
    \ Wisdom saving throw is [deafened](Mechanics/Rules/conditions.md#Deafened) and\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened) for 1 minute. A [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ creature is [paralyzed](Mechanics/Rules/conditions.md#Paralyzed) and can repeat\
    \ the saving throw at the end of each of its turns, ending the effect on itself\
    \ on a success.  \n- Third Roar. Each creature makes a DC 18 Constitution\
    \ saving throw. On a failed save, a creature takes 44 (8d10) thunder damage\
    \ and is knocked [prone](Mechanics/Rules/conditions.md#Prone). On a successful\
    \ save, the creature takes half as much damage and isn't knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \  "
  "name": "Roar (3/Day)"
"legendary_actions":
- "desc": "The sphinx makes one claw attack."
  "name": "Claw Attack"
- "desc": "The sphinx magically teleports, along with any equipment it is wearing\
    \ or carrying, up to 120 feet to an unoccupied space it can see."
  "name": "Teleport (Costs 2 Actions)"
- "desc": "The sphinx casts a spell from its list of prepared spells, using a spell\
    \ slot as normal."
  "name": "Cast a Spell (Costs 3 Actions)"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Sphinx%20%28Type%201%29.webp"
```
^statblock