---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psk
- monster/cr/12
- monster/size/medium
- monster/type/fiend/devil
statblock: inline
aliases: ["Demon"]
---
# [Demon](Mechanics\bestiary\fiend/demon-psk.md)
*Source: Plane Shift: Kaladesh p. 27*  

Demons are artificial creatures, carefully constructed and imbued with aether according to a pattern called the Dark Schematic. Unknown artificers of the ancient past devised this blueprint—perhaps in an attempt to imitate the angels, or possibly to replicate native demons that have since been hunted to extinction. Just as angels embody white mana and the construction phase of the Aether Cycle, demons are ravenous incarnations of black mana that feast on aether. They raid night markets, pillage airships, and break into refinement plants seeking aether to slake their thirst, causing as much destruction as possible in the process. They can thus be imagined as an embodiment of the reclamation stage of the Aether Cycle.

Artificers execute the Dark Schematic only in great desperation, often in the course of seeking power for themselves or revenge against their enemies. The destructive might of demons is hard to control, though, and these creatures have no particular regard for or gratitude toward their creators. As often as not, even an inventor who performs the steps necessary to create a demon with the utmost care suffers the same dismal fate as all its other victims.

Demons resemble angels on a superficial level, wearing ornate masks and headdresses, and often armored. The aether a demon consumes marks its skin with whorls of fiery red, deep purple, or searing yellow.

The statistics of an [erinyes](Mechanics/bestiary/fiend/erinyes.md) work well for demons on Kaladesh, but their weapons deal extra necrotic damage rather than extra poison damage.

```statblock
"name": "Demon (PSK)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](Mechanics/items/plate-armor.md)"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"stats":
- !!int "18"
- !!int "16"
- !!int "18"
- !!int "14"
- !!int "14"
- !!int "18"
"speed": "30 ft., fly 60 ft."
"saves":
  "Charisma": !!int "8"
  "Dexterity": !!int "7"
  "Wisdom": !!int "6"
  "Constitution": !!int "8"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 12"
"languages": "Infernal, telepathy 120 ft."
"cr": "12"
"traits":
- "desc": "The demon's weapon attacks are magical and deal an extra 13 (3d8) necrotic\
    \ damage on a hit (included in the attacks)."
  "name": "Hellish Weapons"
- "desc": "The demon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The demon makes three attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands,\
    \ plus 13 (3d8) necrotic damage."
  "name": "Longsword"
- "desc": "Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage plus 13 (3d8) necrotic damage."
  "name": "Longbow"
"reactions":
- "desc": "The demon adds 4 to its AC against one melee attack that would hit it.\
    \ To do so, the demon must see the attacker and be wielding a melee weapon."
  "name": "Parry"
"source":
- "PSK"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSK/Demon.webp"
```
^statblock