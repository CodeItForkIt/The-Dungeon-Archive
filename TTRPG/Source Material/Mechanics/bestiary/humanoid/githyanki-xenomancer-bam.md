---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/bam
- monster/cr/9
- monster/size/medium
- monster/type/humanoid/druid
- monster/type/humanoid/gith
statblock: inline
aliases: ["Githyanki Xenomancer"]
---
# [Githyanki Xenomancer](Mechanics\bestiary\humanoid/githyanki-xenomancer-bam.md)
*Source: Boo's Astral Menagerie p. 27, Light of Xaryxis*  

A githyanki xenomancer travels to the farthest reaches of Wildspace and the Astral Sea, even visiting worlds of the Material Plane from time to time, to study and catalog creatures it has never encountered before. Friendly contact with sapient creatures can bring the xenomancer's diplomatic skills to the forefront, while hostile contact becomes a test of the xenomancer's survival skills.

Sometimes a xenomancer's research requires that a specimen be captured and imprisoned (to study its behavior) or killed and dissected (to study or harvest its insides). Many xenomancers prefer to do this work in their laboratories on the Astral Plane.

```statblock
"name": "Githyanki Xenomancer (BAM)"
"size": "Medium"
"type": "humanoid"
"subtype": "druid, gith"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "157"
"hit_dice": "21d8 + 63"
"stats":
- !!int "14"
- !!int "18"
- !!int "17"
- !!int "15"
- !!int "18"
- !!int "13"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "8"
  "Constitution": !!int "7"
"skillsaves":
  "Nature": !!int "6"
  "Animal Handling": !!int "8"
  "Perception": !!int "8"
  "Survival": !!int "8"
"senses": "passive Perception 18"
"languages": "Gith plus any four languages"
"cr": "9"
"traits":
- "desc": "The githyanki casts one of the following spells, requiring no spell components\
    \ and using Wisdom as the spellcasting ability (spell save DC 16):\n\nAt will:\
    \ [druidcraft](Mechanics/spells/druidcraft.md), [light](Mechanics/spells/light.md),\
    \ [mage hand](Mechanics/spells/mage-hand.md) (the hand is invisible)\n\n1/day\
    \ each: [dominate monster](Mechanics/spells/dominate-monster.md), [forcecage](Mechanics/spells/forcecage.md),\
    \ [plane shift](Mechanics/spells/plane-shift.md), [telekinesis](Mechanics/spells/telekinesis.md)\n\
    \n2/day each: [invisibility](Mechanics/spells/invisibility.md) (self only),\
    \ [pass without trace](Mechanics/spells/pass-without-trace.md) (self only)"
  "name": "Spellcasting (Psionics)"
"actions":
- "desc": "The githyanki makes three Staff attacks, three Telekinetic Bolt attacks,\
    \ or a combination thereof."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage when used with\
    \ two hands, plus 14 (4d6) psychic damage."
  "name": "Staff"
- "desc": "Ranged Spell Attack: +8 to hit, range 60 ft., one target. Hit: 20\
    \ (3d10 + 4) force damage."
  "name": "Telekinetic Bolt"
"bonus_actions":
- "desc": "The githyanki teleports, along with any equipment it is wearing or carrying,\
    \ up to 30 feet to an unoccupied space it can see."
  "name": "Astral Step (Recharge 4-6)"
"source":
- "BAM"
- "LoX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/BAM/Githyanki%20Xenomancer.webp"
```
^statblock