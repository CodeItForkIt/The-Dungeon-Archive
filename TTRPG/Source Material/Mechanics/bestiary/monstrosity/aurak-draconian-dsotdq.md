---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dsotdq
- monster/cr/6
- monster/size/medium
- monster/type/monstrosity/sorcerer
statblock: inline
aliases: ["Aurak Draconian"]
---
# [Aurak Draconian](Mechanics\bestiary\monstrosity/aurak-draconian-dsotdq.md)
*Source: Dragonlance: Shadow of the Dragon Queen p. 196*  

Created from the eggs of gold dragons, aurak draconians are the most powerful of draconians, their entire being thrumming with eldritch power. Unlike other draconians, auraks are wingless. This might lull foes into a false sense of security, until the auraks exhale noxious fumes resembling those of their dragon progenitors. Auraks are masterminds and strategists that serve as commanders in the Dragon Armies. They often lead contingents of less powerful draconians. When slain, aurak draconians unleash their inherent magic in a deadly burst of lightning.

## Draconians

Draconians are bipedal monsters born from metallic dragon eggs that have been corrupted by a combination of warped alchemy and the Dragon Queen's foul magic. The Dragon Armies closely guard the secret of the draconians' creation, allowing Krynn's metallic dragons to continue to think their eggs are being held hostage so they don't oppose the Dragon Queen's conquests.

```statblock
"name": "Aurak Draconian (DSotDQ)"
"size": "Medium"
"type": "monstrosity"
"subtype": "sorcerer"
"alignment": "typically  Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"stats":
- !!int "13"
- !!int "14"
- !!int "16"
- !!int "16"
- !!int "11"
- !!int "17"
"speed": "35 ft."
"saves":
  "Charisma": !!int "6"
  "Wisdom": !!int "3"
  "Intelligence": !!int "6"
"skillsaves":
  "Perception": !!int "3"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "truesight 60 ft., passive Perception 13"
"languages": "Common, Draconic"
"cr": "6"
"traits":
- "desc": "The draconian casts one of the following spells, requiring no material\
    \ components and using Charisma as the spellcasting ability (spell save DC 14):\n\
    \nAt will: [invisibility](Mechanics/spells/invisibility.md), [mage hand](Mechanics/spells/mage-hand.md)\n\
    \n1/day: [dominate person](Mechanics/spells/dominate-person.md)\n\n2/day\
    \ each: [dimension door](Mechanics/spells/dimension-door.md), [disguise self](Mechanics/spells/disguise-self.md),\
    \ [sending](Mechanics/spells/sending.md)"
  "name": "Spellcasting"
- "desc": "The draconian radiates a commanding presence in a 20-foot-radius sphere\
    \ centered on itself. A draconian in the aura that can see or hear the aurak can't\
    \ be [charmed](Mechanics/Rules/conditions.md#Charmed) and has advantage on saving\
    \ throws made to avoid or end the [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ condition on itself."
  "name": "Aura of Command"
- "desc": "When the draconian is reduced to 0 hit points, its magical essence lashes\
    \ out as a ball of lightning at the closest creature within 30 feet of it before\
    \ arcing out to up to two other creatures within 15 feet of the first. Each creature\
    \ must make a DC 14 Dexterity saving throw. On a failed save, the creature takes\
    \ 9 (2d8) lightning damage and is [stunned](Mechanics/Rules/conditions.md#Stunned)\
    \ until the end of its next turn. On a successful save, the creature takes half\
    \ as much damage and isn't [stunned](Mechanics/Rules/conditions.md#Stunned)."
  "name": "Death Throes"
"actions":
- "desc": "The draconian makes three Rend or Energy Ray attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d12\
    \ + 2) slashing damage."
  "name": "Rend"
- "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 8\
    \ (1d10 + 3) force damage."
  "name": "Energy Ray"
- "desc": "The draconian exhales a 15-foot cone of noxious gas. Each creature in that\
    \ area must make a DC 14 Constitution saving throw. On a failed save, the creature\
    \ takes 21 (6d6) poison damage and gains 1 level of [exhaustion](Mechanics/Rules/conditions.md#Exhaustion).\
    \ On a successful save, the creature takes half as much damage, doesn't gain [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
    \ and is immune to all draconians' Noxious Breath for 24 hours."
  "name": "Noxious Breath (Recharge 5-6)"
"source":
- "DSotDQ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/DSotDQ/Aurak%20Draconian.webp"
```
^statblock