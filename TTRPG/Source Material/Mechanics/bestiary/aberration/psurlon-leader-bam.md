---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/6
- monster/size/medium
- monster/type/aberration
statblock: inline
aliases: ["Psurlon Leader"]
---
# [Psurlon Leader](Mechanics\bestiary\aberration/psurlon-leader-bam.md)
*Source: Boo's Astral Menagerie p. 45*  

One out of every hundred psurlons is a mutant with two heads, one at each end of its body, and a superior intellect. Other psurlons look to the two-headed ones for leadership.

```statblock
"name": "Psurlon Leader (BAM)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "[mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "127"
"hit_dice": "17d8 + 51"
"stats":
- !!int "16"
- !!int "14"
- !!int "16"
- !!int "20"
- !!int "11"
- !!int "7"
"speed": "30 ft."
"saves":
  "Charisma": !!int "1"
  "Wisdom": !!int "3"
"skillsaves":
  "Perception": !!int "6"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 16"
"languages": "Deep Speech, telepathy 120 ft."
"cr": "6"
"traits":
- "desc": "The psurlon casts one of the following spells, requiring no spell components\
    \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\n1/day\
    \ each: [dimension door](Mechanics/spells/dimension-door.md), [suggestion](Mechanics/spells/suggestion.md)\n\
    \n2/day each: [disguise self](Mechanics/spells/disguise-self.md), [mage armor](Mechanics/spells/mage-armor.md)\
    \ (self only)"
  "name": "Spellcasting (Psionics)"
- "desc": "Magic can't read the psurlon's thoughts or put the psurlon to sleep."
  "name": "Aberrant Mind"
- "desc": "The psurlon has advantage on saving throws it makes to avoid or end the\
    \ [frightened](Mechanics/Rules/conditions.md#Frightened), [stunned](Mechanics/Rules/conditions.md#Stunned),\
    \ or [unconscious](Mechanics/Rules/conditions.md#Unconscious) condition on itself.\
    \ While one of the psurlon's heads is asleep, its other head is awake."
  "name": "Two Heads"
"actions":
- "desc": "The psurlon makes two Bite attacks and two Claw attacks. It can also use\
    \ Pacify (if available) or Psychic Crush."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 7\
    \ (1d8 + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) slashing damage."
  "name": "Claw"
- "desc": "The psurlon targets one creature it can see within 120 feet of itself.\
    \ The target must succeed on a DC 16 Wisdom saving throw or fall [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ for 10 minutes. The condition ends if the target takes any damage or if another\
    \ creature uses its action to shake the target awake."
  "name": "Pacify (Recharge 5-6)"
- "desc": "The psurlon targets one creature it can see within 120 feet of itself.\
    \ The target must make a DC 16 Wisdom saving throw, taking 21 (3d10 + 5) psychic\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Psychic Crush"
"source":
- "BAM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Psurlon%20Leader.webp"
```
^statblock