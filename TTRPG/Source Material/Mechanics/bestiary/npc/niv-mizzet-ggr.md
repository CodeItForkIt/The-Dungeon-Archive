---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/26
- monster/size/gargantuan
- monster/type/dragon
statblock: inline
aliases: ["Niv-Mizzet"]
---
# [Niv-Mizzet](Mechanics\bestiary\npc/niv-mizzet-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 241*  

Possessed of arrogance and vanity that matches his vast intellect and tremendous power, Niv-Mizzet is the ancient dragon who founded and continues to control the Izzet League. From his private laboratory at the top of the Izzet guildhall, Niv-Mizzet directs the research and experiments of his countless underlings. He coordinates a tremendous number of apparently unrelated projects, working toward some mysterious end.

There can be little doubt that this ancient dragon is one of the most intelligent beings on Ravnica and one of the world's most powerful spellcasters. He is just as acquisitive as any dragon, but his treasure is scientific and magical knowledge. His ambition is a looming threat in the minds of all the other guildmasters, but confronting him directly is almost unthinkable thanks to the combination of his awesome magical power and the sheer physical threat of a fire-breathing, swordtoothed dragon.

```statblock
"name": "Niv-Mizzet (GGR)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Neutral"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "370"
"hit_dice": "19d20 + 171"
"stats":
- !!int "29"
- !!int "14"
- !!int "29"
- !!int "30"
- !!int "17"
- !!int "25"
"speed": "40 ft., climb 30 ft., fly 80 ft."
"saves":
  "Wisdom": !!int "11"
  "Intelligence": !!int "18"
  "Constitution": !!int "17"
"skillsaves":
  "Insight": !!int "11"
  "Perception": !!int "11"
  "Arcana": !!int "18"
"damage_resistances": "cold, psychic, thunder"
"damage_immunities": "fire, lightning"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "26"
"traits":
- "desc": "Niv-Mizzet is a 20th-level Izzet spellcaster. His spellcasting ability\
    \ is Intelligence (spell save DC 26, +18 to hit with spell attacks). He has\
    \ the following wizard spells prepared:\n\nCantrips (at will): [fire bolt](Mechanics/spells/fire-bolt.md),\
    \ [light](Mechanics/spells/light.md), [prestidigitation](Mechanics/spells/prestidigitation.md),\
    \ [ray of frost](Mechanics/spells/ray-of-frost.md), [shocking grasp](Mechanics/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [detect magic](Mechanics/spells/detect-magic.md), [magic\
    \ missile](Mechanics/spells/magic-missile.md), [shield](Mechanics/spells/shield.md),\
    \ [thunderwave](Mechanics/spells/thunderwave.md), [unseen servant](Mechanics/spells/unseen-servant.md)\n\
    \n2nd level (3 slots): [blur](Mechanics/spells/blur.md), [enlarge/reduce](Mechanics/spells/enlarge-reduce.md),\
    \ [flaming sphere](Mechanics/spells/flaming-sphere.md), [hold person](Mechanics/spells/hold-person.md),\
    \ [scorching ray](Mechanics/spells/scorching-ray.md)\n\n3rd level (3 slots):\
    \ [counterspell](Mechanics/spells/counterspell.md), [fireball](Mechanics/spells/fireball.md),\
    \ [lightning bolt](Mechanics/spells/lightning-bolt.md), [slow](Mechanics/spells/slow.md)\n\
    \n4th level (3 slots): [confusion](Mechanics/spells/confusion.md), [dimension\
    \ door](Mechanics/spells/dimension-door.md), [fabricate](Mechanics/spells/fabricate.md)\n\
    \n5th level (2 slots): [conjure elemental](Mechanics/spells/conjure-elemental.md),\
    \ [polymorph](Mechanics/spells/polymorph.md), [wall of fire](Mechanics/spells/wall-of-fire.md),\
    \ [wall of force](Mechanics/spells/wall-of-force.md)\n\n6th level (1 slots):\
    \ [chain lightning](Mechanics/spells/chain-lightning.md), [disintegrate](Mechanics/spells/disintegrate.md),\
    \ [true seeing](Mechanics/spells/true-seeing.md)\n\n7th level (1 slots): [project\
    \ image](Mechanics/spells/project-image.md), [reverse gravity](Mechanics/spells/reverse-gravity.md),\
    \ [teleport](Mechanics/spells/teleport.md)\n\n8th level (1 slots): [control\
    \ weather](Mechanics/spells/control-weather.md), [maze](Mechanics/spells/maze.md),\
    \ [power word stun](Mechanics/spells/power-word-stun.md)\n\n9th level (1 slots):\
    \ [prismatic wall](Mechanics/spells/prismatic-wall.md)"
  "name": "Spellcasting"
- "desc": "If Niv-Mizzet fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Niv-Mizzet can maintain [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ on two different spells at the same time. In addition, he has advantage on saving\
    \ throws to maintain [concentration](Mechanics/Rules/conditions.md#Concentration)\
    \ on spells."
  "name": "Locus of the Firemind"
- "desc": "Niv-Mizzet has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "When Niv-Mizzet casts a spell that deals damage, he can change the spell's\
    \ damage to cold, fire, force, lightning, or thunder."
  "name": "Master Chemister"
"actions":
- "desc": "Niv-Mizzet makes three attacks: one with his bite and two with his claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 15 ft., one target. Hit: 18\
    \ (2d8 + 9) piercing damage plus 14 (4d6) fire damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d4 + 9) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +17 to hit, reach 20 ft., one target. Hit: 16\
    \ (2d6 + 9) bludgeoning damage."
  "name": "Tail"
- "desc": "Niv-Mizzet exhales fire in a 90-foot cone. Each creature in that area must\
    \ make a DC 25 Dexterity saving throw, taking 91 (26d6) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "Niv-Mizzet casts one of his cantrips."
  "name": "Cantrip"
- "desc": "Niv-Mizzet makes a tail attack."
  "name": "Tail Attack"
- "desc": "Niv-Mizzet beats his wings. Each creature within 15 feet of him must succeed\
    \ on a DC 25 Dexterity saving throw or take 14 (2d4 + 9) bludgeoning damage\
    \ and be knocked [prone](Mechanics/Rules/conditions.md#Prone). Niv-Mizzet can\
    \ then fly up to half his flying speed."
  "name": "Wing Attack (Costs 2 Actions)"
- "desc": "Niv-Mizzet regains a spell slot of 3rd level or lower."
  "name": "Dracogenius (Costs 3 Actions)"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Niv-Mizzet.webp"
```
^statblock