---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/21
- monster/environment/grassland
- monster/environment/mountain
- monster/size/gargantuan
- monster/type/dragon
statblock: inline
aliases: ["Ancient Wind Dragon"]
---
# [Ancient Wind Dragon](Mechanics\bestiary\dragon/ancient-wind-dragon-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 133*  

*Howling wind encircles the dragon, filling and pushing its wings without the need for them to beat.*Wind dragons view anywhere touched by air as their property, and mortals point to them as the epitome of arrogance. Their narcissism is not without reason, for awe‑inspiring power supports their claims of rightful control. To the dragons of the shifting gales, strength is the ultimate arbiter.

## Braggarts and Bullies

Wind dragons number among the greatest bullies and worst tyrants of mortal creatures. The sometimes-foolhardy creatures take offense at any perceived challenge and pleasure in humiliating rivals. They claim great swathes of territory but care little for its governance—they perceive mortals in that territory as possessions. Vassals receive only dubious protection in exchange for their loyalty. A wind dragon might seek bloody vengeance for the murder of a follower, but it's unlikely to go to any length to prevent the loss of that life in the first place.

## Lords of the Far Horizons

Some believe that the dragons of the winds claim much more than they are capable of controlling or patrolling. Because they so love altitude, they prefer to rule and meet with earth-bound supplicants at the highest point available: the summit of a great mountain or atop a towering monument erected by fearful slaves. But these dragons are also driven by wanderlust and roam far from their thrones. They return eventually, ready to subjugate new generations and press a tyrannical claw on the neck of anyone who questions their right to rule.

## Perpetual Infighting

These wandering tyrants are even more territorial among their own kind than they are among groundlings. Simple trespass by one wind dragon into the territory of another can lead to a battle to the death. Thus, their numbers never grow large, and the weakest among them are frequently culled.

## Portable Hoards

Wind dragons' hoards typically consist of only a few truly valuable relics. Other dragons might sleep on a bed of coins, but common things bore wind dragons. While all true dragons desire and display great wealth, wind dragons concentrate their riches in a small number of notable trophies or unique historic items—often quite portable.

## A Wind Dragon's Lair

Wind dragons make their lairs where they can overlook and dominate their claims, but the location must be remote enough that inhabitants can't pester them with requests for protection or justice. As they have little to fear from the elements, a shallow cave high on an exposed mountain face is ideal. Wind dragons enjoy heights dotted with rock spires and tall, sheer cliffs. They perch in the howling wind and catch updrafts and downdrafts sweeping through canyons and tearing across crags.

```statblock
"name": "Ancient Wind Dragon (ToB1-2023)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "351"
"hit_dice": "19d20 + 152"
"stats":
- !!int "28"
- !!int "16"
- !!int "26"
- !!int "18"
- !!int "17"
- !!int "20"
"speed": "30 ft., fly 120 ft. (hover)"
"saves":
  "Charisma": !!int "12"
  "Dexterity": !!int "10"
  "Wisdom": !!int "10"
  "Constitution": !!int "15"
"skillsaves":
  "Intimidation": !!int "12"
  "Stealth": !!int "10"
  "Perception": !!int "17"
  "Acrobatics": !!int "17"
"damage_resistances": "cold"
"damage_immunities": "lightning"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 27"
"languages": "Common, Draconic, Primordial"
"cr": "21"
"traits":
- "desc": "The dragon ignores difficult terrain, and magical effects can't reduce\
    \ its speed or cause it to be [restrained](Mechanics/Rules/conditions.md#Restrained).\
    \ It can spend 5 feet of movement to escape from nonmagical restraints or being\
    \ [grappled](Mechanics/Rules/conditions.md#Grappled)."
  "name": "Freedom of Movement"
- "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The dragon can see through areas obscured by fog, mist, clouds, or precipitation."
  "name": "Storm Sight"
- "desc": "Gale force winds rage around the dragon's body. Arrows, bolts, and other\
    \ ordinary projectiles launched at the dragon are deflected upward and automatically\
    \ miss. Boulders hurled by giants or siege engines, and similar projectiles, are\
    \ unaffected."
  "name": "Whirling Winds"
"actions":
- "desc": "The wind dragon uses its Frightful Presence. It then makes one Bite attack\
    \ and two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one target. Hit: 20\
    \ (2d10 + 9) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. it: 16 (2d6\
    \ + 9) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +16 to hit, reach 20 ft., one target. Hit: 18\
    \ (2d8 + 9) bludgeoning damage."
  "name": "Tail"
- "desc": "Each creature of the dragon's choice that is within 120 feet of the dragon\
    \ and aware of it must succeed on a DC 20 Wisdom saving throw or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success. If a creature's saving throw\
    \ is successful or the effect ends for it, the creature is immune to the dragon's\
    \ Frightful Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "The dragon exhales a blast of stormy wind in a 90-foot cone. Each creature\
    \ in that area must make a DC 23 Strength saving throw. On a failure, a creature\
    \ takes 36 (8d8) bludgeoning damage and 36 (8d8) lightning damage and is pushed\
    \ up to 45 feet away from the dragon and knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ On a success, a creature takes half the damage and isn't pushed or knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ Nonmagical flames in the area are extinguished."
  "name": "Tempest Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "The dragon makes a Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ check."
  "name": "Detect"
- "desc": "The dragon makes a Tail attack."
  "name": "Tail Attack"
- "desc": "The dragon beats its wings. Each creature within 15 feet of the dragon\
    \ must succeed on a DC 24 Dexterity saving throw or take 16 (2d6 + 9) bludgeoning\
    \ damage and be knocked [prone](Mechanics/Rules/conditions.md#Prone). The dragon\
    \ can then fly up to half its flying speed."
  "name": "Wing Attack (Costs 2 Actions)"
"lair_actions":
- "desc": "On initiative count 20 (losing initiative ties), the dragon takes a lair\
    \ action to cause one of the following effects; the dragon can't use the same\
    \ effect two rounds in a row:"
  "name": ""
- "desc": "- Air Blast. A torrent of wind blasts outward in a 60-foot‑radius sphere\
    \ centered on a point the dragon can see within 120 feet of it. Each creature\
    \ in that area must succeed on a DC 15 Strength saving throw or be knocked prone\
    \ and stunned until the end of its next turn. Flying creatures, other than wind\
    \ dragons, have disadvantage on the saving throw.  \n- Blinding Wind. Sand\
    \ and dust swirls up from the ground in a cylinder that is 30 feet tall with a\
    \ 20-foot radius, centered on a point the dragon can see within 120 feet of it.\
    \ The area within the cylinder is difficult terrain. A creature that enters the\
    \ cylinder for the first time on a turn or starts its turn there must succeed\
    \ on a DC 15 Dexterity saving throw or be blinded until the end of its next turn.\
    \ The cylinder of sand and dust lasts until the dragon uses this lair action again\
    \ or until the dragon dies.  \n- Gale Force Smash. A blast of wind slams into\
    \ a surface of the lair and sends fragments of ice and stone flying out from a\
    \ point on the ground, wall, or ceiling the dragon can see within 120 feet of\
    \ it. Each creature within 15 feet of that point must make a DC 15 Dexterity saving\
    \ throw, taking 18 (4d8) bludgeoning damage on a failed save, or half as much\
    \ damage on a successful one.  "
  "name": ""
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Ancient%20Wind%20Dragon.webp"
```
^statblock

## Environment

grassland, mountain