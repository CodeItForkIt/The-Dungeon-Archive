---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/22
- monster/environment/mountain
- monster/size/gargantuan
- monster/type/dragon
statblock: inline
aliases: ["Ancient Mithral Dragon"]
---
# [Ancient Mithral Dragon](Mechanics\bestiary\dragon/ancient-mithral-dragon-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 120*  

*Light glints off the dragon's glossy scales, shining silver-white. Its tiny wings folded flush against its body open like a fan and expose shimmering, diaphanous membranes. Its narrow head, with bare slits for its eyes and nostrils, sits at the end of a slender neck atop an impossibly thin frame*.

## Rage in Youth

Younger mithral dragons raid and pillage as heavily as any chromatic dragon, driven largely by greed to acquire a worthy hoard, though they are less likely to kill for sport or out of cruelty. In adulthood and old age, however, mithral dragons are less concerned with material wealth and more inclined to value friendship, knowledge, and a peaceful life pursuing interesting goals.

## Peacemakers

Adult and older mithral dragons are diplomats and arbitrators by temperament (some dragons cynically call them referees). They enjoy bringing some peace to warring factions. Among all dragons, their strict neutrality and ability to negate magic make them well suited to these vital roles.

> [!note] Mithral Dragons in Midgard
> 
> Mithral dragons are rebellious dragons who once sought to make peace between chromatic and metallic dragons. Having failed in that, they declared themselves neutral and now seek opportunities to make peace elsewhere. They are the only dragons that advocate against the perpetual war of the Dragon Empire, and occasionally serve as mercenaries against the Mharoti.
^mithral-dragons-in-midgard

## A Mithral Dragon's Lair

Mithral dragons are attracted to lairs near humanoid civilization, where petitioners can reach them if their diplomatic services are needed. Unlike other dragons, mithral dragons forsake lairing upon remote natural caverns or cliffs, preferring to dwell in impressive structures of metal and stone—with a particular fondness for towers. More than once, a mithral dragon has accepted the deed to a fortress, palace, or castle as payment for brokering peace between warring factions.

Curiously, mithral dragons don't hoard coins and precious metals as most dragons do. Other curiosities fill their lair, like fine paintings, marble statues, rare tomes, stained glass, and anything made of mithral—rare treasures procured over a lifetime of interacting with mortal creatures.

