---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/11
- monster/size/large
- monster/type/monstrosity
statblock: inline
aliases: ["Sphinx (Type 2)"]
---
# [Sphinx (Type 2)](Mechanics\bestiary\monstrosity/sphinx-type-2-psz.md)
*Source: Plane Shift: Zendikar p. 24*  

Utterly inscrutable, sphinxes are mysterious creatures known for their wisdom and knowledge. Closely aligned with blue mana, they are utterly devoted to gaining and possessing knowledge—but not to sharing or acting upon it. Sphinxes are content to search out the mysteries of Zendikar, then sit in quiet contemplation of what they have learned. To them, everything is an intellectual exercise, including conversation. They are famously oblique, answering questions with questions and posing riddles to test the acuity of others.

Sphinxes choose remote locations for their lairs, preferring sites of great natural beauty such as waterfalls, high promontories, and small islands. They jealously protect their lairs from other sphinxes and large predators, such as dragons, but they pay little attention to smaller visitors. A sphinx's lair is often difficult to reach, and typically involves treacherous climbing for creatures without the ability to fly. A visitor who can reach the spot is often rewarded with an audience—but those who come in search of answers are likely to leave disappointed.

Either sphinx in the Monster Manual can represent the various sphinxes of Zendikar.

```statblock
"name": "Sphinx (Type 2) (PSZ)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "18"
- !!int "18"
- !!int "18"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  "Religion": !!int "8"
  "Perception": !!int "8"
  "History": !!int "12"
  "Arcana": !!int "12"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 18"
"languages": "Common, Sphinx"
"cr": "11"
"traits":
- "desc": "The sphinx is a 9th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 16, +8 to hit with spell attacks). It requires no material\
    \ components to cast its spells. The sphinx has the following wizard spells prepared:\n\
    \nCantrips (at will): [mage hand](Mechanics/spells/mage-hand.md), [minor illusion](Mechanics/spells/minor-illusion.md),\
    \ [prestidigitation](Mechanics/spells/prestidigitation.md)\n\n1st level (4 slots):\
    \ [detect magic](Mechanics/spells/detect-magic.md), [identify](Mechanics/spells/identify.md),\
    \ [shield](Mechanics/spells/shield.md)\n\n2nd level (3 slots): [darkness](Mechanics/spells/darkness.md),\
    \ [locate object](Mechanics/spells/locate-object.md), [suggestion](Mechanics/spells/suggestion.md)\n\
    \n3rd level (3 slots): [dispel magic](Mechanics/spells/dispel-magic.md), [remove\
    \ curse](Mechanics/spells/remove-curse.md), [tongues](Mechanics/spells/tongues.md)\n\
    \n4th level (3 slots): [banishment](Mechanics/spells/banishment.md), [greater\
    \ invisibility](Mechanics/spells/greater-invisibility.md)\n\n5th level (1 slots):\
    \ [legend lore](Mechanics/spells/legend-lore.md)"
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
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 13\
    \ (2d8 + 4) slashing damage."
  "name": "Claw"
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
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Sphinx%20%28Type%202%29.webp"
```
^statblock