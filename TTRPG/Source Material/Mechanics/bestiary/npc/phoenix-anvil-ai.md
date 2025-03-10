---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ai
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/human
statblock: inline
aliases: ["Phoenix Anvil"]
---
# [Phoenix Anvil](Mechanics\bestiary\npc/phoenix-anvil-ai.md)
*Source: Acquisitions Incorporated p. 206*  

The "B" Team hoards person, Phoenix Anvil is a servant of Waukeen and a soft-spoken sort. Really soft. Like, he talks so infrequently that even he might not recognize his own voice. Phoenix comes from the streets, where he grew up a fighter until a job sweeping the steps of a small temple of Waukeen showed him a new path. His hunger for coin as an adventurer is thus guided by his knowledge of what it is to do without.

More of an object individual than a people person, Phoenix is obsessively dedicated to the franchise's assets and accounts. Thankfully, he includes his fellow members among those assets, making him fiercely loyal. However, Oak Truestrike is the only team member he's ever really warmed to, which doesn't do either of them any good.

```statblock
"name": "Phoenix Anvil (AI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "[chain mail](Mechanics/items/chain-mail.md), [shield](Mechanics/items/shield.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "15"
- !!int "10"
- !!int "12"
- !!int "13"
- !!int "16"
- !!int "13"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Religion": !!int "3"
  "Performance": !!int "3"
  "Persuasion": !!int "3"
"senses": "passive Perception 13"
"languages": "Common, Elvish"
"cr": "2"
"traits":
- "desc": "Phoenix is a 4th-level spellcaster. His spellcasting ability is Wisdom\
    \ (spell save DC 13, +5 to hit with spell attacks). He has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [guidance](Mechanics/spells/guidance.md),\
    \ [light](Mechanics/spells/light.md), [mending](Mechanics/spells/mending.md),\
    \ [sacred flame](Mechanics/spells/sacred-flame.md)\n\n1st level (4 slots):\
    \ [bane](Mechanics/spells/bane.md), [cure wounds](Mechanics/spells/cure-wounds.md),\
    \ [guiding bolt](Mechanics/spells/guiding-bolt.md)\n\n2nd level (3 slots):\
    \ [hold person](Mechanics/spells/hold-person.md), [spiritual weapon](Mechanics/spells/spiritual-weapon.md)"
  "name": "Spellcasting"
- "desc": "As a bonus action, Phoenix causes his shield to flare with divine light.\
    \ Each creature of his choice within 30 feet of him must succeed on a DC 13 Wisdom\
    \ saving throw or be [blinded](Mechanics/Rules/conditions.md#Blinded) for 1 minute.\
    \ A creature can repeat the save at the end of each of its turns, ending the effect\
    \ on itself with a success."
  "name": "Divine Display (1/Day)"
"actions":
- "desc": "Phoenix makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage, and the target must succeed on a DC 12 Strength saving\
    \ throw or be pushed 5 feet."
  "name": "Warhammer"
"source":
- "AI"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/AI/Phoenix%20Anvil.webp"
```
^statblock