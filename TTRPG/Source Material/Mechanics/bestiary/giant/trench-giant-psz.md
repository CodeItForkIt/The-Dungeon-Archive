---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/8
- monster/size/huge
- monster/type/giant
statblock: inline
aliases: ["Trench Giant"]
---
# [Trench Giant](Mechanics\bestiary\giant/trench-giant-psz.md)
*Source: Plane Shift: Zendikar p. 30*  

Zendikar's giants are enormous humanoids that live in tight-knit tribes as far as possible from the settlements of other races. Compared to ogres and minotaurs, they are civilized and intelligent, though they are wilder than the smaller humanoid races.

Three major groupings of giants inhabit three of Zendikar's continents. In the mountains of Akoum, the giants of the Boulderfoot tribe have a well-earned reputation for trampling their enemies underfoot (hence their name). In the Skyfang Mountains of Murasa, the giants of the Shatterskull tribe are rough brigands who often extort "tolls" from travelers trying to navigate the treacherous pass that shares the tribe's name. The Boulderfoot and Shatterskull giants are [stone giants](Mechanics/bestiary/giant/stone-giant.md) in D&D terms.

In Ondu, the giants of the Turntimber tribe live in the forest of the same name. They hunt baloths and other large game, living in close harmony with the woodland. Their druids are the only giants of Zendikar that are inclined toward magic. Some legends hold that the Turntimber giants are unrelated to the other giant tribes, but were originally druids who became giants only after years of living among the twisted trees. Elsewhere on Ondu, in the Makindi Trenches, a handful of deformed giants called trench giants scale the canyon walls looking for prey. They are solitary and do not think of themselves as members of a tribe. In fact, they are outcasts of the Turntimber tribe, banished because the mana of the forest warped their bodies and their hearts. The giants of the Turntimber tribe are similar to [cloud giants](Mechanics/bestiary/giant/cloud-giant.md), and the trench giants can be considered [fomorians](Mechanics/bestiary/giant/fomorian.md).

```statblock
"name": "Trench Giant (PSZ)"
"size": "Huge"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "149"
"hit_dice": "13d12 + 65"
"stats":
- !!int "23"
- !!int "10"
- !!int "20"
- !!int "9"
- !!int "14"
- !!int "6"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "8"
"senses": "darkvision 120 ft., passive Perception 18"
"languages": "Giant, Undercommon"
"cr": "8"
"actions":
- "desc": "The giant attacks twice with its greatclub or makes one greatclub attack\
    \ and uses Evil Eye once."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 19\
    \ (3d8 + 6) bludgeoning damage."
  "name": "Greatclub"
- "desc": "The giant magically forces a creature it can see within 60 feet of it to\
    \ make a DC 14 Charisma saving throw. The creature takes 27 (6d8) psychic damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Evil Eye"
- "desc": "With a stare, the giant uses Evil Eye, but on a failed save, the creature\
    \ is also cursed with magical deformities. While deformed, the creature has its\
    \ speed halved and has disadvantage on ability checks, saving throws, and attacks\
    \ based on Strength or Dexterity.\n\nThe transformed creature can repeat the saving\
    \ throw whenever it finishes a long rest, ending the effect on a success."
  "name": "Curse of the Evil Eye (Recharges after a Short or Long Rest)"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Trench%20Giant.webp"
```
^statblock