```statblock
"name": "Ancient Mithral Dragon (ToB1-2023)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "490"
"hit_dice": "28d20 + 196"
"stats":
- !!int "12"
- !!int "26"
- !!int "25"
- !!int "20"
- !!int "21"
- !!int "20"
"speed": "40 ft., fly 80 ft."
"saves":
  "Charisma": !!int "12"
  "Dexterity": !!int "15"
  "Wisdom": !!int "12"
  "Constitution": !!int "14"
"skillsaves":
  "Stealth": !!int "15"
  "Insight": !!int "12"
  "Perception": !!int "19"
  "History": !!int "12"
  "Persuasion": !!int "12"
"damage_resistances": "force"
"damage_immunities": "slashing"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 29"
"languages": "all, telepathy 120 ft."
"cr": "22"
"traits":
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The dragon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "If the dragon succeeds on a saving throw by 5 or more against a spell that\
    \ targets only it, the dragon is unaffected, and the spell is reflected back at\
    \ the caster as though it originated from the dragon, turning the caster into\
    \ the target."
  "name": "Mithral Scales"
"actions":
- "desc": "The dragon uses its Frightful Presence. It then makes one Bite attack and\
    \ two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +15 to hit, reach 15 ft., one target. Hit: 19\
    \ (2d10 + 8) piercing damage. Instead of dealing damage, the dragon can end\
    \ one magical effect of its choice of 7th level or lower on the target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +15 to hit, reach 10 ft., one target. Hit: 15\
    \ (2d6 + 8) slashing damage, and if the target isn't a Construct or Undead,\
    \ it must succeed on a DC 23 Constitution saving throw or lose 10 3d6 hp at\
    \ the start of each of its turns as a piece of metallic claw breaks off in the\
    \ wound. Any creature can take an action to remove the claw with a successful\
    \ DC 16 Wisdom ([Medicine](Mechanics/Rules/skills.md#Medicine)) check. The claw\
    \ pops out of the wound if the target receives magical healing."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +15 to hit, reach 20 ft., one target. Hit: 17\
    \ (2d8 + 8) bludgeoning damage."
  "name": "Tail"
- "desc": "Each creature of the dragon's choice that is within 120 feet of the dragon\
    \ and aware of it must succeed on a DC 20 Wisdom saving throw or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. A creature can repeat the saving throw at the end of its turns,\
    \ ending the effect on itself on a success. If a creature's saving throw is successful\
    \ or the effect ends for it, the creature is immune to the dragon's Frightful\
    \ Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "The mithral dragon spits metallic shards in a 90-foot cone. Each creature\
    \ in that area must succeed on a DC 22 Dexterity saving throw, taking 73 (21d6)\
    \ slashing damage on a failed save, or half as much damage on a successful one.\
    \ The area becomes difficult terrain for 1 minute, then the shards dissolve into\
    \ wisps of silvery smoke. When a creature moves into or within the area, it takes\
    \ 7 (2d6) slashing damage for every 5 feet it travels."
  "name": "Shard Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon makes a Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The dragon makes a Tail attack."
  "name": "Tail Attack"
- "desc": "The dragon beats its wings. Each creature within 10 feet of the dragon\
    \ must succeed on a DC 23 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning\
    \ damage and be knocked [prone](Mechanics/Rules/conditions.md#Prone). The dragon\
    \ can then fly up to half its flying speed."
  "name": "Wing Attack (Costs 2 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the dragon takes a lair\
    \ action to cause one of the following effects; the dragon can't use the same\
    \ effect two rounds in a row:"
  "name": ""
- "desc": "- Impaling Spikes. Metallic spikes sprout from the ground beneath one\
    \ creature the dragon can see within 120 feet of it. The target must make a DC\
    \ 15 Dexterity saving throw. On a failure, the creature takes 10 (3d6) piercing\
    \ damage and is restrained as it is impaled on the magical spikes. On a success,\
    \ a creature takes half the damage and isn't restrained. A creature, including\
    \ the restrained target, can take its action to free the restrained target by\
    \ succeeding on a DC 15 Strength check to break the spikes.  \n- Shimmering\
    \ Scales. Light within the lair bends toward the dragon, reflecting brilliantly\
    \ off its scales. Each creature within 30 feet of the dragon and that can see\
    \ it must succeed on a DC 15 Dexterity saving throw or be blinded until the end\
    \ of its next turn.  \n- Wave of Peace. A pulse of calming energy washes over\
    \ the lair. Each hostile creature the dragon can see within 120 feet of it must\
    \ succeed on a DC 15 Charisma saving throw or become indifferent about creatures\
    \ of the dragon's choice that it is hostile toward for 1 minute. This indifference\
    \ ends if the target is attacked or harmed by a spell or if it witnesses any of\
    \ its friends being harmed. When the effect ends, the creature can choose to become\
    \ hostile again.  "
  "name": ""
"regional_effects":
- "desc": "The region containing a legendary mithral dragon's lair is warped by the\
    \ dragon's magic, which creates one or more of the following effects:"
  "name": ""
- "desc": "- Calming Air. Humanoids within 6 miles of the lair experience feelings\
    \ of peace and are less prone to mood swings. Dragons within 6 miles of the lair\
    \ experience the opposite effect, becoming plagued by anxiety and irritability.\
    \  \n- Peaceful Realm. When a Dragon or Humanoid within 3 miles of the lair\
    \ attempts to commit an act of violence against a Dragon or Humanoid and that\
    \ act of violence isn't in self-defense, that creature must succeed on a DC 13\
    \ Wisdom saving throw or be unable to commit acts of violence, other than self-defense,\
    \ for 1 minute. The dragon can choose to suppress this effect for any creature.\
    \  \n- Shining Mithral. Objects made from metals other than mithril appear\
    \ dull and feel heavy while within 1 mile of the dragon's lair.  "
  "name": ""
- "desc": "If the dragon dies, these effects fade over the course of 1d10 days."
  "name": ""
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ancient%20Mithral%20Dragon.webp"
```
^statblock

## Environment

mountain