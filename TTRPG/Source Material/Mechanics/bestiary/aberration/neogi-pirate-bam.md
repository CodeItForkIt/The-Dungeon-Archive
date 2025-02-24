---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/3
- monster/size/small
- monster/type/aberration
statblock: inline
aliases: ["Neogi Pirate"]
---
# [Neogi Pirate](Mechanics\bestiary\aberration/neogi-pirate-bam.md)
*Source: Boo's Astral Menagerie p. 41, Light of Xaryxis*  

Neogi pirates are adult neogi that serve as crew members aboard nightspiders (see the *Astral Adventurer's Guide*) and other neogi-controlled vessels.

Neogi society makes no distinction between individuals, aside from the ability that a given creature has to control others, and they don't comprehend the emotional aspects of existence that humans and similar beings experience. To a neogi, hatred is as foreign a sensation as love, and showing loyalty in the absence of authority is foolishness.

Neogi pirates (and adult neogi in general) mark themselves and those they capture through the use of dyes, transformational magic, and other markings intended to signify rank, achievements, and the identity of the individual's leader. By these signs, neogi can identify each other's place in the hierarchy—and they must defer to those of higher station or risk harsh punishment.

```statblock
"name": "Neogi Pirate (BAM)"
"size": "Small"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "16"
"ac_class": "[breastplate](Mechanics/items/breastplate.md)"
"hp": !!int "33"
"hit_dice": "6d6 + 12"
"stats":
- !!int "6"
- !!int "15"
- !!int "14"
- !!int "13"
- !!int "12"
- !!int "15"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Deep Speech, Undercommon"
"cr": "3"
"traits":
- "desc": "The neogi has advantage on saving throws against being [charmed](Mechanics/Rules/conditions.md#Charmed)\
    \ or [frightened](Mechanics/Rules/conditions.md#Frightened), and magic can't put\
    \ the neogi to sleep."
  "name": "Mental Fortitude"
- "desc": "The neogi can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "The neogi makes one Bite attack and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage plus 14 (4d6) poison damage, and the target must succeed\
    \ on a DC 12 Constitution saving throw or become [poisoned](Mechanics/Rules/conditions.md#Poisoned)\
    \ for 1 minute. A target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Claw"
"source":
- "BAM"
- "LoX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Neogi%20Pirate.webp"
```
^statblock