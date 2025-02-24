---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/4
- monster/size/large
- monster/type/ooze
statblock: inline
aliases: ["Plasmoid Boss"]
---
# [Plasmoid Boss](Mechanics\bestiary\ooze/plasmoid-boss-bam.md)
*Source: Boo's Astral Menagerie p. 42*  

On occasion, due to some biological anomaly, a plasmoid balloons in size upon reaching adulthood (around the age of twenty years). Plasmoids who use their increased size and strength to boss around smaller, weaker creatures can easily end up in positions of power, surrounded by loyal underlings, sycophants, and would-be usurpers. A plasmoid boss might be the master of a guild, the leader of a criminal enterprise, the lord of a plasmoid community, or the captain of a spelljamming ship. Regardless of the roles they secure for themselves, plasmoid bosses need no small amount of charm and wit, in addition to their strength and size, to stay in power for long.

```statblock
"name": "Plasmoid Boss (BAM)"
"size": "Large"
"type": "ooze"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "82"
"hit_dice": "11d10 + 22"
"stats":
- !!int "18"
- !!int "12"
- !!int "14"
- !!int "14"
- !!int "13"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Constitution": !!int "4"
"skillsaves":
  "Intimidation": !!int "4"
  "Deception": !!int "4"
  "Persuasion": !!int "4"
"damage_resistances": "acid, poison"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common"
"cr": "4"
"traits":
- "desc": "The plasmoid can squeeze through a space as narrow as 1 inch wide, provided\
    \ it is wearing and carrying nothing. It has advantage on ability checks it makes\
    \ to initiate or escape a grapple."
  "name": "Amorphous"
- "desc": "The plasmoid can hold its breath for 1 hour."
  "name": "Hold Breath"
"actions":
- "desc": "The plasmoid makes three Pseudopod attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit (with advantage if the plasmoid has\
    \ one or more allies within 10 feet of itself), reach 10 ft., one target. Hit:\
    \ 11 (2d6 + 4) bludgeoning damage."
  "name": "Pseudopod"
"reactions":
- "desc": "The plasmoid halves the damage that it takes from an attack that hits it.\
    \ The plasmoid must be able to see the attacker."
  "name": "Uncanny Dodge"
"source":
- "BAM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Plasmoid%20Boss.webp"
```
^statblock